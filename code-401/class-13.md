## Reading

### Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.

- real-time chat systems are architected, providing a bi-directional communication channel between a client and a server. the idea is that the server will get it and push it to all other connected clients.

2. What proof of life are we getting on the backend from the above app?

- listening on the connection event for incoming sockets and log it to the console.

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

- the broadcast flag

### Rooms

1. What is a room and how might a room be useful?

- A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

2. How do you join a room?

```
io.on("connection", (socket) => {
  socket.join("some room");
});
```

- use `socket.join` to join a room

3. how do you leave a room?

```
io.on("connection", socket => {
  socket.on("disconnecting", () => {
    console.log(socket.rooms); // the Set contains at least the socket ID
  });
```

### Namespaces

1. What is a Namespace and what does it allow you to do?

- A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

2. Each namespace potentially has its own what? (hint: 3 things)

- `event handlers`
- `rooms`
- `middlewares`

3. Discuss a possible use case for separate namespaces

- you want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application

- your application has multiple tenants so you want to dynamically create one namespace per tenant

## Resources

- [Socket.io Chat Example](https://socket.io/get-started/chat/)
- [Rooms](https://socket.io/docs/v4/rooms)
- [Namespaces](https://socket.io/docs/v4/namespaces/)
