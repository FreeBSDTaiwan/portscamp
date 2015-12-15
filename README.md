
PortsCamp
==============

This is a community event where [FreeBSD][freebsd] committers help people to understand what are ports and how to package new software to submit it as a new port.

這是 [FreeBSD][freebsd] committers 協助大家了解甚麼是 ports 和如何打包軟體並發佈為新的 port 的一個社群活動。

The Basic idea 基本想法
------------------
The Ports System used in FreeBSD is dead simple. It should be easy for any open source software publisher to submit their code to FreeBSD. But they just don't know how simple it is, so we are gonna show 'em.

FreeBSD 用的 Ports 系統超簡單的。任何開源軟體的作者都可以輕易地發佈他們的程式碼到 FreeBSD 。但是他們不知道這有多簡單，所以讓我們來告訴大家。

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

#### Local poudriere 區域的 Poudriere

For practice purpose it will be convenient to prepare a computer in advance, installed with a functional and recent FreeBSD, with [Poudriere][poudriere] already installed and configured, and images already downloaded.

Optimally the participants should be able to ssh to the Test Server (running Poudriere) and either test their builds locally if they are very simple, or launch the tests in Poudriere.

The point is that the participants don't need to install anything, they will have access to a FreeBSD environment using ssh on the local network.

#### Local communication channel 區域通訊頻道

This can be an IRC channel created on the spot, or whatever other group instant messaging the organizers feel comfortable with. The point is to have a place where people can share URLs easily.

這可以是現場設立的 IRC 頻道，或是其他舉辦者熟悉的群組即時通訊軟體。這通訊頻道是讓參加者可以簡單地分享 URLs 。

#### User accounts 使用者帳號

The local FreeBSD server should be all prepared including the user accounts of the participants. To do so, probably it can be convenient to use github for registering participants, and grab ssh public keys from there, but any other method can be setup by the organizers.

The user accounts also can be created on the fly without much trouble at the beginning of each camp.

本地端的 FreeBSD 伺服器 應該準備好所有參加者的使用者帳號。要這樣做，或許可以用參加者的 github 帳號並從那裡取得 ssh 公開金鑰。或是舉辦者有其他設定方法也可以。

使用者帳號也可以在活動剛開始的時候建立，也不會造成太多麻煩。

#### Schedule 活動流程

There should be at the beginning some introduction talk about what are ports and how to prepare them, how to make a shar and how to submit them, then how to update a port with a diff file. Then a list of possible candidates for porting could be presented to the audience, sorted by categories and difficulties level. This introduction is at the discretion of the presenter.

It can be good to have also quick presentation of [bugzilla][bugzilla], [freshports][freshports], [portscout][portscout], [phabricator][phabricator], the [porter's handbook][porterhandbook], and other useful material.

Then everybody can try to create or update ports of their choice, all together in a close proximity with other people following the same path and not far from people that know the path very well.

When a port is ready, tested and uploaded, a committer can then show how the submission process is followed up and what leads to the port being committed in the ports tree.

一開始應該先介紹一下什麼是 ports，如何準備，如何分享和發佈，接下來是如何使用 diff 檔來更新一個 port。然後列出一個可以 porting 的清單給聽眾，根據不同的分類和難易程度來排序。這說明的部份由講者自行斟酌。

如果也能快速地介紹一下 [bugzilla][bugzilla], [freshports][freshports], [portscout][portscout], [phabricator][phabricator], the [porter's handbook][porterhandbook], 和其他相關資料的話，就更好了。

然後每個人都試著建立或是更新他們選擇的 ports，committer可以示範如何追蹤提交過程，以及怎樣將 port 提交到 ports 樹。

#### Fee 費用

Free of charge as FreeBSD !

如 FreeBSD 一樣，免費!

Conclusion 結論
-------------

A portscamp should be a great occasion to have great fun, learning useful stuff and meeting other people from various horizons.

Portscamp是一個很棒的活動，很有趣，可以學習有用的東西，還可以認識許多不同領域的人。

Taiwan Local PortsCamps 台灣本土 Portscamp
=============================

We are in progress of setting up the first sessions:

- find committers interested to participate (we already have araujo@)
- translate this page in traditional Chinese
- setup a date at the Taipei Hackerspace https://taipeihack.org/
- spread the word and find free software publishers that would be interested to participate and learn
- think about ideas to help finishing the translation of the [Porter's handbook in chinese][porterhandbooktw]
- prepare IRC channel #portscamp-tw on efnet? get a bot for factoids?
- setup a way for people to register to the first Portscamp (by mail? on a form? on facebook event? on meetup.com? on kktix?)

我們正在規劃第一次會議：
- 尋找有興趣參與的 committers (我們現在已經有 araujo@ )
- 將這個網頁翻譯成正體中文
- 預訂一個 Taipei Hackerspace的時間 https://taipeihack.org/
- 宣傳並尋找有興趣參加和學習的自由軟體作者
- 思考如何幫忙翻譯 the [Porter's handbook in chinese][porterhandbooktw]
- 在 Efnet 準備 IRC 頻道 #portscamp-tw ? get a bot for factoids?
- 建立一個註冊第一次 Portscamp 的方法 (用 email? 用表單？用 facebook 建立活動？用 meetup.com？用 kktix? )

[freebsd]: https://www.freebsd.org/
[freshports]: http://www.freshports.org/
[portscout]: http://portscout.freebsd.org/
[bugzilla]: https://bugs.freebsd.org/bugzilla/
[phabricator]: https://reviews.freebsd.org/
[poudriere]: https://www.freebsd.org/doc/handbook/ports-poudriere.html
[porterhandbook]: https://www.freebsd.org/doc/en/books/porters-handbook/
[porterhandbooktw]: https://www.freebsd.org/doc/zh_TW/books/porters-handbook/
