---
lab:
  title: 實驗室 3：建立盤點日誌
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e61646d33f284bb7e30b6f63a7db4778f58b47c
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116263"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>模組 3：學習 Microsoft Dynamics 365 Supply Chain Management 的基礎知識

## <a name="lab-3---create-a-counting-journal"></a>實驗室 3 – 建立盤點日誌

1. 在 Finance and Operations 首頁的右上方，請確認您正在與 **USMF** 公司合作。 如有必要，請選取公司，然後從下拉式清單中選取 **USMF**。

2. 在左側的瀏覽窗格中，選取 [模組] > [庫存管理] > [日誌項目] >  **[項目計數]**  > [計數]。

3. 選取動作窗格中的 [+新增] 按鈕。 底部將會出現 [Create inventory journal] \(建立庫存日誌\) 對話方塊表單與 [確定] 按鈕。 選取 [確定] 按鈕。

4. 庫存盤點日誌表單將會與標題與詳細資訊一同出現

![庫存盤點日誌表單的螢幕擷取畫面，其中已填入標題與詳細資訊。](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. 在動作窗格中，選取 [建立明細 -&gt; 線上]。

6. 在 [Create on-hand counting journal] \(建立現有盤點日誌\) 對話方塊窗格中，將 [Warehouse] \(倉庫\)、[Inventory Status] \(庫存狀態\)、[Location] \(位置\) 及 [License Plate] \(牌照\) 欄位設定為 [是]。 

![[Create on-hand counting journal] \(建立現有盤點日誌\) 對話方塊窗格的螢幕擷取畫面，其中欄位已如敘述設定。](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. 展開 [Record to include] \(要包含的記錄\) 區段，並選取 **篩選** 連結。 在 [項目編號] 欄位中，選取 **A0001**，然後選取 [確定]。

8. 在 [Create on-hand counting journal] \(建立現有盤點日誌\) 對話方塊表單的底部選取 [確定]。

項目 A0001 的庫存數量會出現在 [日誌明細] 區段中，其細分為站點、倉庫、位置和牌照。

9. 在 [日誌明細] 區段的 [Counted] \(已計數\) 資料行中，輸入在每個站點/倉庫/位置/牌照內計數的數字。 請注意：

    - 如果 **On-hand (現有)** 數量與 **Counted (已計數)** 數量相等，則 [數量] 欄位將為空白。

    - 如果 [Counted] \(已計數\) 欄位的值大於 [On-hand] \(現有\) 欄位的值，則 [數量] 欄位會包含正值。

    - 如果 [Counted] \(已計數\) 欄位的值小於 [On-hand] \(現有\) 欄位的值，則 [數量] 欄位會包含負值。

10. 選取動作窗格中的 [驗證] 按鈕，然後選取 [Post] \(過帳\) 按鈕。

11. 關閉頁面並返回首頁。
