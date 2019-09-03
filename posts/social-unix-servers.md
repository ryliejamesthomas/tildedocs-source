---
title: Social Unix servers
layout: default.liquid
---

This document will teach you what Social Unix servers are. Users without a
technical background will benefit the most from this document. This document
consists of the following sections:

* What is a server?
* What is Unix?
* What does "Social" mean in the context of Unix servers?

## What is a server?

A server is a computer configured to accept connections from other computers.
Configuration could involved editing a text file, clicking a few buttons,
running a downloaded program, or many other ways. This is a very simplified
definition, but understanding this concept will de-mystify this "server" word
you keep hearing. You will hear the word "client" being thrown around in this
document. A client is a computer that connects to a server, and sometimes even
another client! For now, you can think of a client as a guest, and a server as a
host.

A server could be any machine, even a laptop. The laptop hardware may not
be designed to handle a lot of connections from different computers, but it can
still accept connections from other computers.

One kind of server setup could involved three computers: computer A, computer B,
and computer C. Let's pretend computer B's settings have been configured to
accept connections from other computers. Computer A can connect to computer B to
communicate with computer C (See Figure 1 below).

```
+------------+          +------------+            +------------+
|            |--------->|            |----------->|            |
| computer A |          | computer B |            | computer C |
|            |<---------|            |<-----------|            |
+------------+          +------------+            +------------+
Figure 1
```
Another kind of server setup could just involve two computers: computer A and
computer B. Both computers have software that can search for other computers on
a wifi network. This software can not only connect to other computers, but it
also accepts connections from other computers. Using this software, computer A
can communicate with computer B (See Figure 2 below).

```
+------------+          +------------+
|            |--------->|            |
| computer A |          | computer B |
|            |<---------|            |
+------------+          +------------+
Figure 2
```

In Figure 2 above, computer A and computer B are both servers and clients at the
same time, because they are both accepting connections from clients, and they
both act as clients because they can also connect to each other! This is called
Peer-to-Peer (P2P) networking. "Network" is just a fancy work for a collection
of computers that connect to each other.

## What is Unix?

Coming soon!

## What does "Social" mean in the context of Unix servers?

Coming soon!
