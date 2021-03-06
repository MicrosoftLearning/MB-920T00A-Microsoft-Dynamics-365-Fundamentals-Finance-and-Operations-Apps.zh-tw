---
lab:
    title: '實驗室 8：Dynamics 365 Supply Chain Management 頂點實驗室'
    module: '模組 1：學習 Microsoft Dynamics 365 Supply Chain Management 的基礎知識'
---

## 實驗室 8: Dynamics 365 Supply Chain Management 頂點實驗室

## 目標

在這個實驗室中，您將了解產品建立和定價維護。還將檢閱供應鏈的核心商務程序，例如庫存管理、採購和取得。

## 實驗室設定

- **估計時間**：45 分鐘 

## 練習 1：查詢產品管理

### 建立一個產品

在 Contoso Entertainment System USA (USMF) 中，需要為要從供應商處購買的新設定喇叭機箱建立一個新項目。

1. 在首頁的右上方，請驗證已選取 **USMF** 公司。

1. 如果不是，請選取目前已列出的公司，然後變更公司為 **USMF**。

1. 使用瀏覽窗格，請選取**模組** > **產品資訊管理** > **產品** > **發行產品**。

1. 在已發行產品詳細資料頁面的動作窗格，請選取 **+新增**。

1. 在**新發行**的產品窗格中，請在**產品類型**功能表中，驗證已選擇的**項目**。

1. 在**產品子類型**功能表中，請驗證已選取的**產品**。

1. 請選取**追蹤維度群組**功能表，然後選取**無**。

1. 在**識別**下的**產品編號**中，請輸入 **GTL201**。

1. 在**產品名稱**方塊中，請輸入**喇叭機箱**。

1. 在**銷售徵稅**下，請選擇**項目銷售稅金群組**功能表，然後選擇**全部**。

1. 在**購買徵稅**下，請選擇**項目銷售稅金群組**功能表，然後選擇**全部​​**。

1. 在**價格**下的**購買價格**方塊中，請輸入 **30.00**。

1. 在**銷售價格**方塊中，請輸入 **30.00**。

1. 在**參考群組**下，請選擇**模型群組**功能表，然後選取**先進先出(FIFO)**。

1. 請選取**項目組合**功能表，然後選取**汽車音訊**。

1. 請選取**儲存維度群組**功能表，然後選取 **SiteWH**。

1. 在**量值單位**下，請驗證是否設定了以下值：

    | **設定**| **值**|
    | :--- | :--- |
    | 庫存單位| 每個|
    | 購買單位| 每個|
    | 銷售單位| 每個|
    | 位元順序標記 (BOM) 單位| 每個|

1. 請選擇**確定**。

1. 為確保產品完成，在動作窗格中，請選取**產品**，然後在**維護**下選擇**驗證**。

1. 驗證您是否看到資訊橫幅，確認所有必要的欄位值都已驗證。

1. 請關閉所有頁面並返回首頁。

## 練習 2：了解倉庫管理

### 建立倉庫

1. 使用瀏覽窗格，請選取**模組** > **庫存管理** > **設定** > **庫存分解** > **倉庫**。

1. 在倉庫頁面上的動作窗格中，請選取 **+新增**。

1. 在**倉庫**方塊中，請輸入 **150**。

1. 在**名稱**方塊中，請輸入 **Outpost 倉庫**。

1. 請選取**站台**功能表，然後選取 **1 家用喇叭生產**。

1. 請選取**位置名稱**快速索引標籤。

1. 這個區段中的選項定義了位置名稱的預設格式。

1. 請將**包括通道**和**包括機架**選項設定為**是**。

1. 請將**包括貨架**選項設定為**是**。

1. 在**格式**方塊中，對於貨架，請輸入 **-##**。

1. 在動作窗格中，請選擇**倉庫**。

1. 在**維護**下，請選擇**位置精靈**。

1. 請在歡迎頁面上檢閱該資訊，然後在右下角選取**下一步**。

1. 請清除**輸入碼頭**和**大量位置**核選方塊。

1. 請選取**下一步**並檢閱該資訊。

1. 請繼續閱讀每一頁，然後在完成後選取**完成**。

1. 請關閉頁面並返回首頁。

### 為銷售價格建立的貿易合約

1. 使用瀏覽窗格，請選取**模組** > **產品資訊管理** > **產品** > **發行產品**。

1. 在已發行產品詳細資料頁面上，請搜尋產品編號 **GTL201**。

1. 在 **GTL201** 的左側，請選取**選取或取消選取列**核選方塊。

1. 在動作窗格中，請選擇**銷售**，然後在**貿易協定**下，選擇**建立貿易協定**。

1. 在動作窗格中，請選取 **+新增**。

1. 請選取**名稱**欄位並選擇功能表，然後選取**S_價格**。

1. 在動作窗格中，請選取**明細**。

1. 在帳目明細，貿易合約頁面上的**項目關係**欄位中，請選擇功能表，然後選取**GTL201**。

1. 這是您建立的產品的項目編號。

1. 在**倉庫**欄位中，請選擇功能表，然後選取**150**。

1. 可能需要向右捲動才能看到該欄位。

1. 在**貨幣金額**欄位的方塊中，請輸入**100.00**。

