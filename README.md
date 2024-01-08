# 2022.SDK.Developer : WebAPI 取存 實作考題

請依照下面虛擬情境的需求以及要求之技術，完成該情境需求的系統

** 今天我們需要提供一個資料平台給用戶端的系統呼叫，終端有 Application 可以讀取 CSV 內的資料，將其資料儲存到資料庫，每次讀取 CSV File 時候，要將資料庫內的原資料刪除。除了將資料寫入資料庫外，也有系統讓資料可以讀出 **

##### 原始需求
1. 建立一個 Console Application 將 CSV 內容讀出儲存到資料表
2. Console Application 必須透過 Web API 將資料儲存
3. Console Application 必須透過 Web API 將資料取出

# Skill Requirement
> 環境
- 請將開發之系統，佈署至 Micrsoft Azure (可免費使用30天)，可以用 Azure 免費的 Azure SQL DB
- 請將程式碼透過 Azure DevOps Service 進行版控 (可免費使用)，請將專案設定公開
> 技術
- Console : 請使用 Net6 開發
- WebAPI : 請使用 Net6 開發
- DataBase : 請使用 MS SQL 開發 SQL 程式，一律採用 Store procedure 開發

# Acceptance Criteria
> 時間
- 請先預估完成時間, 並在完成後回報面試主管, 約二次面談時間。

> 成果展示
- 分享自己在 Azure DevOps Service的`Repository`給主考官，Repository 須設定為公開

> 第二次面試時，請現場Demo作品及說明系統架構
- Demo 時，能使用 Postman 呼叫 API 存入與取出資料進行展示


