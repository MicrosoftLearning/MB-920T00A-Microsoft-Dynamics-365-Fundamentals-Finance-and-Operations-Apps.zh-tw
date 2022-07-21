---
lab:
  title: 實驗室 2：Excel 整合
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116256"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>單元 1：探索 Dynamics 365 財務和營運應用程式的核心功能

## <a name="lab-2---excel-integration"></a>實驗室 2 – Excel 整合

現在您已經熟悉了財務與營運應用程式，請花一些時間來探索 Excel 整合案例。

### <a name="task-1-create-template"></a>工作 #1：建立範本

1. 開啟 Finance and Operations 首頁。 

2. 巡覽至 [Modules] \(模組\) > [Common] \(一般\) > [Common] \(一般\) > [Office Integration] \(Office 整合\) > [Excel 活頁簿] [設計工具]。 請注意，大部分的巡覽都會經由 [Modules] \(模組\) 完成，因此通常不會指定此項目。

3. 在篩選中搜尋 **VendorGroup**。

4. 從可用欄位的清單中，選取 [廠商群組]、[描述] 和 [付款條件]，然後藉由選取向右箭號，將這些欄位移至選取的欄位方塊。

5. 在動作窗格中，選取 [建立活頁簿] 按鈕。

6. 在右側的 [Save To] \(儲存至\) 面板中，選取 [下載] 按鈕。

7. 選取 [另存新檔] 下載檔案，將其儲存在 **Downloads** 資料夾內。

8. 巡覽至 [Common] \(一般\) > [Office Integration] \(Office 整合\) > [文件] [範本]。

9. 選取 [新增]。

10. 在右側面板的 [上傳範本] 區段中，選取 [瀏覽] 按鈕，然後選取先前下載的檔案 (如果您使用預設名稱，則名稱為 DynamicsWorkbook)。

11. 在 [範本名稱] 欄位中，輸入 **CustomVendorGroup**。

12. 選取 [確定]，然後選取 [儲存]。

### <a name="task-2-open-in-excel"></a>工作 2：在 Excel 中開啟

1. 巡覽至 [採購和尋找貨源] > [設定] > [廠商] > [廠商群組]。

2. 選取 [在 Microsoft Office 中開啟] > [在 Excel 中開啟] 以尋找您上傳的新範本 CustomVendorGroup。

3. 選取 **CustomVendorGroup** 並下載 Excel 範本。

4. 儲存並開啟下載的 Excel 範本，視需要予以允許、關閉啟用，然後選取 [啟用編輯]。 信任此增益集，然後登入 (如系統詢問，請使用相同的認證)。

[廠商群組] 資料表的所有現有資料，將會出現在 Excel 試算表中。

5. 輸入新記錄。

6. 在 [廠商群組] 欄位中輸入 **100**，在 [描述] 欄位中輸入 **Insurance Vendor**，並在 [付款方式] 欄位中輸入 **Net10**。

7. 選取 Microsoft Dynamics Office 增益集應用程式中的 [發佈] 按鈕。

8. 開啟 [廠商群組] 表單，驗證是否已新增新記錄。

