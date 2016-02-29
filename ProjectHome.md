Welcome to the Nading.Network.Library

**UPDATE: added new libs that now include the new packet queue system for those that dont want to use the events. you will have to enable or disable the queue system when you start the client or server if you are going to use it or not. also some other minor changes and cleanups.. pretty stable version up!**

This library was written in and for the .NET Framework.. Visual Basic, C# and Managed C++. The library utilizes the .NET sockets class. Its a Client / Server architecture driven by events.

Some of the current features include:
  * TCP so all packets are delivered in order guaranteed.
  * Excellent Packet organization with packet and packettype
  * Single line of code to send a packet
  * Your own custom packet types, anything you want
  * Event based connections, disconnections and packet transfers
  * Super simple implementation with less than 10 lines of code for a complete client

Some basic single line of code functions include:
  * `Connect()` to server
  * `Disconnect()` from server
  * `Send()` sends a packet to the server utilizing a packet type
  * `StartServer()` starts the server
  * `StopServer()` stops the server
  * `SendPacketToClient()` sends a packet to a single specified client utilizing a packet type
  * `SendPacketToAllClients()` sends a packet to all connected clients utilizing a packet type
  * `DropClient()` drops a client from the server
  * All actions are risen with events.

Functions in progress include:
  * Dynamic automated encryption and decryption transparent to your code
  * Ability to poll bandwidth statistics including packets sent and network ping times
  * Functions to allow for bandwidth throttling
  * Lag situations simulated
  * Multiple client simulation scenarios
  * Automatic replication of any type or object on both ends
  * Built-in heartbeat system to ensure connectivity
  * Multiple levels of data compression