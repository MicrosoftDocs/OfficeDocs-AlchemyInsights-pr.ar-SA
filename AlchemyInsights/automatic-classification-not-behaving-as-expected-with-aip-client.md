---
title: التصنيف التلقائي لا يتصرف كما هو متوقع مع عميل AIP
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002266"
- "4373"
ms.openlocfilehash: 95a994d6a49ee8737a6ebcb196314f92776d8482
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 05/26/2020
ms.locfileid: "44492891"
---
# <a name="automatic-classification-not-behaving-as-expected-with-the-aip-client"></a><span data-ttu-id="7d19d-102">التصنيف التلقائي لا يتصرف كما هو متوقع مع عميل AIP</span><span class="sxs-lookup"><span data-stu-id="7d19d-102">Automatic classification not behaving as expected with the AIP client</span></span>

<span data-ttu-id="7d19d-103">التصنيف التلقائي لا يتصرف كما هو متوقع، استخدم الإرشادات الموصى بها التالية:</span><span class="sxs-lookup"><span data-stu-id="7d19d-103">Automatic classification not behaving as expected, use the following recommended guidelines:</span></span>

1. <span data-ttu-id="7d19d-104">إذا كنت تواجه مشكلات في وضع العلامات التلقائي، فراجع [كيفية تكوين شروط التصنيف التلقائي والموصى به لحماية معلومات Azure](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) وما تبحث عنه أنواع المعلومات [الحساسة](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="7d19d-104">If you are having issues with automatic labeling, see [How to configure conditions for automatic and recommended classification for Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) and [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>
2. <span data-ttu-id="7d19d-105">تحقق مما إذا كنت تستخدم نُهج ًا ذات نطاق لم يتم تكوينها بشكل صحيح: [كيفية تكوين نهج حماية المعلومات Azure لمستخدمين محددين باستخدام نُهج ذات نطاق](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span><span class="sxs-lookup"><span data-stu-id="7d19d-105">Check if you are using scoped policies that aren't configured properly: [How to configure the Azure Information Protection policy for specific users by using scoped policies](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).</span></span>
3. <span data-ttu-id="7d19d-106">إذا لم يكن وضع العلامات التلقائي ة يعمل مع Outlook عند إرفاق مستند مسمى، فتحقق من عدم `DRMEncryptProperty` تعريفه كما هو موضح هنا: إعدادات التسجيل [IRM للأمان](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span><span class="sxs-lookup"><span data-stu-id="7d19d-106">If automatic labeling isn't working for Outlook when attaching a labeled document, verify that `DRMEncryptProperty` isn't defined as described here: [IRM registry settings for security](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).</span></span>
4. <span data-ttu-id="7d19d-107">إذا كنت تستخدم [أنواع المعلومات المضمنة](https://support.office.com/article/What-the-sensitive-information-types-look-for-fd505979-76be-4d9f-b459-abef3fc9e86b) لسياسة حماية معلومات Azure، فتحقق من تطابق المحتوى مع التنسيق المتوقع.</span><span class="sxs-lookup"><span data-stu-id="7d19d-107">If you used the [built-in information types](https://support.office.com/article/What-the-sensitive-information-types-look-for-fd505979-76be-4d9f-b459-abef3fc9e86b) for your Azure Information Protection policy, verify that your content matches the expected format.</span></span>
5. <span data-ttu-id="7d19d-108">تحقق من تكوين التسمية بشكل مناسب **للتلقائي** أو **الموصى به**.</span><span class="sxs-lookup"><span data-stu-id="7d19d-108">Verify that the label is appropriately configured for **Automatic** or **Recommended**.</span></span> <span data-ttu-id="7d19d-109">(تتوفر وضع العلامات**التلقائية** لجميع تطبيقات Office، في حين يتوفر **الموصى به** لجميع تطبيقات Office باستثناء Outlook.)</span><span class="sxs-lookup"><span data-stu-id="7d19d-109">(**Automatic** labeling is available for all Office apps, whereas **Recommended** is available for all Office apps except for Outlook.)</span></span>
6. <span data-ttu-id="7d19d-110">لا يمكنك استخدام التصنيف التلقائي للمستندات ورسائل البريد الإلكتروني التي تم تصنيفها يدويًا مسبقًا أو تم تصنيفها تلقائيًا مسبقًا بتصنيف أعلى.</span><span class="sxs-lookup"><span data-stu-id="7d19d-110">You cannot use automatic classification for documents and emails that were previously manually labeled or previously automatically labeled with a higher classification.</span></span>  <span data-ttu-id="7d19d-111">لمزيد من المعلومات، [راجع: كيفية تطبيق التسميات التلقائية أو الموصى بها](https://docs.microsoft.com/azure/information-protection/configure-policy-classification#how-automatic-or-recommended-labels-are-applied).</span><span class="sxs-lookup"><span data-stu-id="7d19d-111">For more information, see: [How automatic or recommended labels are applied](https://docs.microsoft.com/azure/information-protection/configure-policy-classification#how-automatic-or-recommended-labels-are-applied).</span></span>
7. <span data-ttu-id="7d19d-112">إذا كنت لا تزال تواجه مشكلات، يرجى جمع سجلات عملاء حماية المعلومات Azure وإرفاق السجلات المصدرة بتذكرة الدعم الخاصة بك.</span><span class="sxs-lookup"><span data-stu-id="7d19d-112">If you are still experiencing issues, please collect Azure Information Protection client logs and attach the exported logs to your support ticket.</span></span> <span data-ttu-id="7d19d-113">لتصدير سجلات حماية المعلومات Azure:</span><span class="sxs-lookup"><span data-stu-id="7d19d-113">To export Azure Information Protection logs:</span></span>
    - <span data-ttu-id="7d19d-114">افتح مستند Office أو أنشئ بريدًا إلكترونيًا جديدًا في Outlook.</span><span class="sxs-lookup"><span data-stu-id="7d19d-114">Open an Office document or create a new email in Outlook.</span></span>
    - <span data-ttu-id="7d19d-115">انقر فوق **حماية / تعليمات الحساسية**  >  **والملاحظات.**</span><span class="sxs-lookup"><span data-stu-id="7d19d-115">Click **Protect/Sensitivity** > **Help and feedback**.</span></span>
    - <span data-ttu-id="7d19d-116">انقر فوق **سجلات التصدير**.</span><span class="sxs-lookup"><span data-stu-id="7d19d-116">Click **Export Logs**.</span></span>
    - <span data-ttu-id="7d19d-117">احفظ السجلات على اختيارك للموقع، وإرفاقها بطلب الخدمة الخاص بك.</span><span class="sxs-lookup"><span data-stu-id="7d19d-117">Save the logs to your choice of location, and attach them to your service request.</span></span>

<span data-ttu-id="7d19d-118">لمزيد من المعلومات، راجع:</span><span class="sxs-lookup"><span data-stu-id="7d19d-118">For additional information, see:</span></span>

- [<span data-ttu-id="7d19d-119">كيفية تكوين شروط التصنيف التلقائي والموصى به لحماية المعلومات Azure</span><span class="sxs-lookup"><span data-stu-id="7d19d-119">How to configure conditions for automatic and recommended classification for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/configure-policy-classification)
- [<span data-ttu-id="7d19d-120">أدلة إرشادية للسيناريوهات الشائعة التي تستخدم حماية معلومات Azure</span><span class="sxs-lookup"><span data-stu-id="7d19d-120">How-to guides for common scenarios that use Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/how-to-guides)
- [<span data-ttu-id="7d19d-121">مراجعة وثائق حماية المعلومات Azure</span><span class="sxs-lookup"><span data-stu-id="7d19d-121">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [<span data-ttu-id="7d19d-122">مراجعة اشتراكات وميزات حماية المعلومات في Azure</span><span class="sxs-lookup"><span data-stu-id="7d19d-122">Review Azure Information Protection subscriptions and features</span></span>](https://azure.microsoft.com/pricing/details/information-protection)
- [<span data-ttu-id="7d19d-123">متطلبات حماية المعلومات اللازوردية</span><span class="sxs-lookup"><span data-stu-id="7d19d-123">Requirements for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/requirements)
- [<span data-ttu-id="7d19d-124">بدء سريع تعليمي لحماية المعلومات أزور</span><span class="sxs-lookup"><span data-stu-id="7d19d-124">Quick start tutorial for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/infoprotect-quick-start-tutorial)
- [<span data-ttu-id="7d19d-125">تحميل عميل حماية المعلومات Azure</span><span class="sxs-lookup"><span data-stu-id="7d19d-125">Download Azure Information Protection client</span></span>](https://www.microsoft.com/download/details.aspx?id=53018)