# replicate-over-network
C# replicate over network

This code creates a server that listens 
for incoming connections on port 8080. 
When it receives a connection, 
it starts a new thread to handle the 
connection. The thread reads a message 
from the client and, if the message is 
"replicate", it reads a file from the 
stream and saves it to disk. 
It then executes the file.
