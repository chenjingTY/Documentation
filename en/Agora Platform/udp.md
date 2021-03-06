
---
title: UDP
description: Definition of UDP
platform: All Platforms
updatedAt: Wed Sep 30 2020 08:52:57 GMT+0800 (CST)
---
# UDP
UDP (User Datagram Protocol) is a connectionless-oriented and unreliable transport layer communication protocol.

Connectionless-oriented means that no connection is established between the sender and receiver before data transmission. UDP has no handshaking dialogues, and data can be sent without verifying the state of the receiver. UDP only adds a header to the data packet for identification.

Unlike TCP, UDP does not know whether the data is successfully sent. In poor network conditions, the data may be lost or received out of the correct order. 

UDP supports one-to-one, one-to-many, and many-to-many connections.

UDP is best suited for time-sensitive scenarios such as real-time communications. Agora SD-RTN™ uses a private protocol based on UDP.

<div class="alert info">See also: 
	<li><a href="../../en/Agora%20Platform/sd_rtn.md">SD-RTN™</a></li>
	<li><a href="../../en/Agora%20Platform/tcp.md">TCP</a></li>
</div>

<a href="../../en/Agora%20Platform/terms.md"><button>Back to glossary</button></a>
