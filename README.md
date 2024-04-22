This C++ program demonstrates a simple client-server model for secure communication using sockets. 
The SecureSystem class represents a client device that establishes a socket connection to a server. 
The client generates events with timestamps and sends them to the server over the network. 
The server, upon receiving event messages, updates its logical clock based on the received timestamps. 
Both client and server utilize mutexes to ensure thread safety when accessing and updating the logical clock. 
After sending events and receiving acknowledgments from the server, the client prints the current timestamp. 
This program serves as a basic example of distributed system communication and logical clock synchronization.
