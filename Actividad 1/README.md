** 3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.**






** 4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
UDP, e IP?**

En TCP el puerto por defecto para un servidor HTTP es el puerto 80 pero tambien se puede usar otros puertos como el 8000 o 8080.
El protocolo HTTP se encuentra en la capa 4 o de aplicacion del modelo TCP/IP. El protocolo TCP se encuentra en la capa 3 o de transporte , el UDP tambien se encuentra en la capa 3 o de transporte.
Y el protocolo IP se encuentra en la capa 1  o Fisica y la capa 2 o Enlace de datos.





** 5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php**

El significado de HTTP/1.1 302 found es cuando el recurso que solicitas ha sido movido temporalmente a la URL, dado a las cabeceras Location(en-US).
El navegador redirecciona la pagina pero los motores de busqueda no actualizan sus enlaces al recurso.





** 6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.**


He puesto la ip: 142.250.200.99 y me ha abierto Google.