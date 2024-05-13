---
tags:
  - protocol
  - ws
  - bidirection
---
- based on TCP
- bidirectional
- full-duplex
- push-based method
- client-server communication
- stateful protocol
- ws:// 
- wss://
- IETF / RFC 6455 (v13)
- 2008 - 2011

**Alternatives**
- Ajax
	- Long polling
	- Short polling
- Server Sent Events (SEE)
- HTTP2 push

**How work
1. Handshake
2. Switch protocol
3. данные

**Как сервер понимает что клент на месте**
- сервер и клиент играют в пинг-понг
- Сервер периодически присылает ответ по WS с просьбой о действии - послать запрос на сервер

**Сравнить Web socket  vs Http yна рисунке**
- Рация и телефон

**Use case**
- Real-time web
- Gaming
- Chat
- Trading 

**Advanced Level**
- WebRTC API
- STOMP
- WAMP

![[Pasted image 20240115153819.png]]
