# Linux Commands Reference Guide

Una guía rápida y directa con los comandos esenciales de Linux para sobrevivir en la terminal. Para ver cómo conectar y gestionar servidores remotos usando estos comandos, revisa nuestra [Guía de Termius](termius.md).

---

## 1. Navegación y Archivos Básicos

| Comando | ¿Qué hace? |
| :--- | :--- |
| `pwd` | Muestra la ruta de la carpeta donde estás parado. |
| `ls -alh` | Lista todos los archivos, tamaños y carpetas ocultas. |
| `cd <ruta>` | Te mueve a la carpeta especificada (`cd ..` para volver atrás). |
| `mkdir <nombre>` | Crea una nueva carpeta. |
| `touch <archivo>` | Crea un archivo vacío. |
| `cp -r <origen> <destino>` | Copia archivos o carpetas por completo. |
| `mv <origen> <destino>` | Mueve o renombra un archivo o carpeta. |
| `rm -rf <ruta>` | **Peligro:** Elimina carpetas o archivos a la fuerza sin preguntar. |

---

## 2. Ver Archivos y Buscar

| Comando | ¿Qué hace? |
| :--- | :--- |
| `cat <archivo>` | Muestra todo el contenido de un archivo en pantalla. |
| `tail -f <archivo>` | Muestra los cambios de un archivo en tiempo real (útil para logs). |
| `nano <archivo>` | Abre un editor de texto rápido dentro de la terminal. |
| `grep "texto" <archivo>` | Busca una palabra específica dentro del archivo. |

---

## 3. Sistema, Permisos y Redes

| Comando | ¿Qué hace? |
| :--- | :--- |
| `sudo <comando>` | Ejecuta un comando con permisos de administrador (root). |
| `chmod +x <archivo>` | Da permisos de ejecución a un archivo o script. |
| `htop` | Muestra el uso de CPU, RAM y procesos en tiempo real. |
| `df -h` | Muestra el espacio libre y ocupado en los discos duros. |
| `ping <ip_o_host>` | Verifica si un servidor remoto está activo y responde. |

---

## Conectividad Remota con Termius

Para administrar servidores Linux en la nube de forma eficiente, la mejor herramienta es **Termius**. Nos permite guardar credenciales, gestionar conexiones SSH fácilmente y sincronizar terminales entre dispositivos.

👉 **[Haz clic aquí para leer la guía completa de Termius y SSH (termius.md)](termius.md)** donde explicamos cómo funciona, cómo conectarte a tu servidor y configurarlo paso a paso.

## About

Guía rápida de comandos Linux indispensables para el día a día.

### Topics

linux bash terminal commands linux-commands ssh termius sysadmin
