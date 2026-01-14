# Práctica 4.1: Instalación y configuración de servidor web Nginx

## Checklists y evidencias

### Fase 1: Instalación y Configuración

| N.º | Requisito | ¿Realizada? | Evidencia |
|-----|-----------|-------------|-----------|
| 1 | **Servicio Nginx activo**: El servidor web está instalado y corriendo en el sistema base. | ✅ | ![Prueba](img/requisito1.png) |
| 2 | **Configuración cargada**: Se ha cargado el archivo de configuración del sitio. | ✅ | ![Prueba](img/requisito2.png) |
| 3 | **Resolución de nombres**: El alumno ha configurado /etc/hosts (o en Windows) para usar un nombre en vez de la IP. | ✅ | ![Prueba](img/requisito3.png) |
| 4 | **Contenido Web**: Se visualiza la web de "Cloud Academy" en lugar de la página por defecto de Nginx. | ✅ | ![Prueba](img/requisito4.png) |

### Fase 2: Transferencia SFTP (Filezilla)

| N.º | Requisito | ¿Realizada? | Evidencia |
|-----|-----------|-------------|-----------|
| 5 | **Conexión SFTP exitosa**: Conexión establecida mediante claves (o usuario/pass) al servidor. | ✅ | ![Prueba](img/requisito5.png) |
| 6 | **Permisos de escritura**: El usuario ha logrado subir archivos sin error de "Permission denied". | ✅ | ![Prueba](img/requisito6.png) |


### Fase 3: Infraestructura Docker

| N.º | Requisito | ¿Realizada? | Evidencia |
|-----|-----------|-------------|-----------|
| 7 | **Contenedores activos**: Nginx y SFTP están corriendo simultáneamente. | ✅ | ![Prueba](img/requisito7.png) |
| 8 | **Persistencia (Volumen Compartido)**: Lo que se sube al SFTP se ve en la Web. | ✅ | ![Prueba](img/requisito8.png) |
| 9 | **Despliegue Multi-sitio**: Se ha desplegado la segunda web (Reloj) en una subcarpeta. | ✅ | ![Prueba](img/requisito9.png) |

### Fase 4: Seguridad HTTPS

| N.º | Requisito | ¿Realizada? | Evidencia |
|-----|-----------|-------------|-----------|
| 10 | **Cifrado SSL**: El servidor responde a peticiones seguras. | ✅ | ![Prueba](img/requisito10.png) |
| 11 | **Redirección Forzada**: HTTP redirige a HTTPS. | ✅ | ![Prueba](img/requisito11.png) |


## Documentación utilizada

- [Cómo configurar servidor HTTPS nginx](https://softwarecrafters.io/devops/configurar-servidor-https-nginx)

- [Módulo SSL - Doc Nginx](https://nginx.org/en/docs/http/ngx_http_ssl_module.html)