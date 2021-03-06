---
title: استدعاء رسالة بريد الكتروني أو استبدالها
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: 05016213a1387c5290cb5899359f1f10b5a413c0
ms.sourcegitcommit: 4e0ae808ee2a586339b396320e3edb8ba066a91a
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 11/19/2020
ms.locfileid: "49353493"
---
# <a name="recall-or-replace-an-email-message-in-microsoft-365"></a>استدعاء رسالة بريد الكتروني أو استبدالها في Microsoft 365

- يمكنك **فقط استدعاء الرسائل التي يتم إرسالها إلى الأشخاص في مؤسستك**. علي سبيل المثال ، إذا تم إرسال الرسالة إلى عنوان Gmail ، فلا يمكنك استدعاؤها.
- يمكنك **فقط استدعاء الرسائل المرسلة من Outlook للكمبيوتر الشخصي**. إذا أرسل أحد المستخدمين رسالة باستخدام Outlook for Mac أو Outlook علي الويب ، فلا يمكنك استدعاؤه.
- بصفتك مسؤول مستاجر ، يمكنك **استدعاء الرسائل بالنيابة عن المستخدمين باستخدام PowerShell** (لمزيد من المعلومات ، راجع: [البحث عن رسائل البريد الكتروني وحذفها](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messages-in-your-organization)).
- لا يمكنك استدعاء الرسائل من مركز الاداره. قم بالتمرير لأسفل وصولا إلى "البحث عن رسائل البريد الكتروني وحذفها في مؤسستك" للحصول علي مزيد من المعلومات.

**استدعاء رسالة بريد الكتروني تم إرسالها أو استبدالها**

1. في جزء المجلدات الموجود في الجانب الأيمن من نافذه Outlook ، اختر مجلد العناصر المرسلة.
2. افتح الرسالة التي تريد استدعائها. يجب ان تنقر نقرا مزدوجا لفتح الرسالة. لن يسمح لك تحديد الرسالة بالظهور في جزء القراءة لاستدعاء الرسالة.
3. من علامة التبويب رسالة ، حدد **الإجراءات**  >  **استدعاء هذه الرسالة**.
4. اختر **حذف النسخ غير المقروءة لهذه الرسالة** أو **حذف النسخ غير المقروءة واستبدالها برسالة جديده**، ثم حدد **موافق**.
5. إذا كنت ترسل رسالة بديله ، فقم بإنشاء الرسالة ، ثم حدد **إرسال**.
6. يتوقف نجاح أو فشل رسالة الاستدعاء علي إعدادات المستلمين في Outlook.

لمزيد من المعلومات ، بما في ذلك كيفيه التحقق من الاستدعاء ، راجع [استدعاء رسالة بريد الكتروني التي أرسلتها أو استبدالها](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

**_للبحث عن رسائل البريد الكتروني وحذفها في مؤسستك_**، من الأسهل إذا كنت مسؤولا عاما. إذا لم تكن مسؤولا عاما ، فيجب أضافه حسابك إلى مجموعه ادوار أداره eDiscovery ، أو إلى دور أداره البحث في التوافق. لحذف الرسائل ، ستحتاج إلى الانضمام إلى مجموعه ادوار أداره المؤسسة أو البحث وأزاله دور الاداره. يتم تعيين الأذونات لهذه الأدوار في [مركز توافق & الأمان](https://protection.office.com/).

1. [إنشاء بحث محتوي](https://docs.microsoft.com/microsoft-365/compliance/content-search) للعثور علي الرسالة التي تريد حذفها.
2. [الاتصال بمركز توافق & الأمان PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell).

إذا كنت تستخدم MFA (المصادقة متعددة العوامل) ، فراجع [الاتصال بمركز توافق Microsoft 365 & الأمان ل PowerShell باستخدام مصادقه متعددة العوامل](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell).
