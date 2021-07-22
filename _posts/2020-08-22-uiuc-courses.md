---
layout: post
title: 在 UIUC 交換的日子 - 修課
feature-img: "assets/img/R0002364.jpeg"
---

![]({{ site.baseurl }}/assets/img/R0001067.jpeg)

在 UIUC 交換的兩個學期 2019 Fall 跟 2020 Spring 各修了 4 門，合計 8 門 CS 的課。國外的課程大家都會用代號來稱呼，第一個數字代表 Level，數字越高代表較進階的課程。400 和 500 Level 屬於研究所的課程，400 Level 的課可以選擇修 3 學分或是 4 學分，4 學分通常是多一個 final project。另外比較特別的是，會有很多門課都叫 CS498 或 CS598，這類課程似乎是實驗性質，所以內容通常都比較特別。

每堂課都各有優缺點，我會用教學品質、作業規劃、職場實用以及綜合推薦來評價這些課程，滿分是五顆⭐️。教學品質會因教授而異，所以我也紀錄當時授課教授的名字。作業規劃包含評分和目標描述是否清楚、寫起來有不有趣、有沒有 TA 和 Office hour 可以問等等。職場實用代表修完這門課後，對未來在職場上擔任一般軟體工程師（SDE）是否實用、有幫助。均為個人評價僅供參考。

**2019 Fall**
* CS412 - Introduction to Data Mining
* CS418 - Interactive Computer Graphics
* CS427 - Software Engineering I
* CS498 - Computational Advertising

## CS412 - Introduction to Data Mining

By Hanghang Tong

修這門課原本是看到授課教授是 Jiawei Han，殊不知只是掛名，最後是他學生來上課。整體課程偏簡單，基本上是從頭開始教起，如果修過林軒田或李宏毅的機器學習，我覺得可以不用修這門課。但修完也是有些許收穫，像是 Pattern Recognition 就是過去沒有接觸的領域。教授上課講的滿清楚，只是說話偏慢，所以後來我都沒去教室上課，是用 2 倍數看完上課錄影。作業中規中矩，實作 Apriori、Decision Tree、Gaussian Mixture Model 等演算法，跑測資評分。有個蠻死的規定是不能用任何套件，導致要自己算反矩陣，也練習把作業包成套件。

* https://github.com/taiyingchen/apriori
* https://github.com/taiyingchen/classifier
* https://github.com/taiyingchen/cluster

```
成績 A
教學 ⭐️⭐️
作業 ⭐️⭐️⭐️
職場 ⭐
綜合 ⭐️⭐
```

## CS418 - Interactive Computer Graphics

By Eric Gene Shaffer

