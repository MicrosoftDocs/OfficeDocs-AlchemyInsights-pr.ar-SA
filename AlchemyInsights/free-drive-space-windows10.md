---
title: تحرير مساحة على محرك الأقراص في Windows 10
ms.author: pebaum
author: pebaum
manager: dansimp
ms.date: 03/16/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9771"
- "9005403"
ms.openlocfilehash: 3838f3db3bc5f54bcb1a2558484056f3194b76e1
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 03/19/2021
ms.locfileid: "51034855"
---
# <a name="free-up-drive-space-in-windows-10"></a>تحرير مساحة على محرك الأقراص في Windows 10

فيما يلي خياران لتحرير مساحة على محرك الأقراص في Windows:

- حرر مساحة على محرك الأقراص في Windows 10.
- حرر مساحة لتحديثات Windows 10 باستخدام جهاز تخزين خارجي.

إذا كان لا يزال لديك مساحة منخفضة على القرص بعد استخدام "تنظيف القرص"، فمن المحتمل أن مجلد Temp يمتلئ بسرعة بملفات التطبيق (appx.) المستخدمة بواسطة Microsoft Store. لإصلاح هذه المشكلة، أعد تعيين المتجر، وأمسح ذاكرة التخزين المؤقت للمتجر، ثم قم بتشغيل مصلح مصلح Windows Update ومصلحها. تأكد من إغلاق Microsoft Store قبل المتابعة إلى هذه الخطوات.

**الخطوة 1: إعادة تعيين Microsoft Store**

**ملاحظة** ويحذف هذا بشكل دائم بيانات التطبيق على الجهاز، بما في ذلك تفضيلاتك وتفاصيل تسجيل الدخول.

1. حدد **بدء**  >  **الإعدادات**  >  **تطبيقات التطبيقات**&  >  **الميزات**.

1. في قائمة التطبيقات، حدد موقع Microsoft Store وحدده.

1. حدد **خيارات متقدمة**.

1. قم بالتمرير لأسفل وحدد **إعادة تعيين**، ثم تأكيد **إعادة تعيين**.

**الخطوة 2: مسح ذاكرة التخزين المؤقت لمتجر Microsoft**

1. اضغط على مفتاح شعار Windows + R لفتح مربع الحوار تشغيل.

1. اكتب wsreset.exe وحدد **موافق**.

1. يتم فتح نافذة "موجه الأوامر" فارغة. بعد حوالي 10 ثوان، يتم إغلاق النافذة ويفتح المتجر تلقائيا.

**الخطوة 3: إعادة تعيين Windows Update**

1. حدد **بدء**  >  **الإعدادات**  >  **تحديث & استكشاف** الأخطاء  >  **وإصلاحها.**

1. قم بالتمرير لأسفل وحدد **Windows Update** من القائمة، وحدد تشغيل م استكشاف **المشاكل ومشكلاتها.**

1. إعادة تشغيل الكمبيوتر والتحقق مما إذا كنت لا تزال تواجه المشكلة.
