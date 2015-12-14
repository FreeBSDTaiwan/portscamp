
PortsCamp
==============

This is a community event where [FreeBSD][freebsd] committers help people to understand what are ports and how to package new software to submit it as a new port.

這是[FreeBSD][freebsd] committers協助大家了解甚麼是ports和如何打包軟體並發佈為新的port的一個社群活動。

The Basic idea 基本想法
------------------
The Ports System used in FreeBSD is dead simple. It should be easy for any open source software publisher to submit their code to FreeBSD. But they just don't know how simple it is, so we are gonna show 'em.

FreeBSD用的Ports系統超簡單的。任何開源軟體的作者都可以輕易地發佈他們的程式碼到FreeBSD。但是他們不知道這有多簡單，所以讓我們來告訴大家。

The Camp
-------------------

#### Timing 時間的安排

The event can be prepared to last from a couple hours to a whole day. It's all a question of participants and organizers convenience. But less than one hour could be too short.

這個活動的時間可以安排為幾個小時到一整天。由活動參加者和舉辦者而定。但是活動時間不適合少於一個小時。

#### Location 地點

Best is to find a venue with good Internet connectivity and a local network where we can put a test server. You need chairs and table, because people typically bring their own laptops.

最好可以找到一個地點，有良好的網路連線和區域網路的架設，這樣我們可以設置一台測試伺服器。還需要桌椅，讓大家可以使用自己的筆記型電腦。

#### Organizers 舉辦者

It's optimal if some FreeBSD committers can be involved in the Camp, so they can explain the process of submission, detail the reviewing, show how they test, up to the point they commit your submission into the ports tree.

#### Local poudriere 區域的Poudriere

For practice purpose it will be convenient to prepare a computer in advance, installed with a functional and recent FreeBSD, with [Poudriere][poudriere] already installed and configured, and images already downloaded.

Optimally the participants should be able to ssh to the Test Server (running Poudriere) and either test their builds locally if they are very simple, or launch the tests in Poudriere.

The point is that the participants don't need to install anything, they will have access to a FreeBSD environment using ssh on the local network.

#### Local communication channel 區域通訊頻道

This can be an IRC channel created on the spot, or whatever other group instant messaging the organizers feel comfortable with. The point is to have a place where people can share URLs easily.

#### User accounts 使用者帳號

The local FreeBSD server should be all prepared including the user accounts of the participants. To do so, probably it can be convenient to use github for registering participants, and grab ssh public keys from there, but any other method can be setup by the organizers.

The user accounts also can be created on the fly without much trouble at the beginning of each camp.

#### Schedule

There should be at the beginning some introduction talk about what are ports and how to prepare them, how to make a shar and how to submit them, then how to update a port with a diff file. Then a list of possible candidates for porting could be presented to the audience, sorted by categories and difficulties level. This introduction is at the discretion of the presenter.

It can be good to have also quick presentation of [bugzilla][bugzilla], [freshports][freshports], [portscout][portscout], [phabricator][phabricator], the [porter's handbook][porterhandbook], and other useful material.

Then everybody can try to create or update ports of their choice, all together in a close proximity with other people following the same path and not far from people that know the path very well.

When a port is ready, tested and uploaded, a committer can then show how the submission process is followed up and what leads to the port being committed in the ports tree.

Conclusion 結論
-------------

A portscamp should be a great occasion to have great fun, learning useful stuff and meeting other people from various horizons.

Portscamp是一個很棒的活動，很有趣，可以學習有用的東西，還可以認識許多不同領域的人。

Taiwan Local PortsCamps
=============================

We are in progress of setting up the first sessions:

- find committers interested to participate (we already have araujo@)
- translate this page in traditional Chinese
- setup a date at the Taipei Hackerspace https://taipeihack.org/
- spread the word and find free software publishers that would be interested to participate and learn
- think about ideas to help finishing the translation of the [Porter's handbook in chinese][porterhandbooktw]
- prepare IRC channel #portscamp-tw on efnet? get a bot for factoids?
- setup a way for people to register to the first Portscamp (by mail? on a form? on facebook event? on meetup.com? on kktix?)


[freebsd]: https://www.freebsd.org/
[freshports]: http://www.freshports.org/
[portscout]: http://portscout.freebsd.org/
[bugzilla]: https://bugs.freebsd.org/bugzilla/
[phabricator]: https://reviews.freebsd.org/
[poudriere]: https://www.freebsd.org/doc/handbook/ports-poudriere.html
[porterhandbook]: https://www.freebsd.org/doc/en/books/porters-handbook/
[porterhandbooktw]: https://www.freebsd.org/doc/zh_TW/books/porters-handbook/
