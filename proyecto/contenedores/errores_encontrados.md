# Errores encontrados en docker-compose.yml y prometheus.yml

## 1. Redes

- **Error:** El servicio `redis` estaba configurado en la red `monitoring-network`,
  pero en la sección `networks` solo existía la red `monitoring`.
- **Detección:** Al ejecutar `docker-compose up -d`, Docker devolvía un error
  indicando que la red `monitoring-network` no existía.
- **Solución:** Cambiar la red de `redis` a `monitoring`.

## 2. Volúmenes de Grafana

- **Error:** El servicio `grafana` montaba el volumen `grafana-data`,
  pero en la sección `volumes` se declaraba `grafana-storage`.
- **Detección:** `docker-compose config` mostraba la inconsistencia en el nombre del volumen.
- **Solución:** Unificar el nombre del volumen usando `grafana-storage` en ambos lados.

## 3. Comando de Loki

- **Error:** La línea `command: -config.file=/etc/loki/local-config.yaml`
  podía interpretarse de forma incorrecta.
- **Solución:** Cambiarla por una lista:
  `command: ["-config.file=/etc/loki/local-config.yaml"]`.

## 4. Configuración de Prometheus

- **Error intencional:** El archivo `prometheus.yml` tenía un job para `nginx`
  con target `nginx:9113`, pero la imagen `nginx:alpine` no expone métricas en ese puerto.
- **Detección:** En la UI de Prometheus, el target aparecía como `DOWN`.
- **Solución:** Comentar el job de `nginx` para la entrega final.
  (Alternativa sería agregar un exporter, pero no era requerido.)
