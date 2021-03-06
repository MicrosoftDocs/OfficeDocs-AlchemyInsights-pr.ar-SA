---
title: تغيير مجال Yammer الافتراضي
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002662"
- "5162"
ms.openlocfilehash: 6a7215ef7187e8dc6c834470b4724692b239efd4
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51817921"
---
# <a name="changing-the-defaultprimary-yammer-domain"></a>تغيير مجال Yammer الافتراضي/الأساسي

يتضمن عنوان URL الخاص بـ Yammer اسم المجال الأساسي الحالي لشبكه Yammer الخاصة بك. قد لا يتطابق اسم المجال هذا مع مجموعة أسماء المجالات الأساسية في Office 365 أو Azure AD. يوجد اختلافات في الأسلوب بناءً على عدد المجالات المخصصة المضافة إلى المستأجر، وعما إذا كان Yammer يتمتع بتكوين مدعوم (مستأجر واحد: شبكة واحدة، أو 1:1). تتوفر الوثائق الخاصة بمجالات Yammer [و Office 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/manage-yammer-domains).

السبب الأكثر شيوعا لرؤية مجال غير صحيح هو وجود العديد من شبكات Yammer والتي يجب تجميعها. [إن التجميع وصولًا إلى شبكة واحدة](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks) باستخدام أداة ترحيل الشبكة تعتبر خطوة أولى مهمة. قم بتكملة ذلك قبل محاولة تعيين مجالك الأساسي.

**لا يوجد المجالات المخصصة**

بالنسبة للمستأجرين الجدد، سيتم استخدام المجال الافتراضي (على سبيل المثال fabrikam.onmicrosoft.com) من المستأجر لـ Yammer. يتم تعيين المجال الأساسي على yammer.com/fabrikam.onmicrosoft.com.

**مجال مخصص واحد**

سيحدد Yammer المجال المخصص تلقائيًا (على سبيل المثال fabrikam.com) من المستأجر كالمجال الأساسي في Yammer. يتم تعيينه على yammer.com/fabrikam.com. يتم إجراء هذا التغيير عن طريق خدمة مزامنة المجال، ويمكن أن يستغرق الأمر حتى 24 ساعة حتى يكون ساري المفعول.

**مجالات مخصصة متعددة**

يمكن أن يتضمن Yammer مجالًا أساسيًا مختلفًا عن المجال المستأجر الافتراضي. نظرًا لوجود مجالات مخصصة متعددة، فإن Yammer لا يحاول تخمين المجال الصحيح من تلك المجالات المتوفرة. يجب فتح حالة دعم للمطالبة بتغيير اسم المجال الأساسي إلى المجال الأساسي الذي تختاره.

**معلومات إضافية حول استكشاف الأخطاء وإصلاحها**

من المحتمل في بعض الحالات حدوث تنقل للمجالات بين المستأجرين وعدم تمكن خدمة مزامنة المجال من العمل بنجاح. قد تواجهك مشاكل خاصة بتسجيل الدخول أو مشاكل أخرى، بالإضافة إلى وجود مجال أساسي غير صحيح. لحل هذه المشكلة، يجب نقل المجالات إلى الشبكة الصحيحة بمساعدة من دعم Microsoft. تتطلب هذه الحالة مساعدة مباشرة وقد يُستغرق بعض الوقت لحلها، وخاصة في حالة وجود قائمة طويلة للغاية بأسماء المجالات. افتح حالة دعم للحصول على مساعدة في حل تلك الأنواع من المشاكل.

عند العمل مع وكيل دعم، سيتأكد من التحقق من المجالات على مستأجر تحت سيطرتك. قد يسألك أسئلة تحقق إضافية حول مجالاتك إذا ما تم إضافتها إلى مستأجرك ولكن لم يتم التحقق منها بواسطة DNS. يرجى التأكد من أنه تم التحقق من المجالات بواسطة DNS لزيادة سرعة العملية.
