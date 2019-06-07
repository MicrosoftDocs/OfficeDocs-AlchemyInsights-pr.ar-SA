---
title: منح المستخدمين حق الوصول إلى SharePoint وأندريف
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
ms.openlocfilehash: 9326932e93970edc96396a141c9b36b14e7b4d4d
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736635"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="8801d-102">منح المستخدمين حق الوصول إلى SharePoint وأندريف</span><span class="sxs-lookup"><span data-stu-id="8801d-102">Give users access to SharePoint and OneDrive</span></span>

<span data-ttu-id="8801d-103">تحدث هذه المشكلة غالباً عندما يكون مستخدم حذف وإعادة إنشاء بواسطة نفس اسم المستخدم الأساسي (UPN).</span><span class="sxs-lookup"><span data-stu-id="8801d-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="8801d-104">يتم إنشاء حساب جديد باستخدام قيمة PUID (المعرف الفريد ل Passport) مختلفة.</span><span class="sxs-lookup"><span data-stu-id="8801d-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="8801d-105">عندما يحاول المستخدم الوصول إلى مجموعة موقع أو أندريف بها، لدى المستخدم PUID غير صحيحة.</span><span class="sxs-lookup"><span data-stu-id="8801d-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="8801d-106">سيناريو ثاني يتضمن الدليل المزامنة مع وحدة "خدمة active Directory" تنظيمية (OU).</span><span class="sxs-lookup"><span data-stu-id="8801d-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="8801d-107">إذا كان المستخدمون قد مسبقاً بتسجيل الدخول إلى SharePoint، ثم يتم نقلها إلى OU مختلفة و resynced مع SharePoint، قد تواجه هذه المشكلة.</span><span class="sxs-lookup"><span data-stu-id="8801d-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="8801d-108">لحل هذه المشكلة يجب عليك استعادة UPN الأصلي باستخدام الخطوات المذكورة في المقالة،[استعادة مستخدم في Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="8801d-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="8801d-109">بعد القيام بذلك، يمكنك التحقق من المستخدم لديه حقوق المسؤول إلى الموقع أندريف باتباع الخطوات التالية [إضافة المسؤول الخاص أندريف المستخدم](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span><span class="sxs-lookup"><span data-stu-id="8801d-109">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="8801d-110">لمزيد من المعلومات حول مستويات الأذونات، راجع المقال، [فهم "مستويات الإذن" في SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="8801d-110">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>