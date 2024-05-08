# Tutorial 10 

## 2.1. Original Code of broadcast Chat
<img src="image/image-2.1.png">

After launching both the clients and the server, I proceeded to input messages from each client. The resulting output showcased a broadcast system where all clients and the server received messages from every other client. Upon input, these messages were relayed to the server and then distributed to all clients listening on the same port.

## 2.2. Modifying the Websocket Port
<img src="image/image-2.2.png">

To change the port number, both the server and client configurations need adjustment. If the server and client have different ports, messages will not be distributed to all clients and the server because communication between them would be restricted to their respective ports. Messages sent by clients would be directed to the server's specified port, and the server would only relay messages to clients connected to its designated port.