# My_Works
The codes are implement to communicate Server and Client in Unidirectional Way. The Proxy Server 1 communicates with the Server in MODBUS TCP and the Client also communicates with the Proxy Server 2 in MODBUS TCP. The Proxy server 1 sends data to in unidirectional way to Proxy Server 2 in UDP Protocol.

To implement it, open 4 terminals and in each terminal write

1)gcc Server.c -o Server  
2)gcc Proxy1.c -o Proxy1 
3)gcc Proxy2.c -o Proxy2 
4)gcc Client.c -o Client 

The order of execution in the terminals are

1) ./Server
2) ./Proxy2
3) ./Proxy1
4) ./Client
