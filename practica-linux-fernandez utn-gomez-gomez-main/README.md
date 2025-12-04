# 🐧 Trabajo Práctico – Administración de Sistemas Linux  
## UTN – Facultad Regional Avellaneda

Este repositorio contiene el Trabajo Práctico grupal de **Administración de Sistemas Linux**, utilizando **Vagrant** para la creación, configuración y automatización de entornos virtuales.  
Incluye el **Vagrantfile**, scripts de **provisioning**, configuraciones, documentación y verificaciones realizadas durante el desarrollo del proyecto.

---

## 👥 Integrantes
- **Jeremías Fernández** — [GitHub](https://github.com/JeremiasFernandez)
- **Elizabet Antonela Gómez** — [GitHub](https://github.com/antokernel)
- **Victor Gómez** — [GitHub](https://github.com/alejandrogomez2004)

---

## 📁 Contenido del repositorio

### 📦 Archivos principales
- `Vagrantfile` — Configuración del entorno virtual  
- Scripts de provisioning y automatización  
- Documentación del proyecto

---

## 🧪 Trabajo realizado

### 🔹 Información de la VM
- `proyecto/informacion/ip_vm.txt`  
- `proyecto/informacion/fastfetch.txt`

### 🔹 Permisos y usuarios
- `proyecto/permisos/usuariosGOMEZE.txt`  
- Directorios configurados:
  - `confidencial/`
  - `publico/`
- Verificación:
  - `proyecto/permisos/verificacionpermisos.txt`

### 🔹 LVM (Logical Volume Manager)
- `proyecto/lvm/lvm-gomeze.txt`  
- `proyecto/lvm/lvm.txt`

### 🔹 Archivos
- `proyecto/archivos/verificacionarchivos.txt`

### 🔹 Contenedores (Docker / Prometheus / Grafana)
- `proyecto/contenedores/docker-compose.yml`  
- `proyecto/contenedores/prometheus.yml`  
- `proyecto/contenedores/errores_encontrados.md`  
- `proyecto/contenedores/logs_completos.txt`  
- `proyecto/contenedores/verificacion_contenedores.txt`  
- Capturas:  
  - `proyecto/contenedores/capturas/`

### 🔹 Bonus LAMP (Apache, MariaDB, PHP)
- Archivos del sitio:
  - `/var/www/html/index.html`  
  - `info.php`
  - `testdb.php`
- Verificación:
  - `proyecto/lamp/verificacion_lamp.txt`  
- Capturas:
  - `proyecto/lamp/capturas/`

---

## 📌 Notas finales
El trabajo cubre la configuración completa de una máquina virtual con automatización mediante Vagrant, administración de usuarios/permisos, LVM, archivos del sistema, contenedores Docker con servicios de monitoreo y un entorno LAMP funcional como bonus.


---

## Objetivo del proyecto

Automatizar la creación y configuración de una máquina virtual Linux usando Vagrant, aplicando conceptos de administración de sistemas: usuarios y permisos, gestión de discos con LVM, manipulación de archivos, uso de contenedores Docker con monitoreo (Prometheus + Grafana) y despliegue de un servidor LAMP para practicar servicios web.
