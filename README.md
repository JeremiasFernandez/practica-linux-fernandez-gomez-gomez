# 🐧 Trabajo Práctico – Administración de Sistemas Linux  
## UTN – Facultad Regional Avellaneda

Este repositorio contiene el Trabajo Práctico grupal de **Administración de Sistemas Linux**, utilizando **Vagrant** para la creación y automatización de entornos virtuales. Incluye el Vagrantfile, scripts de provisioning y la documentación técnica del proyecto.

---

## 👥 Integrantes
- **Jeremias Fernandez** - [GitHub](https://github.com/JeremiasFernandez)
- **Elizabet Antonela Gomez** - [GitHub](https://github.com/antokernel)
- **Victor Gomez** - [GitHub](https://github.com/alejandrogomez2004)

---

## 📁 Contenido del repositorio
- `Vagrantfile`
- Scripts de configuración y provisioning
- Documentación del trabajo

---

## Trabajo realizado

- Información de la VM:
  - `proyecto/informacion/ip_vm.txt`
  - `proyecto/informacion/fastfetch.txt`
- Permisos y usuarios:
  - `proyecto/permisos/usuariosGOMEZE.txt`
  - directorios `confidencial/` y `publico/` con permisos configurados
  - `proyecto/permisos/verificacionpermisos.txt`
- LVM:
  - `proyecto/lvm/lvm-gomeze.txt`
  - `proyecto/lvm/lvm.txt`
- Archivos:
  - `proyecto/archivos/verificacionarchivos.txt`
- Contenedores (Docker, Prometheus, Grafana):
  - `proyecto/contenedores/docker-compose.yml`
  - `proyecto/contenedores/prometheus.yml`
  - `proyecto/contenedores/errores_encontrados.md`
  - `proyecto/contenedores/logs_completos.txt`
  - `proyecto/contenedores/verificacion_contenedores.txt`
  - capturas en `proyecto/contenedores/capturas/`
- Bonus LAMP:
  - sitio en `/var/www/html/index.html`
  - `info.php` y `testdb.php`
  - capturas en `proyecto/lamp/capturas/`
  - `proyecto/lamp/verificacion_lamp.txt`

---

## Objetivo del proyecto

Automatizar la creación y configuración de una máquina virtual Linux usando Vagrant, aplicando conceptos de administración de sistemas: usuarios y permisos, gestión de discos con LVM, manipulación de archivos, uso de contenedores Docker con monitoreo (Prometheus + Grafana) y despliegue de un servidor LAMP para practicar servicios web.
