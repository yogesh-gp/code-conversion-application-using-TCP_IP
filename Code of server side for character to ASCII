# server converting CHARACTER to ASCII CODE
from codecs import encode
import socket
import sys
# s = socket.socket (socket_family, socket_type,
protocol=0)
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
print(s)
print("socket created")
# s.bind method binds address (hostname, port number pair)
to socket.
s.bind(('localhost',9999))
# s.listen method sets up and start TCP listener.
s.listen(3)
print("waiting for connections")
while True:
# s.accept() will passively accept TCP client
connection,
# waiting until connection arrives (blocking).
c,add = s.accept()
print('connected with ',add)
c.send('hello client ok '.encode()) #Transmiting TCP
message
cdata1 = c.recv(1024).decode() #To receives TCP
message
aski = ord(cdata1) #Python ord() function returns the
Unicode code from a given character.
aski = str(aski) #Converting number to character
c.send(aski.encode())
c.close
