PortsCamp
==============

這是 [FreeBSD][freebsd] committers 協助大家了解甚麼是 ports 和如何打包軟體並發佈為新的 port 的一個社群活動。

基本想法
------------------
FreeBSD 用的 Ports 系統超簡單的。任何開源軟體的作者都可以輕易地發佈他們的程式碼到 FreeBSD 。但是他們不知道這有多簡單，所以讓我們來告訴大家。

The Camp
-------------------

#### 時間的安排
這個活動的時間可以安排為幾個小時到一整天。由活動參加者和主辦者而定。但是活動時間不適合少於一個小時。

#### 地點
最好可以找到一個地點，有良好的網路連線和區域網路的架設，這樣我們可以設置一台測試伺服器。還需要桌椅，讓大家可以使用自己的筆記型電腦。

#### 主辦者
最理想的是有一些 FreeBSD committers 可以參與，這樣他們可以解釋發佈的步驟，詳述審核過程，並示範他們如何測試，一直到將你的成果提交到 ports 樹。

#### 區域的 Poudriere
為了要能練習，比較方便的是有一台先準備好的電腦，安裝最新的，已經裝好和設定好 [Poudriere][poudriere]  的FreeBSD 。

最好參加者能夠 ssh 到測試伺服器 (執行 Poudriere)，或是如果他們的建構 (build)很簡單的話，就直接在本地端測試，或是在  Poudriere 執行測試。

重點是參加者不需要安裝任何東西，他們可以透過區域網路用 ssh 連線進 FreeBSD 的環境。

#### 區域通訊頻道
這可以是現場設立的 IRC 頻道，或是其他主辦者熟悉的群組即時通訊軟體。這通訊頻道是讓參加者可以簡單地分享 URLs 。

#### 使用者帳號
本地端的 FreeBSD 伺服器 應該準備好所有參加者的使用者帳號。要這樣做，或許可以用參加者的 github 帳號並從那裡取得 ssh 公開金鑰。或是主辦者有其他設定方法也可以。

使用者帳號也可以在活動剛開始的時候建立，也不會造成太多麻煩。

#### 活動流程

一開始應該先介紹一下什麼是 ports，如何準備，如何打包和發佈，接下來是如何使用 diff 檔來更新一個 port。然後列出一個可以 porting 的清單給聽眾，根據不同的分類和難易程度來排序。這說明的部份由講者自行斟酌。

如果也能快速地介紹一下 [bugzilla][bugzilla], [freshports][freshports], [portscout][portscout], [phabricator][phabricator], the [porter's handbook][porterhandbook], 和其他相關資料的話，就更好了。

然後每個人都試著建立或是更新他們選擇的 ports，committer可以示範如何追蹤提交過程，以及怎樣將 port 提交到 ports 樹。

#### 費用
如 FreeBSD 一樣，免費!

結論
-------------

Portscamp是一個很棒的活動，很有趣，可以學習有用的東西，還可以認識許多不同領域的人。

台灣本土 Portscamp
=============================

我們正在規劃第一次會議：
- 尋找有興趣參與的 committers (我們現在已經有 araujo@ )
- 將這個網頁翻譯成正體中文
- 預訂一個 Taipei Hackerspace的時間 https://taipeihack.org/
- 宣傳並尋找有興趣參加和學習的自由軟體作者
- 思考如何幫忙翻譯 the [Porter's handbook in chinese][porterhandbooktw]
- 在 Efnet 準備 IRC 頻道 #portscamp-tw ? 要用 IRC 機器人來紀錄嗎?
- 建立一個註冊第一次 Portscamp 的方法 (用 email? 用表單？用 facebook 建立活動？用 meetup.com？用 kktix? )

[freebsd]: https://www.freebsd.org/
[freshports]: http://www.freshports.org/
[portscout]: http://portscout.freebsd.org/
[bugzilla]: https://bugs.freebsd.org/bugzilla/
[phabricator]: https://reviews.freebsd.org/
[poudriere]: https://www.freebsd.org/doc/handbook/ports-poudriere.html
[porterhandbook]: https://www.freebsd.org/doc/en/books/porters-handbook/
[porterhandbooktw]: https://www.freebsd.org/doc/zh_TW/books/porters-handbook/
