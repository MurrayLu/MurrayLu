# Murray Lu

以需求分析、系統規劃與 AI 協作方式開發個人軟體專案。通常先釐清問題、討論架構與模組、定義規格及驗收方式，再由 AI 協助實作，透過實際執行和測試持續調整。

## Projects

### 01 · [Mahjong Friends](https://github.com/MurrayLu/mahjong-friends)
**麻將戰績管理網站｜React · TypeScript · Hono · Cloudflare Workers / D1**

從朋友的記分需求開始，逐步增加結算、群組、排行榜和互動功能。公開程式提供前端、API、業務邏輯及 SQL 整合流程。

**[Live Website](https://mahjongfriend.twsites.workers.dev/)** · [Source & Local Demo](https://github.com/MurrayLu/mahjong-friends)

### 02 · [Trading System](https://github.com/MurrayLu/trading-system)
**即時行情與交易執行系統｜C# · .NET · WPF**

原始系統涉及券商 API、行情處理、風控與交易執行。公開版本擷取事件處理與 Paper 下單核心，提供合成行情的離線驗證；不連接真實券商。

### 03 · [Backtesting & Research](https://github.com/MurrayLu/backtesting-research)
**策略回測與市場研究系統｜C# · .NET · WPF · SQLite**

由策略歷史回測延伸出獨立研究工作台。公開版本展示交易模擬、帳務處理及資料可得時間驗證，使用合成資料重現部分流程。

## About the public code

交易與研究原始系統依賴未公開的本地資料庫、市場資料與特定執行環境；公開 Repository **不是完整原始系統**，而是保留部分來源程式的可執行精選切片（Isolated Demo）。兩個公開 WPF 視窗亦非原始桌面介面。

這些專案由我提出需求、決定方向、討論架構與規格，並審查功能和驗收結果；Codex 等 AI 工具參與架構細節及大部分程式實作。不主張程式碼全部由本人手寫。

各 Repository 均附執行方式、測試範圍、來源對照與已知限制。公開供閱讀及技術審查，未另行授予開源授權。
