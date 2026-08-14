# Guía de Conexión SSH con Termius

[Termius](https://termius.com) es un cliente SSH multiplataforma moderno que simplifica la administración de servidores Linux remotos (VPS) desde tu computadora o celular.

---

## ¿Cómo funciona la conexión?

Cuando te conectas a un servidor mediante SSH usando Termius, pasa lo siguiente:
1. **Petición:** Termius envía una solicitud segura al puerto `22` (por defecto) de la IP de tu servidor.
2. **Autenticación:** El servidor te pide identidad mediante una **contraseña** o una **clave SSH pública/privada**.
3. **Control:** Una vez aceptado, Termius abre una terminal segura donde puedes ejecutar cualquiera de los comandos de la lista principal de este repositorio directamente en el servidor.

---

## Configuración Paso a Paso en Termius

1. **Descarga e instala:** Consigue la aplicación para tu sistema operativo.
2. **Agregar Nuevo Host (Servidor):**
   * Ve a la sección **Hosts** y haz clic en **New Host**.
   * **Address:** Coloca la dirección IP de tu servidor Linux.
   * **Port:** `22` (a menos que tu proveedor te haya dado otro).
   * **Username:** Normalmente es `root` o el usuario que configuró tu VPS (ej. `ubuntu`).
   * **Password:** Coloca tu contraseña o importa tu llave privada (`.pem` / `.pub`).
3. **Conectar:** Haz doble clic sobre el Host creado, acepta la huella digital del servidor (ECDSA/RSA) la primera vez y listo. ¡Ya estás dentro de tu servidor!

---

## Comandos SSH Manuales (Por si no usas Termius)

Si alguna vez necesitas conectarte desde una terminal limpia sin la app, usa:

```bash
# Conexión básica con contraseña
ssh usuario@ip_del_servidor

# Conexión especificando un puerto diferente
ssh usuario@ip_del_servidor -p 2222

# Conexión usando una clave privada de seguridad
ssh -i /ruta/tu_clave.pem usuario@ip_del_servidor
```
