---
title: وظيفة الفرق الاضافيه ل Mac
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/10/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6173"
- "9003233"
ms.openlocfilehash: 74bd424f71a59b80a91b960b815363668bee7036
ms.sourcegitcommit: 1361b2b37fd0201502a1a3547084961de284a3fc
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 08/11/2020
ms.locfileid: "46629351"
---
# <a name="teams-add-in-for-mac"></a>وظيفة الفرق الاضافيه ل Mac

لاستكشاف الأخطاء وإصلاحها لمستخدمي نظام التشغيل الاضافيه لفرق العمل المفقودة ، اتبع الخطوات التالية:

**الخطوة 1:** إذا كان لديك Exchange المختلط محليا (2016 CU3 أو إصدار لاحق) ، فاستخدم الاداه Test-HMA.ps1 للتاكد من تكوين المصادقة الاضافيه المختلطة بشكل صحيح. للحصول علي مزيد من المعلومات ، راجع [التحقق من صحة اعداد المصادقة الحديثة المختلط ل Outlook ل iOS و Android](https://aka.ms/AA980zq).  

**ملاحظه** استخدم تنسيق عنوان UPN (علي سبيل المثال ، [username@contoso.com](mailto:username@contoso.com)) ، وليس domain\username. قم بذلك حتى للمستخدمين الذين لديهم علب بريد Exchange Online.

**الخطوة 2:** اجعل المستخدم ينتقل إلى **Tools**  >  **أدوات الحسابات**... في Outlook for Mac ، وابحث عن الحساب وحدده. قم بتاكيد اسم المستخدم المدرج بتنسيق UPN (علي سبيل المثال ، [username@contoso.com](mailto:username@contoso.com)).

**الخطوة 3:** تاكد من ان المستخدم هو مستخدم لفرق Microsoft مرخص. يجب ان يستخدم المستخدم اشتراك Office 365 for Mac أو إصدار المنتج 16.24 أو إصدار أحدث.