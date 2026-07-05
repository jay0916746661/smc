# SMC Market Dashboard

一個用 Smart Money Concept 架構設計的跨市場行情追蹤面板原型。

## 內容

- 大行情總覽：美股、台股、加密市場同時掃描
- 市場清單：SPY、QQQ、NVDA、加權指數、台積電、電子期、BTC、ETH、SOL
- 即時行情：透過 TradingView 元件載入可縮放、可切週期的即時 K 線與 ticker tape
- SMC 線圖分析：依目前標的/劇本重畫 Liquidity、BOS/MSS、OB、Entry、SL、TP
- 白話解釋：線圖旁同步顯示劇本說明、不要做的情況與 SMC 名詞速查
- 派網部位：顯示目前持倉、權重、前五大集中度、分類配置與 24h 漲跌
- SMC 策略圖解：畫出趨勢延續做多、掃高反轉做空、盤整等待突破三種交易路徑
- 標的分析：加入使用者美股持倉與台股觀察池，點 watchlist、分析卡或持倉列可切換即時圖
- SMC 圖表標註：BOS、MSS、Liquidity Grab、Order Block、Premium / Discount
- 盤前檢查清單與 setup score
- 交易計畫與 session journal

## 使用

直接打開 `smc-market-dashboard.html` 即可使用。

即時圖表需要瀏覽器能連線到 TradingView 的外部元件。

派網部位目前是依使用者貼上的快照資料呈現；若要自動刷新持倉、成本與即時損益，需要另外串接派網 API。
