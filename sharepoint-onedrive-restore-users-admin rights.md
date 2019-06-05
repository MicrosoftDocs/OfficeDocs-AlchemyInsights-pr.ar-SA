---
title: منح المستخدمين حق الوصول إلى SharePoint وأونيدريفي
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: ae4d2c00be6387744bdc84e1d8a021530f80f8fa
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715199"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>منح المستخدمين حق الوصول إلى SharePoint وأندريف

<p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">تحدث هذه المشكلة غالباً عندما يكون مستخدم حذف وإعادة إنشاء بواسطة نفس اسم المستخدم الأساسي (UPN). يتم إنشاء حساب جديد باستخدام قيمة PUID (المعرف الفريد ل Passport) مختلفة. عندما يحاول المستخدم الوصول إلى مجموعة موقع أو أندريف بها، لدى المستخدم PUID غير صحيحة. سيناريو ثاني يتضمن الدليل المزامنة مع وحدة "خدمة active Directory" تنظيمية (OU). إذا كان المستخدمون قد مسبقاً بتسجيل الدخول إلى SharePoint، ثم يتم نقلها إلى OU مختلفة و resynced مع SharePoint، قد تواجه هذه المشكلة.</span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">لحل هذه المشكلة يجب عليك استعادة UPN الأصلي باستخدام الخطوات المذكورة في هذه المادة، <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">استعادة مستخدم في Office 365.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">بعد القيام بذلك، يمكنك التحقق من المستخدم لديه حقوق المسؤول إلى الموقع أندريف باتباع الخطوات <a href="https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive">إضافة للمسؤول أندريف المستخدم.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">لمزيد من المعلومات حول مستويات الأذونات، راجع المقال، <a href="https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels">فهم مستويات الأذونات في SharePoint.</a>&nbsp;</span></p>