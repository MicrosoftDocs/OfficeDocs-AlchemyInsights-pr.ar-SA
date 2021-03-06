---
title: 2491 تنبيه رسائل البريد الإلكتروني من نهج "تسليم التصيد الاحتيالي بسبب تجاوز المستأجر أو المستخدم"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2b373423cf3e63b76a62465dd62076c023580e94
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 05/19/2021
ms.locfileid: "52544565"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>تنبيه رسائل البريد الإلكتروني من نهج "تسليم التصيد الاحتيالي بسبب تجاوز المستأجر أو المستخدم"

تم طرح نهج تنبيه افتراضي باسم "تم تسليم التصيد الاحتيالي بسبب تجاوز المستأجر أو المستخدم" للمستأجرين باستخدام تراخيص Microsoft Defender Office 365 P1 و P2. إذا تلقيت هذا التنبيه، فيما يلي الخطوات اللازمة للتحقق من ذلك:

1. من رسالة التنبيه، انقر فوق **عرض** التنبيهات الانتقال إلى صفحة التنبيهات في مركز التوافق & الأمان. 

2. حدد التنبيه لرؤية الخيار لعرض قائمة الرسائل **أو** عرض الرسائل **في المستكشف**. يأخذك كل من هذين الخيارين إلى تفاصيل الرسالة، التي تتضمن "معرّف الرسالة". لاحظ أن الارتباط "مستكشف التهديدات" سيصفي الرسائل التي تتطابق مع معايير التنبيه تلقائيا. قد تحتاج إلى ضبط عامل تصفية التاريخ في "مستكشف التهديدات".

تم تسليم رسالة التصيد الاحتيالي بسبب تجاوز تم تكوينه يدويا:

- مرسل مسموح به أو مجال تم تعيينه بواسطة المستخدم.

- مرسل مسموح به أو مجال تم تعيينه من قبل المسؤول في نهج مكافحة البريد العشوائي.

- عنوان IP مسموح به في نهج عامل تصفية الاتصال.

- قاعدة تدفق البريد (المعروفة أيضا باسم قاعدة النقل) التي تم تكوينها للسماح بالرسائل الواردة.

إذا كنت تعتقد أنه تم وضع علامة تصيد احتيالي على الرسالة بشكل غير صحيح، فاستخدم Outlook "تقرير الرسالة" الإضافية لإرسال نماذج الرسائل إلى Microsoft. [](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2)
