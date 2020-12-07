---
title: استخدام أساسات أمان Microsoft Intune لتكوين أجهزه Windows 10
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004135"
- "7211"
ms.openlocfilehash: 24257f1ac5752df1598d08fcfdb95ee2642adfea
ms.sourcegitcommit: c069f1b53567ad14711c423740f120439a312a60
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 12/04/2020
ms.locfileid: "49573268"
---
# <a name="use-microsoft-intune-security-baselines-to-configure-windows-10-devices"></a>استخدام أساسات أمان Microsoft Intune لتكوين أجهزه Windows 10

تساعد الخطوط الاساسيه للامان في Intune علي حماية المستخدمين والاجهزه. أساسات الأمان هي المجموعات التي تم تكوينها مسبقا في Windows لتطبيق مجموعه معروفه من الإعدادات والقيم الافتراضية الموصي بها بواسطة فرق الأمان ذات الصلة. بإنشاء ملف تعريف أساس الأمان في Intune ، يمكنك إنشاء قالب يتكون من ملفات تعريف متعددة لتكوين الاجهزه.

عند نشر أساسات الأمان علي مجموعات من المستخدمين أو الاجهزه ، يتم تطبيق الإعدادات علي الاجهزه التي يتم تشغيلها علي Windows 10 أو إصدار أحدث. علي سبيل المثال ، يقوم الأساس الخاص بأمان MDM تلقائيا (1) بتمكين BitLocker لمحركات الاقراص القابلة للازاله ، (2) يتطلب كلمه المرور الخاصة بإلغاء تامين جهاز ، و (3) بتعطيل المصادقة الاساسيه. عندما لا تعمل القيمة الافتراضية لبيئتك ، يمكنك تخصيص الأساس لتطبيق الإعدادات التي تحتاج اليها.

تساعدك الخطوط الاساسيه أيضا في إنشاء سير عمل "متكامل الأمان" في Microsoft 365. فيما يلي بعض المزايا التالية:

- يتضمن أساس الأمان أفضل الممارسات والتوصيات لإعدادات تؤثر علي الأمان. نظرا لان شركاء Intune مع فريق أمان Windows الذين يقومون بإنشاء أساسات لنهج المجموعة ، فان هذه التوصيات تستند إلى الإرشادات المتصلة والتجربة الشاملة.
- إذا كنت جديدا في Intune ولم تكن متاكدا من مكان البدء ، سيساعدك أساس الأمان علي إنشاء ملف تعريف أمن ونشره بسرعة.
- إذا كنت تستخدم حاليا نهج مجموعه ، فمن الممكن ان تكون عمليه الترحيل إلى الغرض من الاداره ل Intune for management أكثر سهوله بالنسبة إلى أساسات الأمان ، لأنها مضمنه في Intune وتتضمن إمكانيات القص المتطورة للاداره.

لمعرفه المزيد ، راجع الخطوط الاساسيه [لامان Windows](https://go.microsoft.com/fwlink/?linkid=2141503) [وأداره الاجهزه المحمولة](https://go.microsoft.com/fwlink/?linkid=2141701).