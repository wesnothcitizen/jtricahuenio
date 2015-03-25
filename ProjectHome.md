'JTricahue' es un chat en Java escalable que utiliza la biblioteca NIO basado en xSocket.

Consiste en una aplicación cliente-servidor mediante el cual se pueden conectar cientos de personas para chatear. Mantiene una ventana principal y permite abrir conversaciones privadas.

Se pueden usar avatares y emoticones personalizados.
Aún no soporta envío de archivos.

La ventaja de usar Java NIO en vez de Java IO (con Threads) es que el servidor puede mantener cientos o miles de clientes conectados simultáneamente sin degradar tanto el performance. Para lograr la comunicación mediante NIO se utiliza el proyecto xSocket.

La aplicación está separada en dos partes, un cliente y un servidor.
Se provee de ambos tanto en binarios como en código (proyectos NetBeans 6.7.1).