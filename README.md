# 2nd-ML100Days

### 一個普通人，在資料科學領域的撞牆筆記

為了讓做這件事情更有趣一點，稍微在每一天的學習過程中做一些可能無關緊要的心得記錄。

**2019-4-18** — 作業一，覺得很難，對於資料科學沒什麼感覺，還好有同事一直給我問。

**2019-4-18** — 作業二，假借看展名義把同事拐去咖啡廳，繼續第二天的作業。

**2019-4-18** — 作業三，因為做得很快所以就可以繼續第三天的作業了。

**2019-4-19** — 作業四，剛好在做完前三天作業的當天，第四天～第六天的題目發佈了，在睡前看一下PPT檔案吧！

* 關於label encoder和one hot encoder的不同 [label-encoder-vs-one-hot-encoder](https://medium.com/@contactsunny/label-encoder-vs-one-hot-encoder-in-machine-learning-3fc273365621)
  * 離散的特徵取值之間沒有大小意義那就使用one-hot編碼
  * 離散的特徵取值之間有大小意義可以建立mapping來做數值的映射

**2019-4-19** — 作業五，對於圖形化的方法還要再練習更熟悉，途中碰到各種困難是因為對於畫圖方式的陌生​，語言花越多時間越熟悉，可能前面一段時間(某TED演講是說20小時)都需要稍微撞一下牆:joy:。

**2019-4-19** — 作業六，關於異常值(outliers)的出現原因、檢查流程、處理方法。

**2019-4-20** — 同樣在作業六，稍微看了一下補充資料中關於統計相關的知識點，但是資料處理的程式碼方面還是不夠熟悉，所以又補了一下關於numpy，pandas程式庫的基本概念。折騰了一段時間終於把ecdf(經驗分佈函數)畫出來。

**2019-4-21** — 發現作業六關於[型別判斷的問題](<https://www.cupoy.com/qa/kwassist/ai_tw/0000016A3B608C23000003B66375706F795F72656C656173655155455354>)，並且修改程式碼。有下面兩種寫法。

```python
app_train.dtypes.isin([np.dtype('int64'),np.dtype('float64')]) 
app_train.select_dtypes(include=['float64', 'int64'])
```

