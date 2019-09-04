---
title: Social Unix servers
layout: default.liquid
---

This document will teach you what Social Unix servers are. Users without a
technical background will benefit the most from this document. This document
consists of the following sections:

* What is a server?
* What is Unix?
* What does "social" mean in the context of social Unix servers?

## What is a server?

A server is a computer configured to accept connections from other computers.
Configuration could involved editing a text file, clicking a few buttons,
running a downloaded program, or many other ways. This is a very simplified
definition, but understanding this concept will de-mystify this "server" word
you keep hearing.

You will hear the word "client" being thrown around in this document. A client
is a computer that connects to a server, and sometimes even another client! For
now, you can think of a client as a guest, and a server as a host.

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

As Wikipedia puts it, "Unix is a family of multitasking, multiuser, computer
operating systems that derive from the original AT&T Unix, development starting
in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie,
and others."

Let's slow down here, that was a lot.

When people say Unix nowadays (2019 as I type this), they probably mean one of
the many modern Unix-like operating systems that derived from the original AT&T
Unix, such as GNU/Linux (See Note 1 below) or one of the BSDs (FreeBSD, OpenBSD,
NetBSD).

Forgot everything you just read? Just remember that Unix refers to one of the
Unix-like operating systems mentioned above, and that an operating system allows
your to control your computer.

Note 1: I understand that Linux is a kernel, and GNU is a set of tools that can
interact with the Linux kernel, but that's a whole other discussion.

## What does "social" mean in the context of social Unix servers?

The "social" here refers to how people socialize on Unix servers. This could be
through message boards, real-time chats, email, games, and many more. Many of
these mediums are only accessible within the server itself. This means that you
couldn't, as an example, email people from anywhere outside of the server unless
the server was configured to allow that. This would be called "local" email. So
it would only allow users on that server (computer) to email other users.

It seems limiting, but it is a great way to experience non-commercial digital
mediums of social interactions that may otherwise be monitored or monetized
without your knowing.

As an example, [tilde.town](https://tilde.town) has a game called
[`botany`](https://github.com/jifunks/botany) where the player can grow a
virtual plant. The user is responsible for watering their plant, but users can
also water each other's plants. tilde.town users can only play this game with
other tilde.town users if they are connected to tilde.town (a server).