這門課是上電腦圖學，我修之前幾乎沒有基礎，先備條件只有線性代數，可以說整學期都在計算矩陣。涵蓋圖形放大縮小、旋轉、反射、折射等等。教授有時候上課講一講會越來越小聲，像是喃喃自語，所以聽得有點痛苦。因為是早上九點的課，開始下雪之後就不太常去上課了...。作業非常有趣，是用 JavaScript 寫成網頁上的動畫，會用到 WebGL 和矩陣套件 [glMatrix](http://glmatrix.net/)。其中一個作業如下，要在視線移動、旋轉茶壺下，計算經由反射後茶壺上的每個像素。作業最後能當自己的 Portfolio。

https://taiyingchen.com/CS418

![](https://taiyingchen.com/CS418/MP3/img/animation.gif)

```
成績 A+
教學 ⭐️⭐️
作業 ⭐️⭐️⭐️⭐️
職場 ⭐️
綜合 ⭐️⭐️⭐️
```

## CS427 - Software Engineering I

By Grigore Rosu

我修的所有課中，對職場最有幫助的就是這門課。基本上，就是教你如何跟別人一起開發程式，內容包含功能設計、Unit/Integration Test、System Design、Design Pattern。每次作業都會隨機分配組員， 2 到 3 人一組，印象中組員都蠻給力，不太會擺爛，合作起來蠻愉快的。Project 是一個大組一起做，大概 10 個人一組，模擬在職場上開發程式的流程，為期 2 個月左右，一開始要進行進度規劃、分配工作，之後每一段時間跟 TA 跑 Sprint 報告進度。Project 內容是擴增一個用 Java 寫的醫療管理系統 iTrust，要寫 Unit/Integration Test，Commit 要經過 Code Review。這個跟我現在工作的流程蠻類似，所以入職後比較容易上手。我覺得可以把這門課當作入職前的 Bootcamp，以我的經驗不論是實習或是正職，公司都假設你擁有這些基礎知識跟能力，所以不能期待進去再學。更能利用這門課，提早培養軟體工程師的良好習慣，個人蠻推薦的。

```
成績 A
教學 ⭐️⭐️⭐️
作業 ⭐️⭐️⭐️⭐️
職場 ⭐️⭐️⭐️⭐️⭐️
綜合 ⭐️⭐️⭐️⭐ 
```

## CS498 - Computational Advertising

By Hari Sundaram

「當你上網時，廣告是如何出現在你的瀏覽器上？」這門課介紹了網路廣告的生態跟流程。會從賽局理論、競標開始介紹，因為網路上的廣告事實上是在你按下 Google 搜尋後的幾毫秒內經過競標後出現在你眼前的。接著介紹隱私、文字廣告、圖片廣告、推薦系統，幫你解惑「為什麼 Google、Facebook 都知道我想買 XYZ？」這門課有趣的地方是它包含了經濟學、數學、資訊科學、心理學，所以能從不同的角度切入。不同於填鴨式的教學，教授很常跟學生互動，讓你主動思考，很自然地把整堂課連貫起來。課程安排的很棒，可以看到廣告領域中的樹以及林。

https://github.com/taiyingchen/CS498HS

```
成績 A+
教學 ⭐️⭐️⭐️⭐️⭐️
作業 ⭐️⭐️⭐️⭐️
職場 ⭐️
綜合 ⭐️⭐️⭐️⭐️
```

***

**2020 Spring**
* CS434 - Mobile Computing & Application
* CS438 - Communication Networks
* CS498 - Audio Computing Lab
* CS598 - Advanced Social & Information

這學期因為疫情的關係，上半學期還是實體上課，但下半學期全改為遠端上課。因為大家都是第一次遠端上課，教學品質難免被打折扣，所以我還是以上半學期實體上課的經驗來評價比較公平一點。

## CS434 - Mobile Computing & Application

By Romit Roy Choudhury

因為寒假的實習在寫 iOS App，選課時沒多想，以為這門課也是學寫一些手機 App，沒想到完全搞錯了。這門課事實上教的是更底層的應用，教了如何計算和應用手機、Beacon 等行動裝置上收集的資料。這門課最推薦的是教授，他教得非常清楚直觀，幾乎不用先備條件，甚至開學前幾週都還在幫大家複習線性代數、傅立葉轉換。他蠻強調他不在意成績，只在意大家有沒有真的學會，所以他也沒有急著要這學期上完哪些內容，寧可慢慢上到每個人都融會貫通。他還會記得每個同學的名字，非常親切，是可以衝著他修任何他開的課。除了基礎知識外，課程中也會讀相關的 paper 以及教授的研究，包含和 Uber 合作的專利等。第一次作業是利用手機內三軸加速器的資料寫一個計步器。第二次作業則是給加速器、陀螺儀計算手機旋轉的方向，整體偏簡單。Project 原本計劃是在課堂上 Demo，改成遠端後就沒那麼有趣了。

```
成績 A
教學 ⭐️⭐️⭐️⭐️⭐️
作業 ⭐️⭐️⭐️
職場 ⭐️⭐️
綜合 ⭐️⭐️⭐️⭐️⭐️
```

## CS438 - Communication Networks

By Robin Kravets

我跟網路很不熟所以才選了這門課，教網路的基本概念像是 7 層 OSI Model、IP Addressing、Subnetting、CIDR、TCP vs UDP、DNS 等。工作日常就會處理 IP Routing、DNS Delegation，或是 trace packet loss，所以這些知識對職場很有幫助。教授教得中規中矩，如果以前修過網路相關的課就不需要修這門了。Project 是用 UDP 實作 TCP three-way handshake，和實作 Routing Algorithm，是用 C/C++ 實作，寫完會更熟悉但我自己覺得太底層了，職場上用不太到。因為疫情成績只分成過和沒過。

```
成績 Pass
教學 ⭐️⭐️⭐️
作業 ⭐️⭐️
職場 ⭐️⭐️⭐️⭐️
綜合 ⭐️⭐️⭐️
```

## CS498 - Audio Computing Lab

By Paris Smaragdis

這門是我的愛課之一，整體而言，教授教得很好、助教人很好、作業很有趣。教如何處理語音訊號和實作許多常見的聲音效果器。
因為是 Lab，整堂課非常著重實作。一個禮拜兩堂課，一堂是 lecture 教理論知識，另一堂 lab 則是大家帶電腦跟耳機去教室，然後把當週教的理論實作出來，教授跟助教會在現場開放問問題，教授會到你旁邊看你的 code、幫你 debug。這樣的教學方式其實效果蠻好的，很多觀念因為實作會更印象深刻。每個禮拜都會有 lab 上課時出的作業，然後隔一個禮拜要交，所以如果 delay 就會變成每個禮拜都在趕上禮拜的作業。作業是用 Python Jupyter Notebook，實作環境效果器、等化器、降噪、調整音高等等，記得都在做傅立葉轉換，在頻率空間處理訊號，然後再轉回時間空間。有次作業要實作浴室的環境 filter，還要抱著電腦到浴室錄音。

https://github.com/taiyingchen/CS498PS

```
成績 A+
教學 ⭐️⭐️⭐️⭐️⭐️
作業 ⭐️⭐️⭐️⭐️⭐️
職場 ⭐️
綜合 ⭐️⭐️⭐️⭐️⭐️
```

## CS598 - Advanced Social & Information

By Hari Sundaram

這門課延續上學期的 Computational Advertising，研究在資源限制下社群網路、資訊等如何影響每個人的 decision making。是一門研究導向的課程，要念一堆的 paper，課程安排是每組同學分配一篇 paper，然後由同學上台報告 paper，然後接著討論。可以學到很新、很深的知識和研究，但我自己沒那麼喜歡做研究，所以上到後面就興致缺缺了。有興趣可以參考下面的課程網站。

https://courses.engr.illinois.edu/cs598hs/sp2020/

```
成績 A+
教學 ⭐️⭐️⭐️
作業 ⭐️⭐️
職場 ⭐️
綜合 ⭐️⭐️
```

## Conclusion

諷刺的是，我覺得有趣的課在職場上幾乎用不到。我覺得除非應徵特定領域的軟體工程師，像是影像、訊號、機器學習之類，否則一個 SDE 的工作日常根本不會碰到矩陣、傅立葉轉換或是賽局理論，這些應該是 Data Scientist 或是 PhD 才需要煩惱的事。但不可否認，仍然能在這些課中練習獨立學習和實作的能力，間接增加職場的生存條件。要說最後悔沒修的課就是大名鼎鼎的 CS425 Distributed System，這門課應該對求職跟工作上超有幫助，聽修過的人說面試都被問這堂課的 project，然後要修 4 學分才需要做 project，但 project 才是這門課的精華，loading 可想而知非常重。

下一篇，UIUC - 課外。

![]({{ site.baseurl }}/assets/img/R0002350.jpeg)
