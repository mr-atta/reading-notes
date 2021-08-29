# Socket.io

## What is the benefit of transforming data into packets❓ [📁](https://fntsoftware.com/blog/network-transformation-transitioning-to-packet-technology/)

- to meet the demands of pervasive data-centric applications and services.
- the most cost-effective, efficient, and scalable networks for content delivery.

## UDP is often refereed to as a connectionless protocol. Why is this❓ [📁](https://docs.oracle.com/cd/E19620-01/805-4041/6j3r8iu2f/index.html#:~:text=UDP%20is%20a%20connectionless%20protocol,services%20are%20broadcasting%20and%20tftp%20.)

- because it is analogous to sending a letter where you don't acknowledge receipt.
- UDP : (User Datagram Protocol) is a lightweight data transport protocol that works on top of IP.

## Can a socket server application have multiple socket connections❓ [📁](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port#:~:text=Multiple%20connections%20on%20the%20same,system%20resources%20allow%20it%20to.)

- yes, Multiple connections on the same server can share the same server-side IP/Port pair

## Can a socket connection application be connected to multiple socket servers❓ [📁](https://stackoverflow.com/questions/11129212/tcp-can-two-different-sockets-share-a-port)

- A connected socket is assigned to a new (dedicated) port, so it means that the number of concurrent connections is limited by the number of ports, unless multiple sockets can share the same port.(16bit)

## Can an application be both a socket server and a socket connection❓ [📁](https://www.quora.com/Can-you-make-a-client-socket-and-a-server-socket-in-one)

- no, because a TCP/IP connection goes from a source port to a destination port, with each having unique port numbers.

  <br>
  <br>

## OSI (Open Systems Interconnection Model)

- The OSI Model is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.

![OSI](https://miro.medium.com/max/891/1*QgyDWZRA-eY7bo04M6E_hw.png)

## TCP

- Three-Way HandShake or a TCP 3-way handshake is a process which is used in a TCP/IP network to make a connection between the server and client. It is a three-step process that requires both the client and server to exchange synchronization and acknowledgment packets before the real data communication process starts.

![TCP](https://ars.els-cdn.com/content/image/3-s2.0-B9780128024379000059-f05-08-9780128024379.jpg)

[📁](https://www.guru99.com/tcp-3-way-handshake.html#:~:text=Three%2DWay%20HandShake%20or%20a,real%20data%20communication%20process%20starts.)

<br>

[📁OSI Model Explained VID](https://www.youtube.com/watch?v=vv4y_uOneC0)

<br>

[📁TCP Handshakes Explained VID](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
