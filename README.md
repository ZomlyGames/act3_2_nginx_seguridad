# act3_2_nginx_seguridad

## Proceso de instalación

### Definición de red en VirtualBox y Ubuntu

1. Definición de red en VirtualBox y Ubuntu:
![Configurar VirtualBox](./Screenshots/image1.png)
![Ver ip de red de ubuntu](./Screenshots/image2.png)
![Configurar Ubuntu](./Screenshots/image3.png)
![Aplicar cambios y verificación de que la IP es la correcta](./Screenshots/image4.png)
![Probar ping](./Screenshots/image5.png)
2. Comprobación o instalación de dependencias (Nginx, htpasswd, mkcert):
![Foto del directorio](./Screenshots/image6.png)
3. Creación de directorios y permisos:
![Creación de directorios](./Screenshots/image7.png)
![Copiado de carpetas](./Screenshots/image8.png)
![Creación permisos](./Screenshots/image9.png)
4. Generación de archivos de contraseñas:
![Generación de contraseñas](./Screenshots/image10.png)
5. Generación de certificados SSL
![mkcert para portal y api](./Screenshots/image11.png)
![Mover y renombrar para que coincidan con configuración](./Screenshots/image12.png)
![Mover y renombrar también para api](./Screenshots/image13.png)
![Autofirmado para admin](./Screenshots/image14.png)
![Configuración permisos certificados](./Screenshots/image15.png)
6. Configuración de Nginx (copiar archivos, definir zonas de rate limiting)
7. Habilitación de sitios y recarga de Nginx
8. Configuración del archivo hosts

## Pruebas manuales

## Pruebas automáticas

## Problemas encontrados y soluciones
