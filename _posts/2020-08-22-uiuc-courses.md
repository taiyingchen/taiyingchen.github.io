---
layout: post
title: 在 UIUC 交換的日子 - 修課
feature-img: "assets/img/R0002364.jpeg"
---

![]({{ site.baseurl }}/assets/img/R0001067.jpeg)

在 UIUC 交換的兩個學期 2019 Fall 跟 2020 Spring 各修了 4 門，合計 8 門 CS 的課。國外的課程大家都會用代號來稱呼，第一個數字代表 Level，數字越高代表較進階的課程。400 和 500 Level 屬於研究所的課程，400 Level 的課可以選擇修 3 學分或是 4 學分，4 學分通常是多一個 final project。另外比較特別的是，會有很多門課都叫 CS498 或 CS598，這類課程似乎是實驗性質，所以內容通常都比較特別。

每堂課都各有優缺點，我會用教學品質、作業規劃、職場實用以及個人推薦來評價這些課程，滿分是五顆⭐️。教學品質會因教授而異，所以我也紀錄當時授課教授的名字。作業規劃包含評分和目標描述是否清楚、寫起來有不有趣、有沒有 TA 和 Office hour 可以問等等。職場實用代表修完這門課後，對未來在職場上擔任一般軟體工程師（SDE）是否實用、有幫助。均為個人評價僅供參考。

2019 Fall
* CS412 - Introduction to Data Mining
* CS418 - Interactive Computer Graphics
* CS427 - Software Engineering I
* CS498 - Computational Advertising

## CS412 - Introduction to Data Mining

By Hanghang Tong

修這門課原本是看到授課教授是 Jiawei Han，殊不知只是掛名，最後是他學生來上課。整體課程偏簡單，基本上是從頭開始教起，如果修過林軒田或李宏毅的機器學習，我覺得可以不用修這門課。但修完也是有些許收穫，像是 Pattern recognition 就是過去沒有接觸的領域。教授上課講的滿清楚，只是說話偏慢，所以後來我都沒去教室上課，是用 2 倍數看完上課錄影。作業中規中矩，實作 Apriori、Decision Tree、Gaussian Mixture Model 等演算法，跑測資評分。有個蠻死的規定是不能用任何套件，導致要自己算反矩陣，也練習把作業包成套件。

* https://github.com/taiyingchen/apriori
* https://github.com/taiyingchen/classifier
* https://github.com/taiyingchen/cluster

```
成績 A
教學 ⭐️⭐️
作業 ⭐️⭐️⭐️
職場 ⭐
綜合 ⭐️⭐
```

## CS418 - Interactive Computer Graphics

By Eric Gene Shaffer

這門課是上電腦圖學，我修之前幾乎沒有基礎，先備條件只有線性代數，可以說整學期都在計算矩陣。涵蓋圖形放大縮小、旋轉、反射、折射等等。教授有時候上課講一講會越來越小聲，像是喃喃自語，所以聽得有點痛苦。因為是早上九點的課，開始下雪之後就不太常去上課了...。作業非常有趣，是用 JavaScript 寫成網頁上的動畫，會用到 WebGL 和矩陣套件 [glMatrix](http://glmatrix.net/)。其中一個作業如下，要在視線移動、旋轉茶壺下，計算經由反射後茶壺上的每個像素。作業最後能當自己的 Portfolio。

https://taiyingchen.com/CS418

![](https://taiyingchen.com/CS418/MP3/img/animation.gif)

```
成績 A+
教學 ⭐️⭐️
作業 ⭐️⭐️⭐️⭐️
職場 ⭐️
綜合 ⭐️⭐️⭐️
```

## CS427 - Software Engineering I

By Grigore Rosu

我修的所有課中，對職場最有幫助的就是這門課。基本上，就是教你如何跟別人一起開發程式，內容包含功能設計、Unit/Integration Test、System Design、Design Pattern。每次作業都會隨機分配組員， 2 到 3 人一組，印象中組員都蠻給力，不太會擺爛，合作起來蠻愉快的。Project 是一個大組一起做，大概 10 個人一組，模擬在職場上開發程式的流程，為期 2 個月左右，一開始要進行進度規劃、分配工作，之後每一段時間跟 TA 跑 Sprint 報告進度。Project 內容是擴增一個用 Java 寫的醫療管理系統 iTrust，要寫 Unit/Integration Test，Commit 要經過 Code Review。這個跟我現在工作的流程蠻類似，所以入職後比較容易上手。我覺得可以把這門課當作入職前的 bootcamp，以我的經驗不論是實習或是正職，公司都假設你擁有這些基礎知識跟能力，所以不能期待進去再學。更能利用這門課，提早培養軟體工程師的良好習慣，個人蠻推薦的。

```
成績 A
教學 ⭐️⭐️⭐️
作業 ⭐️⭐️⭐️⭐️
職場 ⭐️⭐️⭐️⭐️⭐️
綜合 ⭐️⭐️⭐️⭐ 
```

## CS498 - Computational Advertising

By Hari Sundaram

「當你上網時，廣告是如何出現在你的瀏覽器上？」這門課介紹了網路廣告的生態跟流程。會從賽局理論、競標開始介紹，因為網路上的廣告事實上是在你按下 Google 搜尋後的幾毫秒內經過競標後出現在你眼前的。接著介紹隱私、文字廣告、圖片廣告、推薦系統，幫你解惑「為什麼 Google、Facebook 都知道我想買 XYZ？」這門課有趣的地方是它包含了經濟學、數學、資訊、心理學，所以能從不同的角度切入。不同於填鴨式的教學，教授很常跟學生互動，讓你主動思考，很自然地把整堂課連貫起來。課程安排的很棒，可以看到廣告領域中的樹以及林。

https://github.com/taiyingchen/CS498HS

```
成績 A+
教學 ⭐️⭐️⭐️⭐️⭐️
作業 ⭐️⭐️⭐️⭐️
職場 ⭐️
綜合 ⭐️⭐️⭐️⭐️
```

2020 Spring
* CS434 - Mobile Computing & Application
* CS438 - Communication Networks
* CS498 - Audio Computing Lab
* CS598 - Advanced Social & Information

![]({{ site.baseurl }}/assets/img/R0002350.jpeg)

## Conclusion