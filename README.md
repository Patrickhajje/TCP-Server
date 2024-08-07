This project demonstrates creating a basic TCP server using Winsock in C++. The server performs the following tasks:

1) Initialize Winsock: Sets up the necessary environment for network communication.
2)Create a Socket: Establishes a socket to listen for incoming connections.
3)Bind Socket: Associates the socket with a specific IP address and port.
4)Listen for Connections: Puts the socket in listening mode to accept incoming client connections.
5)Accept Connections: Waits for a client to connect and then accepts the connection.
6)Receive and Echo Messages: Continuously receives messages from the client and echoes them back until the client disconnects.
7)Cleanup: Closes sockets and cleans up the Winsock environment before exiting.

This project is a fundamental example of understanding TCP server-client communication using Winsock in C++.
