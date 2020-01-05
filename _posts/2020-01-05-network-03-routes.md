---
layout: default
---
## Routes

Messages travel through a network via some route. Sometimes a route is just a
wire, or a single connection, but more often a route involves many
participants: perhaps a message is ignored by most devices attached to a bus,
so only the intended recipient listens. Perhaps the message has to traverse a
bridge or hub, or a switch. Routes exist for many layers of the network, one on
top of the other - an ethernet packet routes across a LAN carrying an IP packet
headed for the internet. Routes are also often made up of smaller routes - each
"hop" of the route is it's own route, down to the simplest connection.

### Questions about routes

* Who are the participants in a route?
* How are routes negotiated?
* Where are routes stored? How quickly are they updated?
* What are the smaller routes that make up this route?
* How much do the endpoints know about the route?
* What happens when one route fails?

