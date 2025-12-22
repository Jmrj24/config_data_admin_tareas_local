# Configuración Centralizada – Spring Cloud Config

Este repositorio contiene los archivos de configuración utilizados por el **Spring Cloud Config Server** del proyecto *Sistema de Gestión de Tareas – Microservicios*.

## 📁 Contenido del repositorio

- Configuraciones **locales** utilizadas para desarrollo y pruebas.

Las configuraciones correspondientes a **Docker** y **entornos cloud (Render)** no se incluyen en este repositorio por motivos de seguridad y buenas prácticas.

## 🔐 Seguridad y buenas prácticas

- No se almacenan credenciales sensibles reales.
- Las configuraciones públicas están pensadas exclusivamente para entorno local.
- Los entornos productivos utilizan variables de entorno y configuraciones privadas.

## ⚙️ Uso

Este repositorio es consumido automáticamente por el **Config Server** al iniciar la aplicación.

No es necesario ejecutar nada manualmente desde este repositorio.
