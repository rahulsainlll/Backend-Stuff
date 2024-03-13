## Connections in backend applications

Lets looks at some definations before diving into architecture

###  Definations

### Listener

When a program wants to communicate over the internet, it opens a "socket", which is like a door that others can knock to talk to program.

### Accepter

When someone knock the door(socket), the program needs to decide whether to let them in or not.

### Reader

Once the connection build, data starts flowing through it. But this data isn't neatly packaged like email its more like a continuous stream of bytes. The reader's job is to make sence of this stream by organising it into meaningful pieces, like understanding where one messages end and another starts.

### TCP (Transmission Communication Protocol)

TCP is underlying protocol that ensures that data gets form one place to another reliably, it doesn't care about the structure of the data itself. Its like a delivery truck that transports packacges. The reader's job is to unpack the packages and make sence of them, like understanding the individual requests being sent on the internet.

