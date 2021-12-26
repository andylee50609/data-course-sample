【Week1 Ruled-based recommendation】

清楚記載這個專案的目的和結果，最後的推薦分數是多少，是否有成功

目的：透過真實店商之資料集(包含產品資訊以及顧客評論資訊)進行資料分析，進而提升客戶購買之機率。

此次主要係以「Ruled-based」之方式進行客戶資料之分析以進行推薦，並以推薦之10項商品於201809被購買之機率進行效益評估，主要使用之規則及結果如下：

[rule_1]：以商品銷售排行進行推薦：0.51%

[rule_2]：以評論次數以及客戶評論(商品熱度)進行推薦：0.0%

[rule_3]：以1個月內之評論次數以及客戶評論(商品熱度)進行推薦：1.69%

[rule_4]：以3個月內之評論次數以及客戶評論(商品熱度)進行推薦：4.24%

結果：透過rule4所進行推薦之方式最準確。

[rule_1]：先行推出之商品可以透過時間之累積提升銷售量，故有失準之可能

[rule_2]：商品有可能有退燒之情形，故造成推薦不準確

[rule_3]：1個月之資料量有不足之可能，故造成推薦不準確

