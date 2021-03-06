---
title: البحث عن الأحداث التي تم تنفيذها على قواعد علبة الوارد
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: deb83d278a2b398b4ea6fc31b043c33309b736e3
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 03/05/2021
ms.locfileid: "50480927"
---
# <a name="find-events-performed-on-inbox-rules"></a>البحث عن الأحداث التي تم تنفيذها على قواعد علبة الوارد

عند إنشاء قواعد علبة الوارد أو تغييرها أو حذفها، يتم تسجيل الأحداث في سجل التدقيق. فيما يلي كيفية مراجعتها:

1. انتقل إلى مركز التوافق في [Office 365 &.](https://go.microsoft.com/fwlink/p/?linkid=2077143)
1. حدد البحث > البحث في سجل التدقيق.

    > [!NOTE]
    > إذا رأيت إشعارا بأنه يجب تشغيل التدقيق، فمضي قدما وقلبه الآن. إذا لم يتم تشغيل هذه الميزة، فلن تتمكن نتائج البحث من سحب البيانات من التواريخ السابقة.
1. حدد حقل "الأنشطة" واعثر على أنشطة علبة بريد Exchange، ثم حدد New-InboxRule قاعدة "إنشاء علبة الوارد" من Outlook Web App. عندما تنتهي، انقر خارج الجزء لتصغير جزء "الأنشطة".
1. حدد نطاق التاريخ، ثم في حقل "المستخدمون"، حدد اسم المستخدم للمستخدم الذي تريد التحقق منه. يمكنك تحديد أكثر من مستخدم واحد في كل مرة.
1. حدد "بحث". تظهر الأنشطة ضمن "النتائج".
1. لعرض التفاصيل، حدد نشاطا، ثم حدد "مزيد من المعلومات". ضمن القسم "معلمات"، يمكنك رؤية اسم القاعدة، مجموعة الشروط، والإجراءات التي ستتخذها القاعدة.

لمعرفة المزيد، راجع "البحث في سجل تدقيق Office 365" للتعرف على السيناريوهات الشائعة وإصلاحها.