1. 在詳細資料區段的**開始日期**方塊中，請輸入目前年份的第一個日期。

1. 在動作窗格中，請選擇**驗證** > **驗證所有明細**。

1. 在**價格/折扣日誌過帳**窗格中，請選擇**確定**。

1. 請驗證無錯誤。

1. 在動作窗格中，請選**公佈**。

1. 在**價格/折扣日誌過帳**窗格中，請選取**確定**。

1. 驗證操作已完成。

1. 請關閉頁面。

1. 在已發行的產品詳細資料頁面的動作窗格**銷售** > **貿易協定**下，請選取**檢視貿易協定**。

1. 貿易合約應已張貼。檢閱該列以觀察價格資訊。

1. 請關閉該頁面並返回首頁。

## 練習 3：查詢生產管理

### 請為產品建立生產訂單

1. 使用瀏覽窗格，請選取**模組** > **生產控制** > **生產訂單** > **所有生產訂單**。

1. 在動作窗格中，請選取**新增生產訂單**。

1. 在**建立生產訂單**窗格的**識別**下之**項目**中，請輸入**D0004,** 然後選擇已識別的項目。

1. 在**生產**下的**交付**方塊中，請選取從當日後一個月的日期。

1. 交付日期表示生產訂單應何時結束以便按時交付。該日期可用於排程程序。例如，您可以從交付日期向後排程訂單。

1. 請在**數量**方塊中輸入**30**。

1. 選取**建立**。

1. 請關閉所有頁面並返回首頁。

## 練習 4：了解庫存管理

### 請使用已建立倉庫的產品建立計數日誌

1. 使用瀏覽窗格，請選取**模組** > **庫存管理** > **日誌項目** > **項目計數 > 計數**。

1. 在動作窗格中，請選取 **+新增**。

1. 在**建立庫存日誌**窗格下的**以計數**窗格中，請選取**倉庫**切換開關將其設定為**是**。

1. 請選取**確定**。

1. 請在庫存計數日誌頁面上的**日誌標題詳細資料**快速索引標籤中，工具列上的**帳目明細**下，選取 **+新增**。

1. 在**項目編號**欄位中，請選取功能表然後選取**GTL201**。

1. 在**倉庫**欄位中，請選取功能表，然後選取**150**。

1. 在**已計數**方塊中，請輸入**100.00**。

1. 這將指定此產品在儲存在倉庫中的項目數量。

1. 在動作窗格中，請選取**驗證**。

1. 在**檢查日誌**窗格中，請選取**確定**。

1. 在動作窗格中，請選取**張貼**。

1. 在**張貼日誌**窗格中，請選取**確定**。

1. 請關閉所有頁面並返回首頁。

### 請檢查產品的現有庫存

1. 使用瀏覽窗格，請選取**模組** > **庫存管理** > **查詢和報表** > **現有清單**。

1. 在動作窗格中，請選取**維度**。

1. 在**維度顯示**窗格的**儲存維度**下，請選取**站台**和**倉庫**核選方塊，然後選擇**確定**。

1. 在**篩選**動作窗格中，請選取**套用**。

1. 請找到並檢閱 **GTL201** 的現有庫存。

1. 請關閉所有頁面並返回首頁。

## 練習 5：查詢採購和外包

### 建立包含產品的採購單

1. 使用瀏覽窗格，請選取**模組** > **採購和取得** > **採購單** > **所有採購單**。

1. 在所有採購單頁面上的動作窗格，請選取 **+新增**。

1. 在**建立採購單**窗格中，請選取**供應商帳戶**功能表，然後選取**US-101**。

1. 當您選擇供應商時，供應商記錄中的詳細資料 (例如地址，發票帳戶，交付條款和交付方式) 將作為預設值複製到訂單標題中。可以隨時變更這些值。

1. 在**一般**區段的**儲存維度**下，請選取**站台**功能表，然後選取 **1 家用喇叭生產**。

1. 在**日期**下，請選取從今天開始一周的**交付日期**。

1. 請選取**管理**。

1. 請選取**下單者**，然後選取 **Lars Giusti** 以指定下訂單的人。

1. 在**建立採購單**窗格中，請選取**確定**。

1. 在工具列上，請選取**採購單列**。

1. 在**顯示**下，請選取**維度**。

1. 在**維度顯示**窗格中的**產品維度**下，請選取**顏色**核取方塊。

1. 請選取**確定**。

1. 在**項目編號**欄位中，請選取功能表然後選擇 **T0005**。

1. 在**變體編號**欄位中選取功能表，然後選取一種顏色。

1. 請在**數量**方塊中輸入 **15**。

1. 在**採購單明細**下，請選取頁面底部的**明細詳細資料**快速索引標籤。

1. 此索引標籤可能已被展開。

1. 請選取**交付**索引標籤，然後在**交付日期**方塊中，使用目前指派的日期或輸入未來的日期。  
    可以為每個訂單明細指派唯一交貨日期。日期是已從採購單標題上的欄位繼承的，但可以變更它。

1. 請記下您的採購單編號。稍後將會需要。

1. 在動作窗格中，請選取**儲存**。

1. 請關閉採購單明細頁面。

1. 在所有採購單頁面上，請使用**篩選**功能來找到您的新採購單。

1. 完成後，請關閉所有採購單頁面並返回首頁。
