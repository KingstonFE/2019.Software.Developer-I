# 2019.IND4 Software.Developer-I
請依照下面虛擬情境的需求以及要求之技術，完成該情境需求的系統

**因應產線自動化及雲端化需求，需要做到即時監控機台所有資訊，必須即時取的機台資訊，並將資訊送到前端WEB呈現，讓使用者可以了解目前現場設備的狀況，如果有發生機台異常，畫面也必須即時跳出訊息，讓使用者確認。**

##### 原始需求
1.  畫面的顯示資訊必須達到每秒更新
  - 顯示資訊最少需要包含: 設備狀態、設備異常資訊和通知、機台內目前WIP數和當日累積WIP量和每分鐘稼動率
2.  建立一個Console模擬蒐集機台資料的程式
3.  WEB請用SPA架構設計，最少要做到Web <--> API <--> DB 架構

# Skill Requirement
> 環境
- 請將開發之系統，佈署至Micrsoft Azure (可免費使用30天)
- 請將程式碼透過Azure DevOps Service進行版控 (可免費使用)，請將專案設定公開
> 技術
- Web : 請使用ASP.Net Core 3.0 專案開發
- 前端框架: 請使用Vue.js 開發
- Web API : 請使用.Net Core 3.0開發
- DataBase : MS SQL
請用signalr技術完成即時通訊的需求，所有開發都必須有版控機制

# Acceptance Criteria
> 時間
- 依照HR指定時間完成，並再跟HR約第二次面談時間

> 成果展示
- 於第二次面試時間的前一週，分享自己在Azure DevOps Service的`Repository`給面試者

> 第二次面試時，請現場Demo作品及說明系統架構
- Demo時，請直接使用Azure Web Site成品展示
- 當天顯示Azure DevOps Service版控歷史紀錄

> 請依照`Description`，發揮創意、設計解決方案

> 第二次面試時，請你所認知的`DevOps`如何在團隊運行
