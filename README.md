# Chat example using Socket.io and Node Js


This project is to understand the principle of
sockets, as well as to implement the use of nodejs.

## What is Node Js?

Conceived as a **JavaScript** execution environment for asynchronous events, Node.js is designed to build scalable network applications.
This contrasts with the most common concurrency model today, where threads of the Operating System are used. Thread-based network operations are relatively inefficient and very difficult to use. In addition, the users of Node.js are free from worries about blocking the process, since it does not exist. Almost no function in Node.js performs I / O directly, so the process never crashes. Because there is no blocking it is very reasonable to develop scalable systems in Node.js.

Node.js has a similar design and is influenced by systems such as Ruby Event Machine or Python Twisted. Node.js takes the event model a little further, it presents an event loop as an environment instead of a library. In other systems there is always a call that blocks to start the event loop.

> * Information retrieved in [Node Js](https://nodejs.org/es/about/)



## What is Socket.io?

*Socket.io* is a **JavaScript** library for *Node Js* that allows real-time two-way communication between client and server.

It is **important** to note that the applications made in Socket.io have a disadvantage and that they do not support interactions with other clients that use standard Websocket. This is because Socket.io is not an implementation of the Websocket protocol but a real-time web communication library that uses several protocols. However, that does not mean that it is very powerful and easy to use, ideal for any project in which both the client and the server can use the same library.

> * Information retrieved in [Hiper textual](https://hipertextual.com/archivo/2014/08/socketio-javascript/)
