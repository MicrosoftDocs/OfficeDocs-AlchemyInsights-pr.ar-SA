---
title: رمز الطاقة أو البطارية مفقود في Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002953"
- "5655"
ms.openlocfilehash: d82994c86126ea9c789e846a74e03794c32c5c3c
ms.sourcegitcommit: b398afd92d4259f893c25b48aec65921e6cc68d6
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 05/16/2020
ms.locfileid: "44268818"
---
# <a name="power-or-battery-icon-missing-in-windows-10"></a><span data-ttu-id="cab2b-102">رمز الطاقة أو البطارية مفقود في Windows 10</span><span class="sxs-lookup"><span data-stu-id="cab2b-102">Power or battery icon missing in Windows 10</span></span>

<span data-ttu-id="cab2b-103">إذا كان جهاز Windows 10 يحتوي على بطارية (على سبيل المثال، كمبيوتر محمول أو جهاز لوحي، أو جهاز كمبيوتر متصل عبر USB إلى UPS)، عادةً ما يتم عرض رمز طاقة/بطارية في شريط المهام بالقرب من الساعة، على سبيل المثال:</span><span class="sxs-lookup"><span data-stu-id="cab2b-103">If your Windows 10 device has a battery (e.g., laptop or tablet, or a PC connected via USB to a UPS), normally a power/battery icon is shown in the taskbar near the clock, for example:</span></span>

![رمز البطارية](media/battery-icon.png)

<span data-ttu-id="cab2b-105">إذا كنت لا ترى هذا الرمز، فقد يكون مخفيًا:</span><span class="sxs-lookup"><span data-stu-id="cab2b-105">If you don't see this icon, it may be hidden:</span></span>

1. <span data-ttu-id="cab2b-106">انتقل إلى **[الإعدادات > التخصيص > شريط المهام](ms-settings:taskbar?activationSource=GetHelp)**.</span><span class="sxs-lookup"><span data-stu-id="cab2b-106">Go to **[Settings > Personalization > Taskbar](ms-settings:taskbar?activationSource=GetHelp)**.</span></span>

2. <span data-ttu-id="cab2b-107">في منطقة الإعلام، انقر فوق **تحديد الرموز التي تظهر على شريط المهام**.</span><span class="sxs-lookup"><span data-stu-id="cab2b-107">In the Notification area, click **Select which icons appear on the taskbar**.</span></span>

3. <span data-ttu-id="cab2b-108">ثم ابحث عن عنصر **الطاقة** في القائمة وتبديل الإعداد إلى **تشغيل**.</span><span class="sxs-lookup"><span data-stu-id="cab2b-108">Then find the **Power** item in the list and toggle its setting to **On**.</span></span>

    ![إظهار رمز الطاقة في شريط المهام](media/power-icon-on.png)

<span data-ttu-id="cab2b-110">**استكشاف الأخطاء وإصلاحها**</span><span class="sxs-lookup"><span data-stu-id="cab2b-110">**Troubleshooting**</span></span>

<span data-ttu-id="cab2b-111">إذا اتبعت الإرشادات المذكورة أعلاه وكان تبديل **الطاقة** رماديًا أو غير مرئي، في مربع البحث على شريط المهام، اكتب **مدير الجهاز،** ثم حدد **إدارة الأجهزة** في قائمة النتائج.</span><span class="sxs-lookup"><span data-stu-id="cab2b-111">If you followed the above instructions and the **Power** toggle is greyed out or not visible, in the search box on the taskbar, type **device manager**, and then select **Device Manager** in the list of results.</span></span> <span data-ttu-id="cab2b-112">ضمن **البطاريات،** انقر بزر الماوس الأيمن على البطارية لجهازك، انقر فوق **تعطيل،** وانقر فوق **نعم**.</span><span class="sxs-lookup"><span data-stu-id="cab2b-112">Under **Batteries**, right-click the battery for your device, click **Disable**, and click **Yes**.</span></span> <span data-ttu-id="cab2b-113">انتظر بضع ثوان، ثم انقر فوق البطارية باليمين وانقر فوق **تمكين**.</span><span class="sxs-lookup"><span data-stu-id="cab2b-113">Wait a few seconds, and then right-click the battery and click **Enable**.</span></span> <span data-ttu-id="cab2b-114">ثم أعد تشغيل جهازك.</span><span class="sxs-lookup"><span data-stu-id="cab2b-114">Then restart your device.</span></span>

<span data-ttu-id="cab2b-115">إذا اتبعت الإرشادات المذكورة أعلاه، ولكن رمز البطارية لا يظهر على شريط المهام، في مربع البحث على شريط المهام، اكتب **مدير المهام،** ثم انقر فوق **إدارة المهام** في قائمة النتائج.</span><span class="sxs-lookup"><span data-stu-id="cab2b-115">If you followed the above instructions, but the battery icon does not appear on the taskbar, in the search box on the taskbar, type **task manager**, and then click **Task Manager** in the list of results.</span></span> <span data-ttu-id="cab2b-116">في علامة التبويب **العمليات،** تحت **الاسم،** انقر بزر الماوس الأيمن **على Explorer،** ثم انقر فوق **إعادة تشغيل**.</span><span class="sxs-lookup"><span data-stu-id="cab2b-116">On the **Processes** tab, under **Name**, right-click **Explorer**, and then click **Restart**.</span></span>