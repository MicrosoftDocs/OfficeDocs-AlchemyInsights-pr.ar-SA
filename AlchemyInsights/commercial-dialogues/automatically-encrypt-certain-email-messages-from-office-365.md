---
title: تشفير بعض رسائل البريد الإلكتروني تلقائيا من office 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 5ddaaed361f6ec934cfffb00cc62a9df2d1a04e8
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743113"
---
# <a name="automatically-encrypt-certain-email-messages-from-office-365"></a>تشفير بعض رسائل البريد الإلكتروني تلقائيا من office 365

1. من مركز [إدارة Exchange،](https://outlook.office365.com/ecp/)اختر **تدفق البريد > قواعد .** 
2. انقر فوق **الأيقونة جديد (+)،** ثم انقر فوق تطبيق تشفير الرسائل وحماية الحقوق في **Office 365 على الرسائل.**
3. في **الاسم**، أدخل اسما للقاعدة، مثل *تشفير كل الرسائل.*
4. في **تطبيق هذه القاعدة إذا**، اختر **[تطبيق على كل الرسائل]**. 
5. إلى بجانب الحقل **قم بما يلي،** انقر **فوق تحديد واحد**. 
6. في القائمة **المنسدلة قالب RMS،** حدد **تشفير**، ثم انقر فوق **موافق**. (إذا لم تشاهد هذا الخيار، فهذا يعني أن خطتك لا تتضمن التشفير التلقائي. ولكن يمكنك إضافته!)
7. حدد **خانة الاختيار تدقيق هذه القاعدة بمستوى الخطورة،** ثم حدد المستوى المطلوب. إذا كانت شركتك لديها التزامات تعاقدية بإرسال كل رسائل البريد الإلكتروني المشفرة، فإني أوصي بإعداد المستوى إلى **مرتفع.**
8. ضمن **اختيار نموذج لهذه القاعدة،** انقر فوق **فرض**. 
9. اختر أي تحديد اختياري (من قائمة التحديدات الاختيارية التي يمكنك إجراءها في هذه المرحلة، ويمكن ترك العديد منها مع الإعداد الافتراضي للتبسيط).
10. انقر فوق **حفظ**.

> [!IMPORTANT]
> يمكنك دائما الرجوع وتحرير هذه القاعدة لاحقا.

لمزيد من المعلومات حول إنشاء قواعد التشفير، راجع تعريف قواعد تدفق البريد لتشفير رسائل البريد الإلكتروني [في Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)
