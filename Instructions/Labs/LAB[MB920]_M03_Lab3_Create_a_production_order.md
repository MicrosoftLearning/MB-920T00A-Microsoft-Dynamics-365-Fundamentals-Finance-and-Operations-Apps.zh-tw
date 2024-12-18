---
lab:
  title: 實驗室 3.2：建立生產訂單
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# 學習路徑 3：學習 Microsoft Dynamics 365 Supply Chain Management 的基本概念
# 課程模組 4：描述製造程式

## 實驗室 3.2：建立生產訂單

## 目標

生產訂單可在 Supply Chain Management 中起始生產流程。 在本實驗室中，您會熟悉生產訂單表單的使用者介面和功能。 此外，您將瞭解如何在練習結束時建立及處理生產訂單。

## 實驗室步驟

1. 在 Dynamics 365 **供應鏈管理首頁**的右上方，確認您正在與 USMF** 公司合作**。

2. 如有必要，請選擇公司，然後從功能表中選取 [USMF]****。

3. 在左側瀏覽窗格中，選取[模組]**** > [生產控制]**** > [生產單]**** > [所有生產單]****。

4. 在頂端功能表上，選取 **[新增生產訂單** ]，然後輸入下列數據。

    - 項目編號： **D0002**

    - 數量： **10**

    - 網站： **1**

    - 倉儲： **11**

    - 傳遞：[從今天的日期選取一個月的日期]

    - BOM 編號： **D0002BOM**

    - 路線號碼： **000004**

5. 選取**建立**按鈕。

系統會針對專案 D0002 的 10 個數量建立新的生產訂單。

6. 選取 **[生產訂單] [動作窗格] [ &gt; 程序 &gt; 估計]。**

7. 在 [估計 **] 對話框中，選取 **[** 收益設定 **] 欄位中的 [標準****]，選取 **[參考] 字段**，然後選取 [**確定]** 按鈕。

生產**訂單的狀態**將會變更為 **[估計]。**

8. 選取 **[排程] （動作窗格功能表） &gt; 生產訂單 &gt; 排程作業。**

9. 在 [**作業排程] 對話框中，選取 **[排程**方向 **]** **字段中的 [今天轉寄]，然後選取 [**確定]** 按鈕。

10. 選取 **[檢視] [動作窗格] 功能表）&gt;[容量保留**] &gt; 相關信息。

11. 確認在 [容量保留 **] 頁面上建立**的新記錄。

12. 流覽回 [ **所有生產訂單** ] 頁面。 請注意，**** 生產訂單的狀態會變更為**已排程**。

13. 選取 **[生產訂單] [動作窗格] [ &gt; 流程 &gt; 發行**]。

14. 在 [ **發行** ] 對話框中，選取 [ **參考] 字段** ，然後選取 [ **確定]** 按鈕。

15. 生產 **訂單的狀態** 將會變更為 [ **已發行**]。

16. 選取 **[生產訂單] [動作窗格] [ &gt; 程序 &gt; 開始**]。

17. 在 [ **開始]** 對話框中，選取 [ **一般]** 索引標籤。

18. 在 [ **一般]** 索引標籤上，輸入下列內容。

    - 日期： **今天的日期**

    - 數量： **10**

    - 開始生產： **是**

    - 現在寄出路由卡： **否**

    - 立即挑選清單： **否**

19. 選取 [確定] **** 按鈕。

生產**訂單的狀態會變更為 **[已啟動**]。**

20. 選取 **[檢視] [動作窗格] &gt; [日誌 &gt; 選擇] 清單**。

新的挑選清單日誌會以三行建立。

21. 張貼挑選清單日誌。

如有需要，請在 [張貼日誌] 視窗中選取 [ **確定**  ]。

22. 流覽回 [ **所有生產訂單** ] 頁面，然後選取 **[檢視][動作窗格] 功能表） &gt; [ &gt; 日誌路由] 卡片**。

新的路由卡日誌會以三行建立。

23. 選取這三行中的 [ **作業已完成** ] 字段，並張貼路由卡日誌。

24. 巡覽回 [**所有生產訂單] 頁面，然後選取 **[生產訂單**][動作窗格] 功能表）&gt;[處理&gt;報表] 完成**。

25. 在 [**報表為已完成]** 對話框中，於 **[良好數量**] 字段中輸入 **10**。 選取 [ **結束作業]** 字段，然後選取 [ **確定**]。

生產 **訂單的狀態** 會變更為 **[已結束**]。 專案 D0002** 的**庫存在工地 1 和倉庫 11 中增加了 10 個。

26. 選取 **[管理成本][動作窗格] 功能表） &gt; [計算] &gt; [檢視計算詳細數據**]。

記下 [概觀成本] 索引卷標上 **製造項目的最終成本** 。

 
