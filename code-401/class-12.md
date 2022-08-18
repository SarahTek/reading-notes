# Readings: Socket.io

## Web Sockets

1. What is a Web Socket?

- WebSocket is a duplex protocol used mainly in the client-server communication channel. It’s bidirectional in nature which means communication happens to and fro between client-server.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

- The client establishes a WebSocket connection through a process known as the WebSocket handshake. This process starts with the client sending a regular HTTP request to the server. An Upgrade header is included in this request which informs the server that the client wishes to establish a WebSocket connection

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a `requested` from that client.

## Socket.io Tutorial

1. What does the event handler io.on() do?

- Start listening for socket events from Sails with the specified `eventName`. Triggers the provided callback function when a matching event is received.

2. Describe some possible proof of life or proof that the code works as expected

3. What does socket.emit() do?

- emit() to send a message to all the connected clients

## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

- WebSocket is the technology, while Socket.io is a library for WebSockets.
- WebSocket doesn’t have fallback options, while Socket.io supports fallback.

2. When would you use Socket.IO?

- If you want server to push data by itself without calling from client.

3. When would you use WebSockets?

- Websockets provide real-time updates and open lines of communication.

- A single server can have multiple WebSocket connections open simultaneously, and can even have multiple connections with the same client, which opens the door for scalability.

## Resources

- [Web sockets](https://en.wikipedia.org/wiki/WebSocket)
- [socket-tutorial](https://www.tutorialspoint.com/socket.io/)
- [web socket vs socket.io](https://www.educba.com/websocket-vs-socket-io/)
