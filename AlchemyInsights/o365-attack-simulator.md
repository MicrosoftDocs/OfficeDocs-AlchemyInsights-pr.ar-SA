---
title: 2681 محاكاة الهجوم في مكتب 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 07d7622c00074f7bd0d567185824db448f1eeef3
ms.sourcegitcommit: 7232b48bcd8bb9867d52a2f055a46ce76a58b8da
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 09/27/2019
ms.locfileid: "37305319"
---
# <a name="attack-simulator-in-office-365"></a>هجوم محاكي في مكتب 365

- هل أنت في عداد المفقودين محاكي الهجوم ؟ هجوم محاكي يتطلب **مكتب 365 متقدمة التهديد خطه الحماية 2 (ATP خطه 2)** أو **مكتب 365 المؤسسة E5**. **لا** يتم تضمين محاكي الهجوم في office 365 المتقدمة خطه حماية التهديد 1 (ATP خطه 1) ، مكتب 365 المؤسسة E3 ، أو اي مكتب 365 الاشتراكات التجارية.

- يتطلب الحساب الذي تستخدمه لتشغيل الهجمات المحاكية المسؤول العمومي أو أذونات مسؤول الأمان والمصادقة متعددة العوامل (وزاره الخارجية). لمزيد من المعلومات حول متطلبات محاكي الهجوم ، راجع [هذا الموضوع](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).

- الأشياء الهامه التي يجب معرفتها عن محاكاة الهجوم **الغاشمة القوه كلمه المرور** :

  - إذا كان الحساب الهدف لديه تمكين وزاره الخارجية وخمنت كلمه المرور بشكل صحيح ، لن تظهر الحساب كما للخطر (سيكون عامل المصادقة الثاني غير مكتملة).

  - لا يمكن ان يكون ملف كلمه المرور أكبر من 10 ميغابايت. استخدم كلمه مرور واحده لكل سطر ، وتضمين سطر فارغ (إرجاع الحرف) بعد كلمه المرور الاخيره في القائمة.

- الأشياء الهامه التي يجب معرفتها حول **الخداع الرمح** إرفاق المحاكاة:

  - حسب التصميم ، لا يمكنك توفير قيمه مخصصه **لعنوان URL لخادم تسجيل الدخول الاحتيالي**.

  - إذا كان المستلم يستخدم [تمكين الوظيفة الاضافيه "رسالة التقرير](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) " للإبلاغ عن الرسالة كتصيد احتيالي ، قد لا تتلقي تنبيات للرسالة (لان هذا هو هجوم محاكاة).

- التقارير: بعد اكتمال الهجوم المحاكي ، يمكنك النقر فوق **تفاصيل الهجوم** لمشاهده التقرير.

- للحصول علي تعليمات مفصله وميزات جديده في هجوم محاكي ، انظر [هجوم محاكي في مكتب 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).