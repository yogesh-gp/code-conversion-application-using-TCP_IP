#client reqest to convert ASCII CODE to CHARACTER
import socket
# s = socket.socket (socket_family, socket_type,
protocol=0)
c = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
print('client socket created')
# c.connect method actively initiates TCP server
connection.
c.connect(('localhost',9999))
# s.recv() method receives TCP message
print(c.recv(1024).decode())
# Taking input from client
tm1 = input('enter number')
#Sendall() method transmits TCP message
c.sendall(tm1.encode())
# Client wait to get response from server
print('wait getting ascii char.....')
# client is now ready print character assembled from server
print(c.recv(1024).decode())
#c.close() closes the socket
c.close()
