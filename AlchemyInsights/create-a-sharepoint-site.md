---
title: إنشاء موقع SharePoint
ms.author: pebaum
author: pebaum
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ms.collection: Adm_O365
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "3911416"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 5ebaa342ca9864bc31a9ef26eebcf42d96523871
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806926"
---
# <a name="create-a-sharepoint-site"></a>إنشاء موقع SharePoint

إنشاء مواقع أو ادارتها من [مواقع نشطه](https://admin.microsoft.com/sharepoint?page=sitemanagement&modern=true) في مركز أداره SharePoint. للحصول علي مزيد من المعلومات ، راجع [أداره المواقع في مركز أداره SharePoint الجديد](https://docs.microsoft.com/sharepoint/manage-site-creation). 

## <a name="tips"></a>المزيد

- **لا يمكنك** إنشاء موقع باستخدام عنوان URL نفسه لموقع موجود. إذا قمت بحذف موقع واتمني لك أعاده استخدام عنوان URL ، فمن المحتمل ان يكون الموقع المحذوف موجودا ضمن [المواقع المحذوفة](https://admin.microsoft.com/sharepoint?page=recyclebin&modern=true). سيحتاج الموقع إلى الحذف بشكل دائم لأعاده استخدام عنوان URL. لأزاله موقع بالبالكامل باستخدام Powershell ، راجع المثال الخاص [بازاله SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet.
- قد لا يتمكن بعض المستخدمين من إنشاء موقع. [راجع أداره إنشاء الموقع في SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).
- من المحتمل ان يظهر الموقع بشكل عالق عند **الإنشاء** أكثر من المتوقع. إذا تم تمرير أكثر من 24 ساعة منذ المرة الاولي التي قمت فيها بمشاهده هذه المشكلة ، يرجى تسجيل تذكره دعم. في حالات كثيره ، نحن نعمل بالفعل علي حل. يرجى تقديم 24 ساعة علي الأقل لإكمال حل.
