# socket-chat-example

# Descripción general de la API del lado del cliente

La API Socket.IO del lado del cliente proporciona métodos para:

-io()- Se conecta al servidor
-socket.emit()- Envía un evento al servidor
-socket.on()- Escucha los eventos del servidor
-socket.disconnect()- Se desconecta del servidor

# Eventos integrados

connect- Disparado al conectarse
disconnect- Disparado al desconectarse
error- Disparado por error
reconnect- Disparado tras una reconexión exitosa
reconnect_attempt- Disparado al intentar reconectarse
