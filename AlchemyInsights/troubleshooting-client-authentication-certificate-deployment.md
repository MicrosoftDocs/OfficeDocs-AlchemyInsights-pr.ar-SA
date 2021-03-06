---
title: استكشاف أخطاء نشر شهادات مصادقه العميل وإصلاحها
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/28/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1546"
- "9000076"
ms.openlocfilehash: cecbd091447e63f2d5012ceaf96e050c92a171e6
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47658973"
---
# <a name="troubleshooting-client-authentication-certificate-deployment"></a>استكشاف أخطاء نشر شهادات مصادقه العميل وإصلاحها

يتم استخدام ملفات تعريف شهادات عميل نديس/سسيب و PKCS/PFX بشكل شائع بالاضافه إلى أنواع ملفات تعريف أخرى مثل Wifi و VPN والبريد الكتروني للسماح للمستخدمين بالمصادقة علي موارد الشركة. عند ارتباط أنواع ملفات التعريف هذه بملف تعريف شهادة عميل ، فانه يعتمد علي النشر الناجح لهذا التشكيل الجانبي.

غالبا ما يتطلب اعداد البنية الاساسيه الاوليه والتكوين المقترن بملف تعريف شهادة العميل استكشاف الأخطاء وإصلاحها. للحصول علي دليل مفصل خطوه بخطوه لاعداد موصل نديس وإرشادات استكشاف الأخطاء وإصلاحها لعزل المشاكل المتعلقة بنشر الشهادات ، راجع: 

- [تكوين البنية الاساسيه لدعم سسيب مع Intune](https://support.microsoft.com/help/4459540/troubleshoot-ndes-configuration-for-use-with-intune)
- [نظره عامه حول استكشاف أخطاء ملفات تعريف شهادات سسيب وإصلاحها باستخدام Microsoft Intune](https://support.microsoft.com/help/4457481/troubleshooting-scep-certificate-profile-deployment-in-intune)

استخدم البرامج النصية ل powershell المشار اليها للمساعدة في التحقق من التكوين. للحصول علي مزيد من المعلومات ، راجع [البرامج النصية للتحقق من موصل الشهادة Intune](https://github.com/microsoftgraph/powershell-intune-samples/tree/master/CertificationAuthority).

  
**مشاكل أخرى شائعه**

**عندما أحاول تثبيت موصل الشهادة Intune علي خادم نديس connector ، أتلقى الرسالة "تعذر التحقق من كلمه المرور في طلب الشهادة. ربما تم استخدامه بالفعل. احصل علي كلمه مرور جديده لإرسالها بهذا الطلب. "**  

تعني هذه الرسالة انك تحتاج إلى تشغيل تثبيت موصل الشهادة كمسؤول.

في بعض البيئات ، يجب ان تستخدم الخوادم التي يتم فيها تشغيل شهادة Intune خادم وكيل للاتصال ب Intune ، التالي يجب ان يستخدم موصل الشهادة وكيلا. في بعض الحالات ، يتجاهل موصل نديس إعدادات الوكيل المكونة ، وقد يكون من الضروري تكوين إعدادات الوكيل اثناء التشغيل في سياق أمان LocalSystem. 
 
الحل هو تشغيل Internet Explorer كنظام وتكوين وكيل في IE. بعد أعاده تشغيل خدمه Intune Connector ، يتصل موصل نديس ب Intune.

**لم تعد أجهزه المستخدم تتلقي شهادات سسيب من نديس.**

من الممكن ان تكون شهادة مصادقه العميل التي تم إصدارها إلى خادم نديس ، والتي تم تحديدها اثناء تثبيت موصل نديس ، قد انتهت أو مفقوده. لحل هذه المشكلة: 
 
1. أزاله تثبيت موصل نديس.  
2. استخدم هذه التفاصيل لطلب مصادقه عميل جديد أو شهادة مصادقه الخادم: 
 
    - اسم الموضوع: CN = fqdn خارجي  
    - الاسم البديل للموضوع (مطلوب كليهما): DNS = fqdn خارجي ، DNS = fqdn داخلي 
 
3. أعد تثبيت موصل نديس مع الشهادة الجديدة.