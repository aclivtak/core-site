---
layout: post
title: 關鍵氣泡
tags: ['戰術', '中盤', '副砲', '同消', '關鍵氣泡']
---

在概論中我們提到，玩家主要的連鎖稱為「主砲」，而另一方面，除了主砲之外，玩家也可以有「副砲」，也就是其他比較小的連鎖。舉個例子： 

{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
|| Y           ||
|| Y           ||
|| B       Y B ||
|| B B   R R R ||
|| G G   Y Y Y ||
|| G B G B B B ||
|| B R B Y G R ||
|| B Y Y G R R ||
|| R R R Y G G ||
++=============++
{% endpuyosim %}

在上圖中，主砲從一樓右下角被蓋住的紅色L字開始，有六連鎖，而副砲有兩個：
1. 從D行紅色發火有三連鎖，
2. 從C行綠色發火有四連鎖。

{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
|| Y     R     ||
|| Y           ||
|| B       Y B ||
|| B B   R R R ||
|| G G   Y Y Y ||
|| G B G B B B ||
|| B R B Y G R ||
|| B Y Y G R R ||
|| R R R Y G G ||
++=============++
{% endpuyosim %}
{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
|| Y           ||
|| Y           ||
|| B   G   Y B ||
|| B B   R R R ||
|| G G   Y Y Y ||
|| G B G B B B ||
|| B R B Y G R ||
|| B Y Y G R R ||
|| R R R Y G G ||
++=============++
{% endpuyosim %}
{% figure %}
{% caption %}
左圖：從D行紅色發火有三連鎖；右圖：從C行綠色發火有四連鎖。
{% endfigure %}

像上圖這樣有副砲的連鎖，在戰術上具有優勢，因為副砲可用來干擾對手。如果成功用副砲逼出了對手的主砲，那還能利用對手施放連鎖的硬直時間加連鎖。

那麼，如何作副砲呢？

最重要的概念是：不要放上關鍵氣泡！

## 什麼是關鍵氣泡？

繼續以圖1舉例。一樓的主砲原本有六連鎖，二樓右側的副砲是三連鎖。此時若是在F行放上一顆紅色，那麼副砲跟主砲就接起來了，成為九連鎖！

{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
|| Y           ||
|| Y         R ||
|| B       Y B ||
|| B B   R R R ||
|| G G   Y Y Y ||
|| G B G B B B ||
|| B R B Y G R ||
|| B Y Y G R R ||
|| R R R Y G G ||
++=============++
{% endpuyosim %}
{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
|| Y     R     ||
|| Y         R ||
|| B       Y B ||
|| B B   R R R ||
|| G G   Y Y Y ||
|| G B G B B B ||
|| B R B Y G R ||
|| B Y Y G R R ||
|| R R R Y G G ||
++=============++
{% endpuyosim %}

換個角度想，**如果不放上F行那顆紅色，那二樓與一樓就接不起來，可以將二樓作為副砲**。F行的這顆紅色可以把連鎖接起來，我們就把他稱為*關鍵氣泡*，而在這裡，我們刻意不放上關鍵氣泡，藉此將連鎖拆成數段，利於中盤的攻防。如此作出來的副砲，可當作小連鎖騷擾對方／防禦對方；如果副砲無利可圖時，再把關鍵氣泡放上，與主砲連起來即可。

關鍵氣泡常常指的是與一樓接起來的氣泡，但是不限於此。放上關鍵氣泡的作法，又稱為「確定化[^1]」。再來幾個刻意不放上關鍵氣泡的例子：

## 關鍵氣泡例1

在下圖的[3-1階梯]({{ "wiki/B_chain/b_regular_form/i_stairs" | relative_url }})中，連鎖已經排到二樓，主砲發火點是B行的黃色，不過右側的連鎖還未與主砲連接。

{% puyosim mode:0 %}
                 
||             ||
||             ||
|| G           ||
|| B       Y   ||
|| G       Y   ||
|| Y       B Y ||
|| G Y     B Y ||
|| G Y     R B ||
|| G R Y   B B ||
|| B G R   G R ||
|| B G R Y G R ||
|| B G R Y G R ||
++=============++
{% endpuyosim %}

此時若是在D行擺上關鍵氣泡的黃綠，可以將連鎖接起來；另一方面，若是直接消除D行的綠色，會是個二連三消的副砲。

{% puyosim mode:0 %}
                 
||             ||
||             ||
|| G           ||
|| B Y     Y   ||
|| G       Y   ||
|| Y       B Y ||
|| G Y     B Y ||
|| G Y     R B ||
|| G R Y G B B ||
|| B G R Y G R ||
|| B G R Y G R ||
|| B G R Y G R ||
++=============++
{% endpuyosim %}
{% puyosim mode:0 %}
                 
||             ||
||             ||
|| G           ||
|| B       Y   ||
|| G       Y   ||
|| Y       B Y ||
|| G Y     B Y ||
|| G Y   G R B ||
|| G R Y   B B ||
|| B G R   G R ||
|| B G R Y G R ||
|| B G R Y G R ||
++=============++
{% endpuyosim %}
{% figure %}
{% caption %}
左圖：擺上D行的黃綠後，從B行黃色發火主線；右圖：直接消除D行的綠色，是個二連三消的副砲。
{% endfigure %}

D行擺上黃綠，可以將連鎖接起來；若是直接消除D行綠色，會是個二連三消的副砲

## 關鍵氣泡例2

下圖的連鎖亦已經排到二樓，而且我們可以看出二樓連鎖的形狀有點像是[鑰匙排法]({{ "wiki/B_chain/b_regular_form/ii_sandwich" | relative_url }})。

{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
||             ||
|| R G     R R ||
|| R Y   B Y R ||
|| Y G   G G Y ||
|| R Y G B G Y ||
|| R Y G B B R ||
|| G G B G R R ||
|| Y Y Y B B B ||
|| G G G R R R ||
++=============++
{% endpuyosim %}

這個主砲有相當多的關鍵氣泡並未放上，不過相對的，他的副砲很多。首先，如果要發火主線的話，需要擺上C行的藍綠、F行的黃綠，以及AB行兩顆二樓通往一樓的黃綠，然後才能發火。

{% puyosim mode:0 %}
                 
||             ||
||         R   ||
||           G ||
|| G Y       Y ||
|| R G     R R ||
|| R Y G B Y R ||
|| Y G B G G Y ||
|| R Y G B G Y ||
|| R Y G B B R ||
|| G G B G R R ||
|| Y Y Y B B B ||
|| G G G R R R ||
++=============++
{% endpuyosim %}
{% figure %}
{% caption %}
擺上許多關鍵氣泡後，可以從E行紅色發火主線。
{% endfigure %}

假設不打算擺完全部的關鍵氣泡，也可以在F行擺上黃綠後，直接從E行紅色發火，這會是個四連鎖的副砲；如果把C行的藍綠也補上的話，那就是個七連鎖的大副砲。

{% puyosim mode:0 %}
                 
||             ||
||         R   ||
||           G ||
||           Y ||
|| R G     R R ||
|| R Y   B Y R ||
|| Y G   G G Y ||
|| R Y G B G Y ||
|| R Y G B B R ||
|| G G B G R R ||
|| Y Y Y B B B ||
|| G G G R R R ||
++=============++
{% endpuyosim %}
{% puyosim mode:0 %}
                 
||             ||
||         R   ||
||           G ||
||           Y ||
|| R G     R R ||
|| R Y G B Y R ||
|| Y G B G G Y ||
|| R Y G B G Y ||
|| R Y G B B R ||
|| G G B G R R ||
|| Y Y Y B B B ||
|| G G G R R R ||
++=============++
{% endpuyosim %}
{% figure %}
{% caption %}
左圖：在F行擺上黃綠後，從E行紅色發火四連鎖的副砲；右圖：如果C行的藍綠也補上了，就是個七連鎖的副砲。
{% endfigure %}

要是連一顆關鍵氣泡都不想補，也可以直接消掉C行的綠色，這是個[二連雙消]({{ "wiki/B_chain/g_others/i_power_chain" | relative_url }})的三連鎖！

{% puyosim mode:0 %}
                 
||             ||
||             ||
||             ||
||             ||
|| R G G   R R ||
|| R Y   B Y R ||
|| Y G   G G Y ||
|| R Y G B G Y ||
|| R Y G B B R ||
|| G G B G R R ||
|| Y Y Y B B B ||
|| G G G R R R ||
++=============++
{% endpuyosim %}

最後，來一個比較特別的副砲例子：在E、F行擺上幾顆氣泡，但讓這些氣泡的排列方式跟前面不同，然後從D行發火紅色。結果這個副砲神奇地從右邊消到左邊，總共有八連鎖！

{% puyosim mode:0 %}
                 
||             ||
||             ||
||       R   R ||
|| G Y     G Y ||
|| R G     R R ||
|| R Y   B Y R ||
|| Y G   G G Y ||
|| R Y G B G Y ||
|| R Y G B B R ||
|| G G B G R R ||
|| Y Y Y B B B ||
|| G G G R R R ||
++=============++
{% endpuyosim %}

這個副砲的連鎖方向很不直觀，因此有很大機會能造成對手的判斷錯誤。

如果對手事先知道是八連鎖，正確的選擇是：趁著副砲的施放時間把他的連鎖加大。但要是他判斷錯誤、認為這個副砲沒那麼大，他可能會用個五連鎖來對應，結果就是他白白浪費了五連鎖的氣泡量，而且五連鎖的施放期間他也不能延伸連鎖了，等於浪費資源也浪費時間。

## 何時該擺上關鍵氣泡？

前面提到，刻意不擺關鍵氣泡的作法能將連鎖拆成數段，有利中盤的攻防。那麼，何時該擺上關鍵氣泡呢？擺上關鍵氣泡的有利或不利，如何判斷？有幾個指標可作為參考[^2]：
* 快要被蓋住的時候：如果在沒擺上關鍵氣泡的情況下，對手給了兩～三排的攻擊，吃下來的話很難再擺上關鍵氣泡，連鎖也就接不起來，若對手再用主砲追擊便會相當不利。因此，若是注意到對手要作小型攻擊，可先將關鍵氣泡放上。
* 雙方暫時都沒有要用小連鎖攻防的時候：例如對手沒有要用小連鎖催促，此時自己可選擇將重點放在主砲的延伸，可將關鍵氣泡放上
* 其他無利可圖的時候：例如對手也有副砲，而且比你的還大。那此時將副砲打出去可能會導致不利，不如將關鍵氣泡放上。

[^1]: [ぷよぷよ攻略　確定領域と全連鎖理論（超上級者向け）](https://ch.nicovideo.jp/tom_nadja/blomaga/ar919395).
[^2]: [ぷよぷよ用語辞典　キーぷよ](https://www26.atwiki.jp/puyowords/pages/52.html).