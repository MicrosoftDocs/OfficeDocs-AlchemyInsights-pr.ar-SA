---
title: إصلاح المشاكل المتعلقة بأجهزة Windows 10 في Microsoft Defender Advanced Threat Protection عن بعد
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 5473d090f6d4680f9a62f34f943ac6cea53b2079
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743158"
---
# <a name="remotely-fix-problems-with-onboarding-windows-10-devices-to-microsoft-defender-advanced-threat-protection"></a>إصلاح المشاكل المتعلقة بأجهزة Windows 10 في Microsoft Defender Advanced Threat Protection عن بعد

إذا كان بإمكانك الوصول إلى الكمبيوتر البعيد، فاتبع الخطوات التالية:

1. قم [بتنزيل أداة](https://go.microsoft.com/fwlink/?linkid=2143466) تشخيص محلل اتصال العميل.
2. استخراج MDATPAnalyzer.cmd وتشغيله.
3. حدد موقع سجل التشخيص في مجلد MDATPClientAnalyzerResult، وهو المجلد نفسه حيث تم تنزيل أداة محلل.
4. للعثور على مشاكل تتعلق بالاتصال أو إعدادات وكيل الإنترنت، راجع ملف السجل MDATPClientAnalyzer.txt.

لمعرفة المزيد، راجع [المشاكل المتعلقة بآلات التكهين](https://go.microsoft.com/fwlink/?linkid=2143634).
