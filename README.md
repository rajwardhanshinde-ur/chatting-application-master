# chatting-application-master
Developed a real-time chat system using Java socket programming and multithreading. Implements client-server architecture with concurrent user handling, message exchange, and connection management. Focuses on debugging, error handling, and network communication concepts.
# Chat Application (Java + Socket Programming)

This project is a real-time chat application built using Java and TCP sockets.
It demonstrates client-server communication, multi-threading, and message handling.

The system allows multiple users to connect to a server and exchange messages in real-time.
## Features
- Real-time messaging using TCP sockets
- Multi-client handling using multithreading
- Server-client architecture
- Basic error handling and logging
- User connection management
- ## Tech Stack
- Java (Core Java, Multithreading, Sockets)
- Networking (TCP/IP)
- IDE: IntelliJ / Eclipse
- OS: Windows/Linux
- 
- ## Architecture

The system follows a client-server model:

- Server:
  - Listens on a specific port
  - Accepts multiple client connections
  - Handles each client using separate threads

- Client:
  - Connects to server via socket
  - Sends and receives messages
  - ## Troubleshooting

Issue: Port already in use
Solution: Change port number or stop existing process

Issue: Client not connecting
Solution:
- Check server is running
- Verify IP and port
- Check firewall settings

Issue: Messages not received
Solution:
- Ensure thread handling is correct
- Check socket connection status
