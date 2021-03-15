# Code-Migration
The client stub sends a marshalled object, method and relevant variables to the server stub.
The server stub receives the message.
The server stub processes the message and executes the method (Bubble sort or Quick Sort)
The server stub writes the result(s) into the socket buffer for the client.
The client stub receives the result and outputs it to the terminal screen.
The client stub closed the connection and sent an EOF to the server socket.
The server closed the connection after reading an EOF and started listening again for a new connection on the same port.
