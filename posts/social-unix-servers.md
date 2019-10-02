---
title: Social Unix servers
layout: default.liquid
---

This document will teach you about Social Unix servers. Users without a
technical background will benefit the most from this document. This document
consists of the following sections:

* What is Unix?
* Servers and clients
* What does "social" mean in the context of social Unix servers?

## What is Unix?

As Wikipedia puts it, "Unix is a family of multitasking, multiuser, computer
operating systems that derive from the original AT&T Unix, development starting
in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie,
and others."

Okay, let's slow down here, that was a lot of jargon.

To simply put it, an operating system allows you to control your computer. Some
popular operating systems, as of 2019, are Microsoft Windows, macOS, Android,
iOS, and Ubuntu (A GNU/Linux [[1]](#1) distribution [[2]](#2)).

To simplify things, nowadays (2019 as I write this), when people say Unix, they
probably mean one of the Unix-like operating systems that derived from the
original AT&T Unix, such as:

* GNU/Linux
* FreeBSD
* OpenBSD
* NetBSD
* and many more

---

<span id="1">[1]:</span> Linux is a kernel and GNU is a set of tools that can
interact with the Linux kernel, but these would need a whole other article to
understand them better. Many people refer to these two things as an operating
system.

<span id="2">[2]:</span> A distribution of GNU/Linux means that the operating
system comes with certain default settings, such as programs available,
security, desktop graphics, etc.

## Servers and clients

Before you continue to the next two sections "What is a server?" and "What is a
client?", you should know that the descriptions in each of the sections below
are generalized. They leave out information related to server and client
processes.  This is done intentionally so readers are not overwhelmed with
information.

### What is a server?

A server is hardware or software that has been configured to accept connections
from other hardware or software.

An example of a server could be a computer that has chat server software running
on it, so other people can connect and chat to each other.

### What is a client?

A client is hardware or software that has been configured to connect to other
hardware or software.

An example of a client could be your internet browser, which connects to a
social media website (a server).

### A common server-client setup

One kind of server-client setup could involved three computers: computer A,
computer B, and computer C. Let's pretend computer B's settings have been
configured to accept connections from other computers. Computer A can connect to
computer B to communicate with computer C (See Figure 1 below).

```
+------------+          +------------+            +------------+
|            |--------->|            |----------->|            |
| computer A |          | computer B |            | computer C |
|            |<---------|            |<-----------|            |
+------------+          +------------+            +------------+
Figure 1
```

## What does "social" mean in the context of social Unix servers?

The "social" here refers to how people socialize on Unix servers. This could be
through:

* Message boards
* Real-time chat
* Local [[3]](#3) Email
* Games
* and many more.

All of this "local" business seems limiting, but it is a great way to experience
non-commercial digital mediums of social interactions that may otherwise be
monitored or monetized without your knowing. This is also a great way to avoid
[dark patterns](https://www.darkpatterns.org).

Another example of something "local" is [tilde.town](https://tilde.town)'s
[botany](https://github.com/jifunks/botany) game where the player can grow a
virtual plant. The user is responsible for watering their plant, but users can
also water each other's plants. Only tilde.town users can play this game with
other tilde.town users if they are connected to tilde.town.

In this case, tilde.town is the server, and the users connecting to tilde.town
are clients.

---

<span id="3">[3]:</span> The word "local" in this context refers to user-to-user
emails on a server, rather than communicating with external email services, such
as [Protonmail](https://protonmail.com). "Local" is just a fancy word people use
to refer to something that doesn't leave or connect to another computer.
