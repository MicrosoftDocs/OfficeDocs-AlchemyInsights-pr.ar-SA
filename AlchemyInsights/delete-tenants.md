---
title: حذف المستاجر
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 11/23/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003256"
- "7297"
ms.openlocfilehash: aa1525c6d221dbcfe91da7abd3d094ae1c228ece
ms.sourcegitcommit: 0f42d1600b6845083f0273d14c1d9e59344e4371
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 11/30/2020
ms.locfileid: "49564355"
---
# <a name="delete-tenant"></a><span data-ttu-id="3e09f-102">حذف المستاجر</span><span class="sxs-lookup"><span data-stu-id="3e09f-102">Delete tenant</span></span>

<span data-ttu-id="3e09f-103">لحذف Azure AD ، تاكد من:</span><span class="sxs-lookup"><span data-stu-id="3e09f-103">To delete an Azure AD, ensure:</span></span>
- <span data-ttu-id="3e09f-104">أنت مسؤول عام علي الدليل.</span><span class="sxs-lookup"><span data-stu-id="3e09f-104">You are a Global Administrator on the directory.</span></span>
- <span data-ttu-id="3e09f-105">لم يتم تسجيل دخولك باستخدام حساب لديه الدليل الافتراضي مثل contoso.onmicrosoft.com في الحساب الذي تم تسجيل دخوله ، مثل admin@contoso.onmicrosoft.com.</span><span class="sxs-lookup"><span data-stu-id="3e09f-105">You are NOT signed in with an account that has the default directory such as contoso.onmicrosoft.com in the signed--in account, such as admin@contoso.onmicrosoft.com.</span></span>
- <span data-ttu-id="3e09f-106">قم بازاله اي تطبيقات نشطه في الدليل قبل الحذف.</span><span class="sxs-lookup"><span data-stu-id="3e09f-106">Remove any active applications in the directory before deletion.</span></span> <span data-ttu-id="3e09f-107">لأزاله التطبيقات النشطة ، انتقل إلى تسجيلات التطبيق وأزاله التطبيقات الموجودة.</span><span class="sxs-lookup"><span data-stu-id="3e09f-107">To remove active applications, navigate to App registrations and remove the existing applications.</span></span>
- <span data-ttu-id="3e09f-108">لا توجد اي اشتراكات نشطه لأي من خدمات Microsoft عبر الإنترنت ، مثل Microsoft Azure أو Office 365 أو Azure AD Premium المقترنة بالدليل.</span><span class="sxs-lookup"><span data-stu-id="3e09f-108">There are no active subscriptions for any Microsoft Online Services, such as Microsoft Azure, Office 365 or Azure AD Premium associated on the directory.</span></span> <span data-ttu-id="3e09f-109">يمكنك نقل الاشتراكات أو تسريع إلغاء الاشتراكات النشطة عبر دعم Azure والفوترة.</span><span class="sxs-lookup"><span data-stu-id="3e09f-109">Transfer your subscriptions or expedite cancellation of active subscriptions via Azure Support and Billing.</span></span> <span data-ttu-id="3e09f-110">تعرف علي المزيد حول كيفيه إلغاء اشتراكات Office 365 و Azure.</span><span class="sxs-lookup"><span data-stu-id="3e09f-110">Learn more on How to Cancel Office 365 and Azure subscriptions.</span></span> <span data-ttu-id="3e09f-111">للحصول علي إرشادات حول اقران اشتراك موجود أو اضافته إلى المستاجر ، راجع [اقران اشتراك azure أو اضافته إلى مستاجر AZURE AD](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory).</span><span class="sxs-lookup"><span data-stu-id="3e09f-111">For guidance on associating or adding an existing subscription to a tenant, see [Associate or add an Azure subscription to your Azure AD tenant](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory).</span></span>
- <span data-ttu-id="3e09f-112">لا يوجد ترخيص نشط.</span><span class="sxs-lookup"><span data-stu-id="3e09f-112">There are no Active license.</span></span> <span data-ttu-id="3e09f-113">لأزاله التراخيص ، راجع [كيفيه أزاله الاشتراك لأزاله الترخيص](https://docs.microsoft.com/azure/active-directory/enterprise-users/directory-delete-howto#delete-a-subscription).</span><span class="sxs-lookup"><span data-stu-id="3e09f-113">To remove licenses, see [How to remove Subscription to Remove license](https://docs.microsoft.com/azure/active-directory/enterprise-users/directory-delete-howto#delete-a-subscription).</span></span>
- <span data-ttu-id="3e09f-114">لا يوجد اي مستخدمين نشطين آخرين في الدليل بجانب نفسك كالمسؤول العام عند محاولة حذف Azure AD.</span><span class="sxs-lookup"><span data-stu-id="3e09f-114">There are no other active users in the directory besides yourself as the Global Administrator when attempting to delete the Azure AD.</span></span> <span data-ttu-id="3e09f-115">قم بازاله اي مستخدمين آخرين نشطين ، سيحتاج اي تبعيات علي اسم مجال مخصص في المستاجر إلى ازالته ، مثل المستخدمين الذين تم إنشاؤهم باستخدام admin@contoso.com.</span><span class="sxs-lookup"><span data-stu-id="3e09f-115">Remove any other active users, and any dependencies on a custom domain name in the tenant will also need to be removed, such as users created with admin@contoso.com.</span></span>

<span data-ttu-id="3e09f-116">لمزيد من الخطوات التفصيلية حول كيفيه القيام بما يلي:</span><span class="sxs-lookup"><span data-stu-id="3e09f-116">For more detail steps on how to:</span></span>
- <span data-ttu-id="3e09f-117">حذف "Azure Active directory" أو "الاشتراك" ، راجع [حذف Azure active](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-delete-howto)directory.</span><span class="sxs-lookup"><span data-stu-id="3e09f-117">Delete "Azure Active Directory" or "subscription",  see [Delete Azure Active Directory](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-delete-howto).</span></span>
- <span data-ttu-id="3e09f-118">أزاله التطبيقات في الدليل ، راجع [أزاله التطبيقات](https://docs.microsoft.com/azure/active-directory/develop/quickstart-remove-app).</span><span class="sxs-lookup"><span data-stu-id="3e09f-118">Removing applications in the directory, see [Removing Applications](https://docs.microsoft.com/azure/active-directory/develop/quickstart-remove-app).</span></span> 
