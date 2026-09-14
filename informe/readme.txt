Introducción

En la presente práctica se realizaron pruebas con comandos básicos de navegación y listado de archivos en la terminal (Konsole) de un sistema operativo Linux, con el objetivo de identificar el contenido del directorio personal del usuario y practicar el desplazamiento entre carpetas.

Desarrollo

Primero se ejecutó el comando ls estando dentro del directorio personal (home) del usuario "eduardo". Al ponerlo, la terminal mostró el contenido de dicho directorio, listando únicamente los nombres de las carpetas visibles: Descargas, Desktop, Documentos, Imágenes, Música, Plantillas, Público, Vídeos y snap.

Después se ejecutó ls -l, que despliega la misma información pero en formato de lista larga. Al ponerlo, la terminal mostró para cada carpeta el tipo de archivo y permisos (por ejemplo drwxr-xr-x), el número de enlaces, el propietario y grupo (eduardo eduardo), el tamaño en bytes, así como la fecha y hora de la última modificación.

A continuación se probó ls -la, que combina el formato largo con la opción para mostrar archivos ocultos. Al ejecutarlo, además de las carpetas ya vistas aparecieron los archivos y directorios ocultos del sistema, como .bashrc, .bash_history, .bash_logout, .cache, .config, .profile y .vimrc, junto con las entradas especiales . (directorio actual) y .. (directorio padre).

Luego se ejecutó ls -lh, que utiliza el formato largo pero con tamaños legibles para humanos. Al ponerlo, el resultado fue el mismo listado de carpetas, pero con el tamaño mostrado en unidades como "4.0K" en lugar del valor exacto en bytes.

Posteriormente se trabajó con el comando cd para practicar la navegación entre directorios. Al ejecutar cd sin argumentos, la terminal regresó al directorio personal del usuario. Enseguida se ejecutó cd Descargas, y como resultado el símbolo del sistema (prompt) cambió a eduardo@ed-thinkpad:~/Descargas$, confirmando que la ubicación actual pasó a ser esa carpeta.

Estando dentro de Descargas, se ejecutó cd .., y el prompt regresó a eduardo@ed-thinkpad:~$, es decir, subió un nivel de vuelta al directorio padre (el home). Finalmente se ejecutó cd ~, obteniendo el mismo resultado: el sistema se ubicó nuevamente en el directorio personal del usuario, confirmando que el símbolo ~ es un atajo hacia el home.

Conclusión

Con esta práctica se comprobó el funcionamiento de los comandos ls y cd junto con sus principales opciones (-l, -a, -h). Se observó que cada opción modifica la cantidad y el formato de la información mostrada, y que cd permite moverse fácilmente entre directorios usando rutas relativas, el directorio padre (..) o el atajo al home (~).
