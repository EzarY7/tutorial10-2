Mochammad Ezar Yudha 2206046746
<h1>Tutorial 10 (2)</h1>
<h2>Experiment 2.1: Original code, and how it runs</h2>
<h3>Client 1 Console</h3>
<img src= "images/client1.jpg">
<h3>Client 2 Console</h3>
<img src= "images/client2.jpg">
<h3>Client 3 Console</h3>
<img src= "images/client3.jpg">
<h3>Server Console</h3>
<img src = "images/server.jpg">

The server handles multiple WebSocket connections concurrently and broadcasts messages received from clients to all connected clients. The client connects to the server, sends messages entered by the user, and prints out messages received from the server.

<h2>Experiment 2.2: Modifying port</h2>
I modified the following snippets of code to change the port to 8080,
<h3>client.rs</h3>
<img src= "images/client_rs.jpg">
<h3>server.rs</h3>
<img src= "images/server_rs.jpg">
The modified version uses the same Websocket.