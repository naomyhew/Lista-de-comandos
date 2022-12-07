# Lista-de-comandos
|comando| Descipción| Ejemplos|
|-------|-----------|---------|
|kill|cerrar una proceso que no finaliza ayudando a terminarlo de manera manual|kill -9 12345|
|chown|permite cambiar el propietario del archivo o directorio | |
|find|buscar archivos y directorios según sus permisos, tipo, fecha, propiedad, tamaño, etc|chown usuario:grupo archivo.html|
|mkdir|permite a los usuarios crear directorios (carpetas)|mkdir /home/imagenes|
|ls|enumera el contenido del directorio que desee, archivos y otros directorios anidados|ls -la|
|cd|navegar por todos nuestros directorios en nuestro sistema|cd /home/usuario/public_html|
|cat|concatenar archivos o unir, sumar. Puede leer, concatenar archivos, combinarlos y escribir contenidos de archivos en una salida estándar| |
|sudo apt|cat archivo.txt| 
|pwd|mostrar el nombre de su directorio actual, lo que puede ser útil al navegar por el sistema de archivos| /home/usuario
|cp| copiar archivos o directorios a otro directorio, se puede usar con los comandos ‘cp’ o ‘mv’ para mover archivos| cp foto.jpg public_html/imagenes/ | 
|rmdir| eliminar un directorio vacío y su contenido del sistema de archivos| rmdir carpeta |
|rm|personalizar con una variedad de opciones, como el indicador -r, que elimina recursivamente los archivos de un directorio determinado|rm imagen.jpg|
|touch| cambiar la marca de tiempo en un archivo, tambien para un archivo vacio| touch archivo.txt |
|uname|muestra información sobre el sistema, como el nombre del kernel, el nombre del host, el sistema operativo, la fecha de lanzamiento y la versión|uname|
|locate|buscar archivos en la computadora, la red o Internet, también se puede usar para buscar texto dentro de un archivo usando expresiones regulares|locate archivo.txt|
|chmod|cambiar los permisos de un archivo|chmod 755 archivo.jpg|
|ps|listar los procesos que se ejecutan en el sistema, enumera todos los procesos que coinciden con esas especificaciones|ps -a| 
|top| ver las tareas más intensivas de la CPU que se ejecutan en su sistema|top|
|history| mostrar al usuario lo que ha hecho en el sistema. Puede enumerar el contenido del directorio, iniciar programas y más|history|
|echo|línea de comandos que proporciona páginas de manual completas de las herramientas de Unix. Se puede usar junto con otras herramientas y scripts para permitir que el usuario busque información sobre comandos y datos del sistema relacionados|echo Esto es un ejemplo|
|zip|comprime archivos,ademas permite,crear, extraer, listar y actualizar archivos zip| zip -r archivocomprimido.zip directorio, zip archivocomprimido.zip archivo1 archivo2 archivo3, unzip archivocomprimido.zip|
|grep|buscar a través de todo el texto en un archivo dado|grep azul notepad.txt|
|sudo|realizar tareas que requieren permisos administrativos o raíz| sudo|
|useradd|rear un nuevo usuario, mientras que passwd agrega una contraseña a la cuenta de ese usuario|useradd [options] nombre_de_usuario| 
|sudo pacman|delegar autoridad para otorgar a ciertos usuarios (o grupos de usuarios)|sudo pacman -Syu|
|yum update| instala la última versión del paquete que se indique|yum install {package}|
|pwd|muestra la ruta absoluta del directorio en el que se encuentra|pwd|
|man| Muestra la página del manual de cualquier otro comando (siempre que tenga uno)|man mkdir| 
|./|Permite a tu shell ejecutar un archivo ejecutable con cualquier intérprete instalado en tu sistema directamente desde el terminal|#! /usr/bin/python3|
|exit|terminar una sesión de shell y, en la mayoría de los casos, cerrar automáticamente|exit|
|shutdown|permite apagar tu máquina. Sin embargo, también puede utilizarse para detenerla y reiniciarla|shutdown now|
|htop|gestionar los recursos de tu máquina directamente desde el terminal|htop|
|unzip|extraer el contenido de un archivo .zip|unzip images.zip|
|ping|solicitar un dominio o una direccion IP|ping google.com|
|passwd|cambiar las contrasenas de las cuentas de usuario|passwd|
|less|permite inspeccionar archivos hacia atrás y hacia adelante|less large_text_file.txt|
|neofetch|muestra información sobre tu sistema -como la versión del kernel, el shell y el hardware- junto a un logotipo ASCII de tu distribución de Linux|neofetch|
|top|podemos ver una lista con todos los procesos activos que está ejecutando el sistema,muestra los consumos de memoria RAM y CPU y todo en tiempo real|top -n refrescar|
|man|ver un manual sobre las funciones disponibles para un comando en concreto|man| 
|du|saber cuánto espacio está ocupando un archivo o un directorio en el sistema|du -h /Directorio1| 
|grep|utilizarlo para encontrar un texto dentro de uno o varios archivos|grep -w horario /home/archivo1.txt|
|file|recoge y muestra información sobre el archivo especificado en el cuadro de diálogo|file|
|unmount|elimina los sistemas de archivos especificados, pero la petición específica umount sdX desactivará la unidad externa para eliminarla|sudo umount|
|arch|mostrar la arquitectura de la máquina|arch|
|date|mostrar la fecha del sistema|date 
|user1|cambiar atributos del usuario|user1
|yum clear| limpiar un caché rpm borrando los paquetes descargados|yum clean packages|
