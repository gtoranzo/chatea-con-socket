# chatea-con-socket

Chatea con socket

#### Servidor de socket de Python

Guardaremos el programa del servidor de socket de Python como socket_server.py. Para usar la conexión de socket de Python, necesitamos importar el módulo de socket. Luego, secuencialmente, debemos realizar alguna tarea para establecer la conexión entre el servidor y el cliente. Podemos obtener la dirección del host usando la función socket.gethostname(). Se recomienda una dirección de puerto de usuario superior a 1024 porque los números de puerto inferiores a 1024 están reservados para el protocolo de Internet estándar. Consulte el siguiente código de ejemplo del servidor de socket de Python, los comentarios lo ayudarán a comprender el código.

Entonces, nuestro servidor de socket python se ejecuta en el puerto 5000 y esperará la solicitud del cliente. Si desea que el servidor no se cierre cuando se cierra la conexión del cliente, simplemente elimine el ciclo while de Python que se usa para ejecutar el programa del servidor indefinidamente y siga esperando la solicitud del cliente.

#### Cliente de socket de Python

Guardaremos el programa de cliente de socket de python como socket_client.py. Este programa es similar al programa del servidor, excepto por el enlace. La principal diferencia entre el servidor y el programa del cliente es que, en el programa del servidor, debe unir la dirección del host y la dirección del puerto. Consulte el siguiente código de ejemplo de cliente de socket de python, el comentario lo ayudará a comprender el código.

Tenga en cuenta que el servidor de socket se ejecuta en el puerto 5000, pero el cliente también requiere un puerto de socket para conectarse al servidor. Este puerto se asigna aleatoriamente por llamada de conexión del cliente. En este caso, es 57822. Entonces, eso es todo para la programación de socket de Python, el servidor de socket de Python y los programas de ejemplo de cliente de socket. Referencia: Documentación Oficial
