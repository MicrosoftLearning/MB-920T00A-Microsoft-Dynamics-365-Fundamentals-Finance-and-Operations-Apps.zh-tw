---
lab:
  title: 實驗室 2：Excel 整合
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# 單元 1：探索 Dynamics 365 財務和營運應用程式的核心功能

## 實驗室 2：Excel 整合

## 目標

在此實驗室中，您將瞭解如何使用 Dynamics Data Connector office 增益集應用程式，將資料從財務和作業複製到 Excel。 您也將瞭解如何使用相同的應用程式將資料插入Dynamics 365 Finance和作業。 

## 實驗設定

   - **預估時間**：5 分鐘

## 指示

現在您已經熟悉了財務與營運應用程式，請花一些時間來探索 Excel 整合案例。 

1.  在 **[財務與營運] 首頁** 的右上方，確認您是使用 **USMF** 公司。 

2.  巡覽至 [採購和尋找貨源] > [設定] > [廠商] > [廠商群組]。

3.  在動作窗格中，選取 [ **在 Microsoft Office 中開啟** ]，然後在 [在 **Excel 中開啟**] 底下，選取 **[廠商群組 (usmf) **]。

4.  在 [ **在 Excel 中開啟]** 窗格中，選取 [ **下載**]。 

5.  Excel 範本檔案將會下載並儲存。 **開啟** 下載的 Excel 範本檔案、視需要略過或允許其他標準安全性提示、關閉啟用，然後選取 [ **啟用編輯**]。 如果系統詢問) ，請選取 **[信任此載入**宏]，然後使用您的相同認證登入 (。 

    登入之後，Data Connector 應用程式會重新整理 **廠商群組** 資料表中的現有資料，並在 Excel 試算表中顯示。 

6.  若要建立新記錄，請在 [**廠商群組**] 欄位、[ `Insurance vendor` **描述**] 欄位和 `Net10` [**付款條款**] 欄位中輸入 `100` 。 

7.  選取 [Microsoft Dynamics Data Connector] 工作窗格中的 [ **發佈** ] 按鈕。 

8.  重新整理 Dynamics 365 Finance 和 Operations 中的**廠商群組**清單，以確認新記錄已成功新增。 

