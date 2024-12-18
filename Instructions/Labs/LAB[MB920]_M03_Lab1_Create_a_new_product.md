---
lab:
  title: 實驗室 3.1：建立新產品
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# 學習路徑 3：學習 Microsoft Dynamics 365 Supply Chain Management 的基本概念
# 課程模組 2：描述銷售和採購程式

## 實驗室 3.1：建立新產品

在您的組織中，您計劃建立新的專案，也就是襯衫。 襯衫將有不同的顏色和大小。 在此實驗室中，您將瞭解如何建立具有多個變體的新專案，並在法律實體USMF中發行它。

## 實驗室步驟

1. 在 [Dynamics 365 供應鏈管理] 瀏覽窗格中，選取 **[模組**]，然後選取 **[產品資訊管理** > **設定** > **維度] 和 [變體群組]。** 開啟 [ **色彩群組** ] 頁面並建立新的記錄。

    - 色彩群組： **ShirtColor**

    - 描述： **襯衫色彩**

2. 在 [ **色彩群組行** FastTab] 上，輸入下列三筆記錄：

    | **色彩** | **色彩名稱** |
    |-----------|----------------|
    | 藍色      | 藍色           |
    | 白人     | 白人          |
    | 黑色     | 黑色          |


3. 儲存記錄。

4. 選取 **[產品資訊管理** > **設定** > **維度] 和 [變體群組]。** 開啟 [ **大小群組** ] 頁面，然後建立新的記錄。

    - 大小群組： **ShirtSize**

    - 描述： **襯衫大小**

5. 在 [大小] 群組行** FastTab **中，輸入下列三筆記錄

    | **大小** | **大小名稱** |
    |----------|---------------|
    | S        | Small         |
    | 月        | 中        |
    | L        | 大型         |


6. 儲存記錄

7. 在 [Dynamics 365 供應鏈管理] 瀏覽窗格中，選取 **[模組**]，然後選取 [ **產品資訊管理**]。 然後在 [ **產品]** 功能表上，選取 **[產品主圖形**]。

8. 在 [ **產品主版]** 頁面上的上方功能表中，選取 **[+ 新增**]。

9. 在 [**新產品] 頁面上的 **[產品**類型**] 字段中，確認已**選取 [專案**]。

10. 在 [**產品子類型**] 字段中，確認**已選取 [產品****主**圖形]。

11. 在 [**識別]** 索引標籤的 [產品名稱 **] 方塊中**，輸入 **SH001**。

12. 在 [ **產品名稱]** 欄位中，輸入 **[襯衫**]。

13. 在 [ **產品維度群組** ] 字段中，輸入 **ColorSize**。

14. 選取 [確定] **** 按鈕。

15. 在動作窗格中的 [**產品**] 功能表下，選取 **[設定 **] 群組底下的 **[維度**群組]。

16. 在 [ **記憶體維度群組** ] 下拉式清單中，選取 **[SiteWH**]。

17. 在 [ **追蹤維度群組** ] 下拉式清單中，選取 [ **無**]。

18. 選取 [確定] **** 按鈕。

19. 在 [色彩群組 **] 列表中選取 **[ShirtColor**]。**

20. 在 [**大小] 群組**清單中選取 **[ShirtSize**]。

21. 選取動作窗格中的 [ **產品變體]** 按鈕。

22. 在 [ **產品變體]** 頁面上，選取 **動作窗格中的 [Variant 建議]** 按鈕。

23. 選取 [Variant 建議 **] 頁面上的 **[**建議所有**] 按鈕。

24. 選取 [選取所有 **] 按鈕，**然後選取 [建立**] 按鈕，以選取**建議的變體。

Variant 將會在 [產品變體] 頁面上建立。

25. 選取動作窗格中的 [ **發行產品** ] 按鈕，以釋放法律實體中的產品。

26. 隨即開啟頁面，其中顯示第一個步驟為 [選取要發行的產品]****。

27. 選取頁面底部的 [下一步] **** 按鈕。

28. 選取您想要在法律實體中發行的變體，然後選取 [ **下一步]** 按鈕。

29. 在 [ **選取要發行的公司]** 頁面上，選取 **應發行產品的USMF** 法律實體。

30. 選取頁面底部的 [下一步] **** 按鈕。

31. 在 [**確認選取範圍**] 頁面上，將失敗**時顯示 Infolog 的值**設定為 **[是**]，並將 **[以批次**執行] 設定為 **[否**]。

32. 選取頁面底部的 [完成] **** 按鈕。

33. 在右上方，切換至 **USMF** 作為法律實體。

34. 在瀏覽窗格中，選取 [模組]****，然後選取 [產品資訊管理]****。 接著，在 [產品]**** 功能表上，選取 [發行產品]****。

33. 在 [ **發行產品]** 頁面上，找出方格中的新專案 **SH001** 。

34. 選取產品鏈接，然後流覽至 [ **已發行的產品詳細數據** ] 頁面。

35. 在 [ **一般** FastTab] 上，輸入下列專案：

    - 專案模型群組： **FIFO**

36. 在 **[購買** FastTab] 上，輸入下列專案：

    - 單位： **ea**

    - 項目銷售稅群組： **ALL**

    - 價格： **30**

37. 在 [ **銷售** FastTab] 上，輸入下列內容：

    - 單位： **ea**

    - 項目銷售稅群組： **ALL**

    - 價格： **35**

38. 在 [ **管理清查** FastTab] 上，輸入下列專案：

    - 單位： **ea**

39. 在 **[工程師** FastTab] 上，輸入下列專案：

    - BOM 單位： **ea**

40. 在 [ **管理成本** FastTab] 上，輸入下列專案：

    - 專案群組： **音訊**

41. 若要完成設定，請在動作窗格中選取 **[產品** ]。 選取 [維護] 群組底下的 **[**驗證**]** 按鈕。

42. 關閉所有頁面並返回 **首頁** 。

 
