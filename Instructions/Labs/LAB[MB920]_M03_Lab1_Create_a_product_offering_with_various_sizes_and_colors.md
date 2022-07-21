---
lab:
  title: 實驗室 1:建立提供不同尺寸和色彩的產品
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e32371aea8a73c04c6aee60953ff9c344b3a533
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116259"
---
# <a name="module-1-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>單元 1：學習 Microsoft Dynamics 365 Supply Chain Management 的基礎知識

## <a name="lab-1---create-a-new-product"></a>實驗室 1 – 建立新產品

## <a name="objectives"></a>目標

在 Contoso Entertainment System USA (USMF) 中，您需要為要從供應商處購買的新設定機櫃建立一個新項目。

## <a name="lab-setup"></a>實驗設定

   - **預估時間**：10 分鐘

## <a name="instructions"></a>指示

1. 在 Finance and Operations 首頁的右上方，請確認您正在與 USMF 公司合作。

1. 如有必要，請選擇公司，然後從功能表中選取 **USMF**。

1. 在左上方，請選取[**展開瀏覽窗格**] 漢堡功能表。

1. 在瀏覽窗格中，選取 [課程模組]  >  [產品資訊管理]，然後選取 [產品] 類別下的 [已發行的產品]。

1. 在 [已發行的產品詳細資料]頁面中，從最上方的功能表選取 [+新增]。

1. 在 [新發行的產品] 窗格中，於 [產品類型] 功能表中，確認已選取 [項目]。

1. 在 [產品子類型] 功能表中，確認已選取 [產品]。

1. 選取 [追蹤維度群組] 功能表，然後選取 [無]。

1. 在 [識別] 下的 [產品編號] 和 [項目編號] 方塊中，輸入 **GTL007**。

1. 在 [產品名稱] 方塊中，輸入 **Cabinet 2**。

1. 在 [參考群組] 下，選取 [項目模型群組] 功能表，然後選取 [FIFO 先進先出]。

1. 選取 [項目群組] 功能表，然後選取 [電視和視訊]。

1. 選取 [儲存體維度群組] 功能表，然後選取 **SiteWH**。

1. 在 [**量值單位**] 下，請驗證是否設定了以下值：

    | **設定**| **值**|
    | :--- | :--- |
    | 庫存單位| 每個|
    | 購買單位| 每個|
    | 銷售單位| 每個|
    | 位元順序標記 (BOM) 單位| 每個|

1. 在 [銷售稅賦] 下，選取 [項目銷售稅群組] 功能表，然後選取 [全部]。

1. 在 [購買稅賦] 下，選取 [項目銷售稅群組] 功能表，然後選取 [全部]。

1. 在價格下的 [購買價格] 方塊中，輸入 30.00。

1. 在 [銷售價格] 方塊中，輸入 30.00。

1. 您的新發行產品應如下所示：

    ![畫面影像正在顯示已完成的新發行產品表格](./media/lp1-m2-new-release-product.png)

1. 選取 [確定]。

1. 為確保產品最終確定，請在功能區列中的 [**維護**] 下，選取 [**驗證**]。

    ![畫面影像正在顯示功能區列的醒目提示驗證](./media/lp1-m2-validate-ribbon-bar.png)

1. 驗證您是否看到資訊橫幅，確認所有必要的欄位值都已驗證。

    ![已驗證所有必要欄位的資訊通知畫面影像](./media/lp1-m2-confirmation-of-validation.png)

1. 請關閉所有頁面並返回首頁。
