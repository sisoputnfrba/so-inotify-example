## Introducción sobre inotify ##

Inotify es un modulo del kernel que exitiende el monitoreo sobre los sistemas de archivos. Su biblioteca de usuario permite supervisar las operaciones del sistema de archivos, tales como leer, escribir y crear. Inotify es fácil de usar, y mucho más eficiente al basarse en un sistema similar a eventos.

## Notas ##

En este ejemplo se maneja el file descriptor devuelto por inotify con las funciones de archivos. Pero una de sus grandes ventajas es que se puede poner dentro de un select/poll/epoll. Por lo que teniendo 1 solo thread podemos estar escuchando sockets y a su vez los eventos del filesystem.

## Links ##

http://www.ibm.com/developerworks/linux/library/l-ubuntu-inotify/index.html?ca=drs-

http://en.wikipedia.org/wiki/Inotify


