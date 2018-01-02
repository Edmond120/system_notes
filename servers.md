Aim: Always tip your servers.
=============================
Forking server/client design pattern
------------------------------------

1. Setup

2. Handshake
  1. Client connects to server and sends the private FIFO name. Client waits for a response from the	 server.
  2. Server recieves client's message and forks off a subserver.

3. Operation
  + Server recreates WKP and waits for a new connection.
