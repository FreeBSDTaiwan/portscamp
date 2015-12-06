
PortsCamp
==============

This is a community event where FreeBSD commiters help people to understand what are ports and how to package new software to submit it as a new port.

The Basic idea
------------------
The Ports System used in FreeBSD is dead simple. It should be easy for any open source software publisher to submit their code to FreeBSD. But they just don't know how simple it is, so we are gonna show 'em.

The Camp
-------------------

#### Timing

The event can be prepared to last from a couple hours to a whole day. It's all a question of participants and organizers convenience. But less than one hour could be too short.

#### Location

Best is to find a venue with good internet connectivity and a local network where we can put a test server. You need chairs and table, because people typically bring their own laptops.

#### Organizers

It's optimal if some FreeBSD commiters can be involved in the Camp, so they can explain the process of submission, detail the reviewing, show how they test, up to the point they commit your submission into the ports tree.

#### Local poudriere

For practice purpose it will be convenient to prepare a computer in advance, installed with a functional and recent FreeBSD, with poudriere already installed and configured, and images already downloaded.

Optimally the participants should be able to ssh to the Test Server (running poudriere) and either test their builds locally if they are very simple, or launch the tests in poudriere.

The point is that the participants don't need to install anything, they will have access to a FreeBSD environment using ssh on the local network.

#### User accounts

The local FreeBSD server should be all prepared including the user accounts of the participants. To do so, probably it can be convenient to use github for registering participants, and grab ssh public keys from there, but any other method can be setup by the organizers.

The user accounts also can be created on the fly without much trouble at the beginning of each camp.

#### Schedule

There should be at the beginning some introduction talk about what are ports and how to prepare them, how to make a shar and how to submit them, then how to update a port with a diff file. Then a list of possible candidates for porting could be presented to the audience, sorted by categories and difficulties level. This introduction is at the discretion of the presenter.

Then everybody can try to create or update ports of their choice, all together in a close proximity with other people following the same path and not far from people that know the path very well.

When a port is ready, tested and uploaded, a commiter can then show how the submission process is followed up and what leads to the port being committed in the ports tree.

Conclusion
-------------

A portscamp should be a great occasion to have great fun, learning useful stuff and meeting other people from various horizons.

