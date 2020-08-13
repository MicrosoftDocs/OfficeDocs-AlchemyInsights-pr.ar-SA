---
title: تجاوز قفل التنشيط على أجهزة iOS الخاضعة للإشراف مع Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1277"
- "6700008"
ms.openlocfilehash: 16be4e0cd2e47fe5d5888cbbe1380774f859e4d6
ms.sourcegitcommit: 07e56267dedfc4cec1143072c791670cbf81186b
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 07/24/2020
ms.locfileid: "45423307"
---
# <a name="bypass-activation-lock-on-supervised-ios-devices-with-intune"></a>تجاوز قفل التنشيط على أجهزة iOS الخاضعة للإشراف مع Intune

القدرة على تجاوز تأمين التنشيط على أجهزة iOS يجعل من السهل استرداد من السيناريو حيث يقوم المستخدم بتمكين تأمين التنشيط على جهاز الشركة، ثم يترك الشركة.

المتطلبات المسبقة لتجاوز قفل التنشيط تشمل:

- الجهاز هو أن "تحت إشراف".
- يتم تمكين تأمين التنشيط بنجاح باستخدام سياسة تقييد جهاز iOS في Intune.

بالإضافة إلى ذلك، عند تجاوز تأمين التنشيط، يجب عليك:

- تمتلك فعليا الجهاز الذي يجري مسحها.
- نسخ التعليمات البرمجية قبل إصدار المسح.

**ملاحظة:** رمز المسح غير حساس لحالة الأحرف، لذا لا تكون الأحرف "-" مطلوبة.

للحصول على التفاصيل، راجع [تجاوز قفل التنشيط على أجهزة iOS الخاضعة للإشراف مع Intune](https://docs.microsoft.com/intune/device-activation-lock-bypass).

**الأسئلة المتداولة**

س: **أصدرت إجراءً عن بعد لإزالة بيانات الشركة من جهاز، والآن هو عالق في حالة معلقة.**

A: لكي يتم إكمال إجراء عن بعد بنجاح، يجب أن يكون الجهاز المستهدف متصلاً و سليمًا. في الحالات التالية، يبقى الإجراء عن بعد في حالة معلقة لمدة 30 يوماً أو حتى الجهاز يعترف الأمر عند الجهاز:

- ليس لديه اتصال.
- يفقد حالته الإدارية مع Intune.

إذا كنت تعتقد أن الجهاز لم يعد يقوم بتسجيل الدخول، وأنه لن يزيل بيانات الشركة، فحدد حذف. يؤدي الحذف إلى إزالة سجل الجهاز بحيث لا يظهر في قائمة الأجهزة Intune. لكي يصبح الجهاز نشطًا مرة أخرى، يجب أن يعيد المستخدم تسجيل الجهاز.

س: **لماذا لا تتوفر بعض الإجراءات عن بعد لاستخدامها؟**

A: ليست كل الأنظمة الأساسية تدعم كافة إجراءات الجهاز البعيد. الإجراءات التالية عن بعد هي النظام الأساسي الخاصة.

- تجاوز قفل التنشيط (iOS فقط)
- بداية جديدة (ويندوز فقط)
- وضع المفقودة (دائرة الرقابة الداخلية فقط)
- تحديد موقع الجهاز (iOS فقط)
- إعادة التشغيل (ويندوز فقط)

لمزيد من التفاصيل حول كل إجراء، راجع [الإجراءات المتوفرة للجهاز](https://docs.microsoft.com/intune/device-management#available-device-actions).