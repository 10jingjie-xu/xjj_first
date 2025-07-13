This is a high-concurrency server in a Linux environment,whose main function is to receive a large number of HTTP requests from clients.
It includes a thread-safe thread pool. A loop detection mechanism based on epoll and edge-triggered mode. Parsing of HTTP requests and generating response messages to clients based on the parsing results. And a mechanism for handling expired connections.
