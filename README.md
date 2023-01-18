# R-breaker-Bitcoin
### 邏輯：

空倉時：突破策略  
多趨勢：盤中價 > 突破買入價 -> 開倉做多  
空趨勢：盤中價 < 突破賣出價 -> 開倉做空  

持倉時：反轉策略  
持多：(時段最高價>觀察賣出價 & 盤中價<反轉賣出價) or 空趨勢 -> 反做空or平倉  
持空：(時段最低價<觀察買入價 & 盤中價>反轉買入價) or 多趨勢 -> 反做多or平倉  

![R-breaker](https://i.imgur.com/Kr7lEOq.png"多單邏輯")
![R-breaker](https://i.imgur.com/PWev9AD.png"空單邏輯")
