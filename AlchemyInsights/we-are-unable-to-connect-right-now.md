---
title: مشكله التنشيط-نحن غير قادرين علي الاتصال الآن
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 84e3a7700558ad8a5fad5b7ded6354fe8736e0f7
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628229"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a>إصلاح تطبيقات Office "نحن غير قادرين علي الاتصال الآن" رسالة

إذا تلقيت هذه الرسالة ، فجرب ما يلي:

1. تحقق من جدار الحماية وبرنامج مكافحه الفيروسات وإعدادات الوكيل للتاكد من انها لا تمنع الوصول إلى الإنترنت إلى تطبيقات Office. راجع [عناوين url 365 Office ونطاقات عناوين IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. انتقل إلى **بدء** > **تشغيل**، ومن ثم اكتب **خدمات. msc**. تاكد من تشغيل كافة الخدمات التالية:
    - الاعداد التلقائي للاجهزه المتصلة بالشبكة
    - خدمه قائمه الشبكة
    - التوعية بموقع الشبكة
    - سجل احداث Windows

إذا لم تكن أحدي هذه الخدمات قيد التشغيل ، فحاول تشغيلها. إذا كان لديك مشكله في بدء الخدمة ، قم بتشغيل الأمر التالي عن طريق فتح موجه الأوامر بأذونات مرتفعه:

**sfc/scannow**

بعد انتهاء هذا الأمر ، قم باعاده تشغيل جهاز الكمبيوتر.

للحصول علي معلومات مفصله ، راجع ["عذرا ، لا يمكننا الاتصال بحسابك. الرجاء المحاولة مره أخرى لاحقا "خطا عند تنشيط Office من Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).