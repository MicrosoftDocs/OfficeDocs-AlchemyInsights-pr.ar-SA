---
title: 726 حظر أعاده توجيه البريد الكتروني
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "726"
- "1200004"
ms.assetid: 8865c68e-7e8a-4135-a254-d7f69f1ded30
ms.openlocfilehash: 610013c4f46e999f1a8715aea14dd557ed8b0e2a
ms.sourcegitcommit: 88f24bb6ced16842de165af416e3f21feae13063
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 10/15/2020
ms.locfileid: "48478338"
---
# <a name="blocking-or-unblocking-email-forwarding"></a>حظر أعاده توجيه البريد الكتروني أو إلغاء حظره

لتمكين أعاده توجيه البريد الكتروني لعلبه بريد معينه أو تعطيلها ، راجع [تكوين أعاده توجيه البريد الكتروني](https://docs.microsoft.com/microsoft-365/admin/email/configure-email-forwarding).

علي مستوي المستاجر ، يتم التحكم في أعاده التوجيه الخارجي باستخدام نهج البريد العشوائي الصادر. يمكنك التحقق من نهج تصفيه البريد العشوائي الصادر من مركز الأمان والتوافق [هنا](https://protection.office.com/antispam) أو باستخدام [الأمر هوستيدوتبوندسبامفيلتيربوليسي](https://docs.microsoft.com/powershell/module/exchange/get-hostedoutboundspamfilterpolicy).

إذا ظهرت رسالة الخطا التالية: **"550 5.7.520 تم رفض الوصول ، فلا تسمح مؤسستك باعاده التوجيه الخارجي"**، الرجاء التاكد من تكوين النهج لتمكين الإرسال التلقائي الخارجي.

**ملاحظه:** من المستحسن الإبقاء علي أوتوفوروارد الخارجي معطلا علي نهج تصفيه البريد الكتروني الصادر الافتراضي وتمكينه فقط للمستخدمين الذين يحتاجون إلى أعاده توجيه خارجيه من خلال إنشاء نهج مخصص لهؤلاء المستخدمين. يمكنك قراءه المزيد في [تكوين أعاده توجيه البريد الكتروني الخارجي في Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/external-email-forwarding).