---
title: إرشادات لإخفاء/إلغاء إخفاء المجموعة من قائمة العناوين
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 02368d6a06df90d76ee1bd5448819e7ffe12c18c
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 06/05/2020
ms.locfileid: "44579996"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a><span data-ttu-id="68892-102">إخفاء مجموعة Microsoft 365 من قائمة العناوين (GAL)</span><span class="sxs-lookup"><span data-stu-id="68892-102">Hide Microsoft 365 group from address list (GAL)</span></span>

<span data-ttu-id="68892-103">لإخفاء مجموعة Microsoft 365 من قوائم العناوين (GAL) لعملاء Exchange (مثل Outlook أو OWA)، استخدم الأمر التالي في EXO shell:</span><span class="sxs-lookup"><span data-stu-id="68892-103">To hide a Microsoft 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="68892-104">لإخفاء مجموعة Microsoft 365 من أن تكون مرئية لعملاء Exchange، استخدم الأمر التالي في EXO shell:</span><span class="sxs-lookup"><span data-stu-id="68892-104">To hide the Microsoft 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

