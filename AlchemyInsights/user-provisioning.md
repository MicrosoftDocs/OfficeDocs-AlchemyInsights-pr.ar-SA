---
title: توفير المستخدم
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004348"
- "8428"
ms.openlocfilehash: bd415b2d44bccf0c2b3eccb4e38452498b748b3a
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 03/04/2021
ms.locfileid: "50480840"
---
# <a name="user-provisioning"></a>توفير المستخدم

- استخدم إمكانية [توفير](https://docs.microsoft.com/azure/active-directory/app-provisioning/provision-on-demand) عند الطلب لتوفير مستخدم والحصول على تشخيص تفصيلي حول الخطوات التي تم اتخاذها.
- استكشاف المشاكل التي تواجهها عند توفير المستخدمين والمجموعات [وإصلاحها،](https://docs.microsoft.com/azure/active-directory/app-provisioning/application-provisioning-config-problem-no-users-provisioned)راجع دليل استكشاف الأخطاء وإصلاحها الذي لا يتم فيه توفير أي مستخدمين.
- إذا لاحظت عدم توفير الخدمة للمستخدمين، فشاهد توفير السجلات [(معاينة)](https://docs.microsoft.com/azure/active-directory/reports-monitoring/concept-provisioning-logs) في Azure Active Directory (AD). ابحث عن إدخالات السجل المتعلقة بمستخدم معين.
- أعد تشغيل عملية توفير الخدمة بشكل دوري لقبضة أي مستخدمين فاتهم في دورة توفير سابقة.
- ربما لم يتم توفير الخدمة للمستخدم/المجموعة نظرا لعدم فرصة تقييم المستخدم بعد. راجع الإرشادات المتعلقة بمدى الوقت الذي تستغرقه عملية التكوين بالإضافة إلى شريط التقدم على صفحة تكوين الإعداد. إذا كانت الحالة الثابت المحددة في قسم التفاصيل الإضافية قبل تاريخ إنشاء/تحديث/حذف المستخدم، فهذا يعني أننا لم نقيم المستخدم بعد. في هذا السيناريو، أفضل شيء يجب فعله هو انتظار انتهاء توفير الخدمة. إذا تم تحقيق الحالة الثابتة، نوصي بإجراء إعادة تشغيل من واجهة المستخدم في مدخل Azure.
  - لاحظ أن خدمتنا على علم فقط بتغييرات المستخدم/المجموعة في النظام المصدر (Azure Active Directory). إذا تمت إزالة مستخدم/مجموعة مباشرة في التطبيق (على سبيل المثال، ServiceNow)، فنحن لسنا على علم بهذه التغييرات ولا نتراجع عن هذه التغييرات استنادا إلى حالة المستخدم في النظام المصدر. في هذا السيناريو، من الأفضل التراجع عن التغيير مباشرة في التطبيق الهدف.
- قيمت خدمتنا المستخدم/المجموعة وحددنا أنه لا يجب توفيرها:
  - إذا قمت بتعيين النطاق إلى المستخدمين والمجموعات المعينة، فتحقق مما إذا تم تعيين المستخدم/المجموعة للتطبيق.
  - إذا تم تعيين المستخدم/المجموعة إلى التطبيق، فتأكد من عدم تعيينها لدور الوصول الافتراضي. لا يمكن استخدام هذا الدور لتوفيره.
  - إذا قمت بتعيين عامل تصفية تحديد عدد استنادا إلى سمة، فتأكد من أن المستخدم يلبي المعايير التي حددتها.
  - إذا كان المستخدمون موجودين بالفعل في النظام الهدف وكانت حالة المستخدم في تطابق المصدر والهدف، فلن نتخذ أي إجراء آخر.
- حاولت خدمتنا توفير الخدمة للمستخدم وفشلت. بالنسبة إلى هذه السيناريوهات، راجع علامة التبويب "استكشاف الأخطاء وإصلاحها" و"التوصيات" لسجلات توفير:
  - قد تكون السمة المطلوبة للمستخدم مفقودة في Azure Active Directory أو لا تتطابق مع التنسيق الذي يتطلبه تطبيق الطرف الثالث. على سبيل المثال، قد يتم تعيين سمة "البلد" على مستخدم إلى "الولايات المتحدة" عندما يكون من المفترض أن تكون الولايات المتحدة.
  - السمة هي سمةرجعية غير موجودة بعد في التطبيق الهدف. السمة الرجوعية هي سمة تشير إلى كائن آخر، على سبيل المثال، مستخدم عضو في مجموعة. سيكون تعريف المستخدم في سمة العضو في المجموعة، ولكن يمكن معالجته فقط إذا كان الكائن المستخدم الذي يشير إلى أنه موجود بالفعل.