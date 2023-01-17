# CMPUT404Lab2
plekach, 1573266

Question 1:
s = socket.socket(socket.SOL_TCP, socket.SOCK_STREAM, 1)

Question 2:
A server socket needs to bind to an address, binds to a port and accepts requests and needs an option to listen to for data where as client sends commands to an address and port

Question 3:
.setsockopt(socket.SOL_SOCKET, socket.SO_REUSEADDR, 1) will allow that to happen

Question 4:
connection, which is a socket but not the socket we created as the client socket and the address.

Question 5: 
It receives a blank/empty string

Question 6:

