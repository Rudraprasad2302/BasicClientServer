# BasicClientServer
A simple multi-threaded client-server application in Java using socket programming. The server handles multiple client connections concurrently, allowing for efficient communication.

Features
* Multi-threaded server using a thread pool for efficient handling of client requests.
* Client can connect to the server and send messages.
* Server responds to each client with a greeting message.
* Configurable number of threads in the server's thread pool.

Technologies Used
* Java (JDK 22)
* XML for project configuration
* Socket programming for client-server communication

Project Structure
MultipleFiles/
├── .gitignore
├── Client.java          # Client application source code
├── Server.java          # Server application source code
├── Client.class         # Compiled Client class
├── Server.class         # Compiled Server class
├── misc.xml             # Project configuration file
├── modules.xml          # Module configuration file
├── workspace.xml        # Workspace configuration file
├── MultiThreaded.iml    # IntelliJ IDEA module file
└── ThreadPool.iml       # IntelliJ IDEA module file for ThreadPool

