# code-conversion-application-using-TCP_IP
Implementation of a Client Server based Character to ASCII and vice-versa code conversion application using TCP.
This mini project details the great potential that socket programming has. We were able to implement concept of client and server using TCP through programme.
Socket programming is a way of connecting two nodes on a network to communicate with each other.
One socket(node) listens on a particular port at an IP, while other socket reaches out to the other to form a connection.
TCP does Flow Control and requires three packets to set up a socket connection, before any user data can be sent. 
There is absolute guarantee that the data transferred remains intact and arrives in the same order in which it was sent.
TCP handles reliability and congestion control. It also does error checking and error recovery. The entire process can be broken down into following steps:
TCP Server –
• using create(), Create TCP socket.
• using bind(), Bind the socket to server address.
• using listen(), put the server socket in a passive mode, where it waits for the client to approach the server to make a connection
• using accept(), At this point, connection is established between client and server, and they are ready to transfer data.
• Go back to Step 3.
TCP Client –
• Create TCP socket.
• connect newly created client socket to server.
Through this mini project we were able to understand how to use these function for establish connection between client and user
and successfully i did it and create application to convert ASCII to Binary and vice-versa. 
Even we are in condition to implement these concept of socket programming different application.
