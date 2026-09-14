Resultados

Los resultados obtenidos coincidieron con el comportamiento esperado de cada comando:

ls mostró correctamente el listado simple de carpetas del directorio personal, sin mostrar archivos ocultos.
ls -l agregó la información detallada (permisos, propietario, grupo, tamaño y fecha) para cada elemento, tal como corresponde al formato largo.
ls -la incluyó, además de lo anterior, los archivos y carpetas ocultas (los que inician con punto), que no habían aparecido en los comandos anteriores.
ls -lh conservó el formato largo, pero convirtió los tamaños a unidades legibles (K), facilitando su interpretación.
cd, cd Descargas, cd .. y cd ~ permitieron desplazarse correctamente entre directorios, y en cada caso el cambio se reflejó de inmediato en el prompt de la terminal, mostrando la ruta actual del usuario.

En ningún caso se presentaron errores ni mensajes inesperados; cada comando devolvió exactamente la salida que le corresponde según su función.

Lo esperado

Se esperaba que ls listara únicamente el contenido visible del directorio actual, y que al agregar las opciones -l, -a y -h la información fuera aumentando o formateándose de manera acumulativa (más detalle, más elementos visibles, mejor legibilidad), sin alterar el contenido real de las carpetas. De igual forma, se esperaba que cd permitiera moverse entre directorios sin listar contenido, y que el prompt de la terminal reflejara siempre la ubicación actual como confirmación visual del cambio. Los resultados obtenidos cumplieron con estas expectativas en su totalidad, validando el funcionamiento correcto de ambos comandos y sus variantes.
