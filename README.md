# Murray Lu

AI 協作軟體開發（AI-assisted Software Development）｜需求分析｜API 整合｜工程驗證

將需求拆成可實作的功能與驗收條件，透過 AI 協作、程式碼審查與測試迭代。以下提供實際來源程式的可執行切片、來源 Commit SHA、架構、操作步驟與已知限制。

## 01 · [Mahjong Friends](https://github.com/MurrayLu/mahjong-friends)

麻將戰績管理網站：React → Hono API → 群組授權與結算規則 → SQL。展示完整結算與排行榜流程，並驗證非法寫入拒絕及交易回滾。

技術：TypeScript、React、Hono、SQLite；原始 Cloudflare 邊界以本機 adapter 隔離。

## 02 · [Trading System](https://github.com/MurrayLu/trading-system)

即時行情與交易執行系統（MuNTrade）：合成行情經事件匯流排（Event Bus）、風控門檻與 Paper Gateway，驗證委託、觸價成交與持倉更新。

技術：C#、.NET、WPF、事件處理。公開桌面是新建隔離展示（Isolated Demo），不是原始 WPF 介面；不連券商。

## 03 · [Backtesting & Research](https://github.com/MurrayLu/backtesting-research)

策略回測與市場研究平台（BacktestEngine）：回測引擎使用實際撮合與會計主線；獨立研究入口以只讀 SQLite 與可得時間（AvailableAt）規則查詢證據。

技術：C#、.NET、WPF、SQLite、確定性回放（Deterministic Replay）。公開 CLI 與縮減工作台使用合成資料，工作台明示 Isolated Demo。

## 角色與協作方式

本人選定作品與公開範圍並核准發布；本次 AI 協助讀碼、擷取、隔離展示、測試與文件。不主張全部獨立手寫或精確手寫比例；原始專案的精確分工與歷史 AI 使用情形未在本次查核。各 repository 清楚區分來源碼、調整碼與新建展示碼，不將切片驗收當作完整原系統驗證。

本次沒有公開原系統截圖、正式資料、交易紀錄、帳號、憑證、私有策略或原始 Git 歷史。公開供技術審查，未另行授予開源授權。
