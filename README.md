# Client-Server-Application

Designed a complete social environment, with all the features 
? like sending and receiving messages from various clients
? sending files from one client to all
? sending messages to friends in a group or we can send 
private message to the one we want.


How to Run:-

Firstly server.c and client.c should be compiled in a way that we 
usually do i.e;

->gcc server.c -o server
->gcc client.c -o client

After that run client and server on different terminal if using same
system or you can use different systems connected on same 
network.

Command to run:-

->./server <port number> 

This start the server and server now waiting for the 
connections.
<port number> is the argument passed to the program 
which decide which post if use for the connections.



->./client <ip address><port number>

After the successful run , client is connected to the server 
and client is asked for unique id so he can be located later 
by that id. After this, client will be able to use the features 
of the chatroom.