---
title: قواعد الاعمال في Dynamics 365 Forms-قاعده العمل التي لا يتم تكوينها لنموذج
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 7422b67973f93ce10c1639209cc50206a1016c10
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47711478"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>لا يحدث الحدث OnChange إذا تم تغيير الحقل برمجيا

لا يحدث الحدث *OnChange* إذا تم تغيير الحقل برمجيا باستخدام *السمة.* أسلوب [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . إذا كنت تريد تشغيل معالجات الاحداث الخاصة بالحدث *OnChange* بعد تعيين القيمة ، سيتم استخدام أسلوب [فيريونتشانجي](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) *للسمة فورمكونتيكست* في التعليمات البرمجية.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
