---
lab:
  title: 實驗室 6：建立生產訂單
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 222c557f935bc0dcfaa4f2e96049774f141ea028
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909448"
---
## <a name="lab-6---create-a-production-order"></a>實驗室 6 – 建立一個生產訂單

## <a name="objectives"></a>目標

生產訂單包含關於即將生產的產品、生產數量和計劃完成日期的資訊。 它還包含有關消耗哪些材料以及生產該項目要遵循的程序資訊。

您必須為您的公司建立一個新的生產訂單。

## <a name="lab-setup"></a>實驗設定

   - **預估時間**：5 分鐘

## <a name="instructions"></a>指示

1. 在 Finance and Operations 首頁的右上方，請確認您正在與 USMF 公司合作。

1. 如有必要，請選擇公司，然後從功能表中選取 **USMF**。

1. 在左側瀏覽窗格中，選取[模組] > [生產控制] > [生產單] > [所有生產單]。

1. 在上層功能表，請選取 **新增生產訂單**。

1. 在 **識別** 下的 **項目編號** 中，請輸入 **D0001,** ，然後選取已識別的項目。

1. 在 **生產** 下的 **交付** 方塊中，請選取從當日後一個月的日期。  
    交付日期表示生產訂單應何時結束以便按時交付。 該日期可用於排程程序。 例如，您可以從交付日期向後排程訂單。

1. 請在 [數量] 方塊中輸入 **20**。

1. 在 **位元順序標記 (BOM) / 路由** 下，BOM 編號欄位會自動顯示目前項目的任何使用中 BOM 編號，但是您可以通過從被核准的 BOM 版本清單中選取一個使用中 BOM 來變更生產訂單的 BOM。 路線號碼欄位會自動顯示目前項目的任何使用中路由編號，但您可以通過從被核准的路由版本清單中選取使用中路由來更改生產訂單的路由。

    ![畫面影像正在顯示完整的建立生產訂單窗格](./media/lp1-m4-new-production-order-pane.png)

1. 選取 [建立]。
