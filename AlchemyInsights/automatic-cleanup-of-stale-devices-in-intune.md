---
title: التنظيف التلقائي للأجهزة التي لا معنى لها في Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/28/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1285"
- "6700008"
ms.openlocfilehash: 874ee290c59df3b5de1421369484a1a5a0ff7be4
ms.sourcegitcommit: 0e50dfcdb3f6aa72368279e23b83efecb9dc9c3f
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 07/28/2020
ms.locfileid: "46554710"
---
# <a name="automatic-cleanup-of-stale-devices-in-intune"></a>التنظيف التلقائي للأجهزة التي لا معنى لها في Intune

Intune يسمح للمسؤول لتكوين الفاصل الزمني بين 90 و 270 يوما ، وبعد ذلك يتم إزالة الأجهزة التي لا معنى لها من الخدمة. هذا الإعداد هو المنظمة واسعة وبمجرد تفعيلها يدخل حيز التنفيذ على الفور. يتم حذف أي أجهزة لم يتم إيداعها في خادم Intune لفترة تتجاوز الإعداد بشكل دائم.

**ملاحظة** كائنات جهاز MDM هي فقط المؤهلة لإجراء التنظيف هذا. يتم استبعاد كائنات الجهاز فقط EAS.

للحصول على معلومات إضافية حول الوقت الذي يصبح فيه الجهاز مؤهلاً للحذف بناءً على إعداد تنظيف الجهاز و"حالته":

الإعداد: **حذف الأجهزة بعد تاريخ آخر تسجيل للانقـان: نعم (بعض القيمة (N) في الأيام المحددة)**

- استناداً إلى القيمة (N) التي تم تكوينها في الإعداد، تقوم خدمة Intune بحذف الجهاز في الأيام المحددة بعد أن تحقق بنجاح.

الإعداد: **حذف الأجهزة بعد تاريخ آخر تسجيل الوصول: لا**

- بعد 180 يوماً من انتهاء صلاحية شهادة الجهاز وعدم تجديدها، يتم حذف الجهاز.

**ملاحظة** في كلتا الحالتين، يجب أن يتم تسجيل الجهاز بنجاح في Intune. يحدث التسجيل أثناء تسجيل الجهاز الأول مع خدمة Intune.

إذا كان الجهاز يسجل بنجاح إلى إينتوني ولكن لا تصبح Intune مسجلة، يتم حذف الجهاز 270 يوما بعد التسجيل. (90 يوماً لوضع علامة على الجهاز كما إبطال، ثم 180 يوماً أخرى لحذف السجل.)

لا توجد آلية حالياً في وحدة التحكم Intune لتحديد تاريخ انتهاء صلاحية شهادة الجهاز لأي جهاز معين.