---
layout: default
categories: [network]
---
## Client

Messages on a network are passed with some purpose. The originator of the
message is reporting something, or precipitating some behavior (even if that
behavior is just a response.) Every message has some intent, and that intent
belongs to the client. When protocols require multiple messages back and forth,
the client is typically the sender of the original message. In the macro, the
sender is the client and the reciever and responder is the server. The client
asks for something, the server delivers it.

Often clients have a weaker identity than servers - servers must be found by
clients in advance of particular message.

### Questions about clients

* How does a client find its server?
* How does the client identify itself? What agencies does it represent?
* Why is the client sending a message? What does it need?
* What is the character of the request?
