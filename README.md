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
![Copiado archivos de Nginx](./Screenshots/image16.png)
![Definición zonas rate limiting](./Screenshots/image17.png)
7. Habilitación de sitios y recarga de Nginx
![Habilitación sitios](./Screenshots/image18.png)
![Verificación y recarga Nginx](./Screenshots/image19.png)
8. Configuración del archivo hosts
![Configuración archivo hosts](./Screenshots/image20.png)

## Pruebas manuales

Algunas de las capturas solicitadas en este apartado, por ejemplo la de configuración de red, ya están en el apartado anterior, por lo que no veo necesario volver a repetirlas aquí.
![Pruebas](./Screenshots/image.png)

## Pruebas automáticas

![Ejecución y resultado del script](./Screenshots/image.png)

## Problemas encontrados y soluciones

La práctica aún está sin terminar, debido a que me quedó la máquina virtual en clase. Lo terminaré el jueves o viernes y añadiré los apartados que faltan en este readme.
