# Message Queues (13)

<br>

![Message Queues](https://www.cloudamqp.com/img/blog/thumb-mq.jpg)

<br><hr>

## What does it mean that web sockets are bidirectional? Why is this useful❓ [📁](https://www.amx.com/en/site_elements/benefits-and-applications-of-websockets#:~:text=Whereas%20HTTP%20relies%20on%20a,submit%20a%20request%20each%20time.)

- This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time. allows devices to send and receive continuous streams of data to and from any point on the network.

## Does `socket.io` use HTTP? Why❓ [📁](https://stackoverflow.com/questions/37836130/socket-io-why-does-it-need-an-http-server#:~:text=Even%20when%20websockets%20can%20be,%2F`socket.io`.js%20.)

- `socket.io` server will attach to an HTTP server so it can serve its own client code through /`socket.io`/`socket.io`.js.

* On top of the transport, it offers additional functionality like segmentation (namespaces, rooms), acknowledgements, broadcasts, etc.

- `socket.io` is a websocket library

## What happens when a client emits an event❓ What happens when a server emits an event❓ [📁](https://stackoverflow.com/questions/32674391/io-emit-vs-socket-emit)

- When a click event happens, run the callback function that inside the listen(.on).

- you can emit events on one side and register listeners on the other side.

<br>

- `socket.emit` will send back message to sender only,
- `io.emit` will send message to all the client including sender
- if you want to send message to all but not back to sender then `socket.broadcast.emit`

## What happens if a client “misses” an event❓ [📁]()

- will receive the response after he be connected

## How can we mitigate this❓ [📁]()

- use Queue

  <br><hr>

## Server

- Is a computer program or device that provides a service to another computer program and its user, also known as the client. In a data center, the physical computer that a server program runs on is also frequently referred to as a server.

## Socket

- Java Socket programming is used for communication between the applications running on different JRE. … Socket and ServerSocket classes are used for connection-oriented socket programming

## Web Socket

- WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection

## OSI Model

- (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.

## Rooms

![Rooms](https://socket.io/images/rooms.png)

- A **room** is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

* You can call **join** to subscribe the socket to a given channel.
* use **to** or **in** to emitting/send sothing.(room or rooms)
* every socket in the room excluding the sender will get the event.

## Reserved events:

- connect
- connect_error
- disconnect
- disconnecting
- newListener
- removeListener

<br><hr>

[📁 `Socket.io` **Chat Example**](https://`socket.io`/get-started/chat/)

<br>

[📁Rooms and Namespaces](https://`socket.io`/docs/v3/rooms/index.html)

<br>

[📁`Socket.io` Emit Cheatsheet](https://`socket.io`/docs/v3/emit-cheatsheet/index.html)
