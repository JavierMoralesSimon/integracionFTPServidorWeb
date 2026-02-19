# Integración de FTP con servidor web

## Configuración de un directorio FTP vinculado a un DocumentRoot
Seleccionamos un usuario que en mi caso es "anonymous" y le ponemos de "Native Path" "/var/www/html" del cual es dueño el servidor web.
![Usuario a usar](https://github.com/JavierMoralesSimon/integracionFTPServidorWeb/blob/main/Capturas/1.png)
Además le damos todos los permisos.
![Permisos del usuario](https://github.com/JavierMoralesSimon/integracionFTPServidorWeb/blob/main/Capturas/2.png)

## Subida de un archivo HTML por FTP
Nos conectamos al servidor con el usuario "anonymous" y subimos el archivo HTML dando click derecho en él y dandole a "Subir".
![Subida del archivo HTML](https://github.com/JavierMoralesSimon/integracionFTPServidorWeb/blob/main/Capturas/3.png)
![Subida del archivo HTML](https://github.com/JavierMoralesSimon/integracionFTPServidorWeb/blob/main/Capturas/4.png)

## Acceso al archivo HTML desde el navegador vía HTTP
Escribimos la url que se muestra y nos sale el contenido del archivo HTML subido.
![Acceso al archivo HTML desde el navegador vía HTTP](https://github.com/JavierMoralesSimon/integracionFTPServidorWeb/blob/main/Capturas/5.png)
