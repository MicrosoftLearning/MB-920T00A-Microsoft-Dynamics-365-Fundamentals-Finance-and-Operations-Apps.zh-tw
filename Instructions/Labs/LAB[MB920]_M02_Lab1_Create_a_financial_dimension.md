---
lab:
    title: '實驗室 1：建立財務維度'
    module: '模組 2：學習 Microsoft Dynamics 365 Finance 的基礎知識'
---

## 實驗室 1: 建立財務維度

## 目標

使用財務維度頁面來建立財務維度，其可以用作會計區段的財務圖表。財務維度有兩種類型:自定義維度和實體支持維度。自訂維度在法律實體之間共用，而該值由使用者來輸入和維護。對於實體支援的維度，其值會在系統中的其他地方被定義，例如在客戶或商店實體中。有些實體支援的維度可在法律實體之間共用，而其他實體支援的維度是特定於公司的。

必須建立由貴公司使用的自訂財務維度。

## 實驗室設定

   - **估計時間**：5 分鐘

## 說明

1. 在 Finance and Operations 首頁的右上方，請確認您正在與 USMF 公司合作。

1. 如有必要，請選擇公司，然後從功能表中選取 **USMF**。

1. 在左側瀏覽窗格中，請選取**模組** > **一般底帳** > **會計圖表** > **維度** > **財務維度**。

1. 在上層功能表，請選取 **+新增**。

1. 在財務維度頁面上，請選取**使用值來源**的功能表，然後選取 **<自訂維度>**。

1. 在**維度**名稱方塊中，輸入 **Affliate_營收**。

1. 在**報表欄位名稱**方塊中，輸入 **Afflt**。

1. 請在上層功能表選擇**啟用**。

    ![螢幕擷取畫面正在顯示新的自訂財務維度，並醒目提示了「使用值來源」、「維度名稱」、「報表欄位名稱」和「啟用」功能表](./media/lp2-m3-new-financial-dimension.png)

1. 請檢閱對話方塊中的資訊，然後選取**關閉**。

1. 請檢閱警示通知橫幅。

    ![螢幕擷取畫面正在顯示警告資訊橫幅，其參考啟用一個新維度的維護模式要求。](./media/lp2-m3-activation-warning-banner.png)

    >[!注意] 可以通過沙箱和生產環境中的生命週期服務 (LCS) 直接開啟和關閉維護模式。有關管理生命週期服務的更多資訊，請參閱 [https://docs.microsoft.com/zh-tw/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure](https://docs.microsoft.com/zh-tw/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure)。
