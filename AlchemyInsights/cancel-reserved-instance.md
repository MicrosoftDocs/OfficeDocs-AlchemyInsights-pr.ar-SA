---
title: إلغاء الحجز
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003552"
- "6817"
ms.openlocfilehash: 04875e33f07c6d0a4306b3579ef81f2d28c7f506
ms.sourcegitcommit: f8b41ecda6db0b8f64fe0c51f1e8e6619f504d61
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 10/28/2020
ms.locfileid: "48807178"
---
# <a name="cancelling-reservation"></a><span data-ttu-id="7c350-102">إلغاء الحجز</span><span class="sxs-lookup"><span data-stu-id="7c350-102">Cancelling Reservation</span></span>

- <span data-ttu-id="7c350-103">**الخدمة الذاتية:** يمكنك إلغاء مثيل محجوز أو exchange بنفسك باستخدام [مدخل Azure](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span><span class="sxs-lookup"><span data-stu-id="7c350-103">**Self-service:** You can cancel or exchange a reserved instance yourself using [Azure portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span></span> <span data-ttu-id="7c350-104">حدد الحجز وانقر فوق الاسترداد أو الصرف.</span><span class="sxs-lookup"><span data-stu-id="7c350-104">Select the reservation and click on refund or exchange.</span></span> <span data-ttu-id="7c350-105">لاحظ انه يجب ان يكون لديك حق الوصول إلى المالك في أمر الحجز للتبادل أو الاسترداد.</span><span class="sxs-lookup"><span data-stu-id="7c350-105">Note that you must have owner access on the Reservation Order to exchange or refund.</span></span> <span data-ttu-id="7c350-106">لن يسمح لك الوصول إلى الحجز الا بمتابعه الاسترداد أو الصرف.</span><span class="sxs-lookup"><span data-stu-id="7c350-106">Access to only the Reservation will not let you proceed with refund or exchange.</span></span> <span data-ttu-id="7c350-107">أسال مالك طلب الحجز بمنحك حق الوصول إلى طلب الحجز</span><span class="sxs-lookup"><span data-stu-id="7c350-107">Ask the Reservation Order owner to give you owner access to the Reservation Order</span></span>
- <span data-ttu-id="7c350-108">**نهج Exchange:** يمكنك تبادل حجز لحجز آخر من النوع نفسه-لا توجد **عقوبات** عند حجز exchange.</span><span class="sxs-lookup"><span data-stu-id="7c350-108">**Exchange policy:** You can exchange a reservation for another reservation of the same type – there are **no penalties** on reservation exchange.</span></span> <span data-ttu-id="7c350-109">يجب ان يكون إجمالي التزام بالحجز الجديد أكبر من مجموع قيمه المبلغ المسترد للحجز الذي تم تبادله والمدفوعات الشهرية المستقبلية (إذا كان ذلك ممكنا)</span><span class="sxs-lookup"><span data-stu-id="7c350-109">The total commitment with new reservation should be greater than the sum of exchanged reservation’s refund amount and the future monthly payments (if applicable)</span></span>
- <span data-ttu-id="7c350-110">**سياسة الاسترداد:** لا يمكن ان يتجاوز مجموع المبالغ المدفوعة والتي تم إلغاؤها المستقبلية $50,000 دولار في نافذه التداول لمده 12 شهرا.</span><span class="sxs-lookup"><span data-stu-id="7c350-110">**Refund policy:** Sum of refund and the cancelled future payments cannot exceed $50,000 USD in a 12-month rolling window.</span></span> <span data-ttu-id="7c350-111">لا نقوم **حاليا بشحن اي جزاءات** في المبالغ المستردة ، ولكنه قد يفرض عليها المبالغ المستردة المستقبلية</span><span class="sxs-lookup"><span data-stu-id="7c350-111">We are **currently not charging any penalty** on refunds but could charge it on future refunds</span></span>  
    <span data-ttu-id="7c350-112">**الاستثناءات:** لا تتوفر الميزات الذاتية لتبادل الخدمة وإلغاء لعملاء اتفاقيه المؤسسات الحكومية الامريكيه</span><span class="sxs-lookup"><span data-stu-id="7c350-112">**Exceptions:** Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers</span></span>
- <span data-ttu-id="7c350-113">لا يتوفر دعم **واجهه برمجه التطبيق (API)/PS/CLI** لعمليات إلغاء والاسترداد [الذاتي لعمليات الحجز والاسترداد المبالغ المستردة لحجوزات Azure](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="7c350-113">**API / PS / CLI** support is not available for cancellation and refunds [Self-service exchanges and refunds for Azure Reservations](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>
- <span data-ttu-id="7c350-114">لا تتوفر امكانيه تبادل الخدمة الذاتية وإلغاء لعملاء اتفاقيه المؤسسات الحكومية الامريكيه.</span><span class="sxs-lookup"><span data-stu-id="7c350-114">Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers.</span></span> <span data-ttu-id="7c350-115">أنواع اشتراكات الولايات المتحدة الامريكيه ، بما في ذلك الدفع بالمثل و CSP معتمده</span><span class="sxs-lookup"><span data-stu-id="7c350-115">Other US Government subscription types including Pay-As-You-Go and CSP are supported</span></span>

<span data-ttu-id="7c350-116">تعرف علي المزيد: [كيفيه معالجه حركات المرتجعات والتبادل](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed)</span><span class="sxs-lookup"><span data-stu-id="7c350-116">Learn more : [How return and exchange transactions are processed](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed)</span></span>  
<span data-ttu-id="7c350-117">تعرف علي [المزيد: سياسات Exchange و الاسترداد](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies)</span><span class="sxs-lookup"><span data-stu-id="7c350-117">Learn more : [Exchange and Refund policies](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies)</span></span>  
<span data-ttu-id="7c350-118">الاسئله الأخرى: [زيارة مستندات المثيل المحجوزة](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="7c350-118">Other questions: [Visit reserved instance docs](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="7c350-119">**Exchange مثيل محجوز موجود (خدمه ذاتية)**</span><span class="sxs-lookup"><span data-stu-id="7c350-119">**Exchange an existing reserved instance (Self-service)**</span></span>

<span data-ttu-id="7c350-120">يمكنك تبادل حجز لحجز آخر من النوع نفسه.</span><span class="sxs-lookup"><span data-stu-id="7c350-120">You can exchange a reservation for another reservation of the same type.</span></span> <span data-ttu-id="7c350-121">يمكنك أيضا استرداد مبلغ حجز حتى $50,000 دولار لكل عام ، إذا لم تعد بحاجه اليه.</span><span class="sxs-lookup"><span data-stu-id="7c350-121">You can also refund a reservation, up to $50,000 USD per year, if you no longer need it.</span></span> <span data-ttu-id="7c350-122">لا تتوفر امكانيه تبادل الخدمة الذاتية وإلغاء لعملاء اتفاقيه المؤسسات الحكومية الامريكيه.</span><span class="sxs-lookup"><span data-stu-id="7c350-122">Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers.</span></span> <span data-ttu-id="7c350-123">أنواع اشتراكات الولايات المتحدة الامريكيه ، بما في ذلك الدفع بالمثل و CSP معتمدين.</span><span class="sxs-lookup"><span data-stu-id="7c350-123">Other US Government subscription types including Pay-As-You-Go and CSP are supported.</span></span> <span data-ttu-id="7c350-124">يجب ان يتوفر لديك حق الوصول إلى المالك في أمر الحجز لتبادل الحجز الحالي أو استرداده.</span><span class="sxs-lookup"><span data-stu-id="7c350-124">You must have owner access on the Reservation Order to exchange or refund an existing reservation.</span></span>

<span data-ttu-id="7c350-125">سترشدك الخطوات التالية علي الاجراء لإكمال المعاملة</span><span class="sxs-lookup"><span data-stu-id="7c350-125">The following steps will guide on the procedure to complete the transaction</span></span>

1. <span data-ttu-id="7c350-126">سجل دخولك إلى [مدخل Azure](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span><span class="sxs-lookup"><span data-stu-id="7c350-126">Log in to your [Azure portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span></span> <span data-ttu-id="7c350-127">حدد الحجوزات التي تريد استردادها وانقر فوق **Exchange**</span><span class="sxs-lookup"><span data-stu-id="7c350-127">Select the reservations that you want to refund and click **Exchange**</span></span>
2. <span data-ttu-id="7c350-128">حدد منتج VM الذي تريد شراءه واكتب الكمية.</span><span class="sxs-lookup"><span data-stu-id="7c350-128">Select the VM product that you want to purchase and type a quantity.</span></span> <span data-ttu-id="7c350-129">تاكد من ان إجمالي الشراء الجديد أكبر من العدد الإجمالي الذي [يحدد الحجم الصحيح قبل الشراء](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy)</span><span class="sxs-lookup"><span data-stu-id="7c350-129">Make sure that the new purchase total is more than the return total [Determine the right size before you purchase](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy)</span></span>
3. <span data-ttu-id="7c350-130">مراجعه المعاملة وإكمالها</span><span class="sxs-lookup"><span data-stu-id="7c350-130">Review and complete the transaction</span></span>

<span data-ttu-id="7c350-131">**استرداد مثيل محجوز**</span><span class="sxs-lookup"><span data-stu-id="7c350-131">**Refund for a reserved instance**</span></span>

<span data-ttu-id="7c350-132">لاسترداد قيمه حجز ، انتقل إلى **تفاصيل الحجز** وانقر فوق **المبلغ المسترد**</span><span class="sxs-lookup"><span data-stu-id="7c350-132">To refund a reservation, go to **Reservation Details** and click **Refund**</span></span>

<span data-ttu-id="7c350-133">**المبلغ المسترد ل Pro:**</span><span class="sxs-lookup"><span data-stu-id="7c350-133">**Pro-rated refund:**</span></span>

<span data-ttu-id="7c350-134">**أمثله علي نسبه والحد الأدنى لمتطلبات المبالغ لاسترداد الأموال والتبادل**</span><span class="sxs-lookup"><span data-stu-id="7c350-134">**Pro-ration and minimum requirement examples for refund and exchange**</span></span>  
<span data-ttu-id="7c350-135">مثال لحجز توجد:</span><span class="sxs-lookup"><span data-stu-id="7c350-135">Upfront reservation example:</span></span>

- <span data-ttu-id="7c350-136">انك تشتري مصطلحا واحدا لمده عاما ل $120 في 1 يناير</span><span class="sxs-lookup"><span data-stu-id="7c350-136">You purchase a one-year term RI for $120 on January 1</span></span>
- <span data-ttu-id="7c350-137">في سابع ، لقد أردت استرداد مبلغ الحجز أو exchange</span><span class="sxs-lookup"><span data-stu-id="7c350-137">On April 7th you want to refund or exchange this reservation</span></span>
- <span data-ttu-id="7c350-138">نظرا لبقاء الحجز في غضون 97 يوما ، ستحصل علي (1-97/365) \* $120 مره أخرى.</span><span class="sxs-lookup"><span data-stu-id="7c350-138">Since the reservation has been live for 97 days, you will get (1-97/365) \* $120 back.</span></span> <span data-ttu-id="7c350-139">(علي سبيل المثال $88.1).</span><span class="sxs-lookup"><span data-stu-id="7c350-139">(i.e. $88.1).</span></span> <span data-ttu-id="7c350-140">لا توجد حاليا اي جزاءات في المبالغ المستردة</span><span class="sxs-lookup"><span data-stu-id="7c350-140">There is currently no penalty on refunds</span></span>
- <span data-ttu-id="7c350-141">إذا قمت بالتبادل ، فيجب ان تكون عمليه الشراء الجديدة أكبر من $88.1</span><span class="sxs-lookup"><span data-stu-id="7c350-141">If exchanging, your new purchase should be greater than $88.1</span></span>
- <span data-ttu-id="7c350-142">لا يوجد جزاءات في المبالغ المستردة حاليا</span><span class="sxs-lookup"><span data-stu-id="7c350-142">There is no penalty on refunds currently</span></span>

<span data-ttu-id="7c350-143">**مثال علي حجز خطه الفوترة:**</span><span class="sxs-lookup"><span data-stu-id="7c350-143">**Billing plan reservation example:**</span></span>

- <span data-ttu-id="7c350-144">ستشتري مصطلحا واحدا لمده عاما لمده $10 شهريا</span><span class="sxs-lookup"><span data-stu-id="7c350-144">You purchase a one-year term RI for $10 per month</span></span>
- <span data-ttu-id="7c350-145">في سابع ، لقد أردت استرداد مبلغ الحجز أو exchange</span><span class="sxs-lookup"><span data-stu-id="7c350-145">On April 7th you want to refund or exchange this reservation</span></span>
- <span data-ttu-id="7c350-146">منذ المرة الاخيره التي حدثت فيها الدفعة ، ستحصل علي (1-7/31) \* $10 مره أخرى.</span><span class="sxs-lookup"><span data-stu-id="7c350-146">Since the last payment happened 7 days, you will get (1-7/31) \* $10 back.</span></span> <span data-ttu-id="7c350-147">(علي سبيل المثال $7.74)</span><span class="sxs-lookup"><span data-stu-id="7c350-147">(i.e. $7.74)</span></span>
- <span data-ttu-id="7c350-148">المدفوعات المستقبلية التي تم إلغاؤها هي $80.</span><span class="sxs-lookup"><span data-stu-id="7c350-148">The future payments cancelled are $ 80.</span></span> <span data-ttu-id="7c350-149">لا توجد حاليا اي جزاءات في المبالغ المستردة</span><span class="sxs-lookup"><span data-stu-id="7c350-149">There is currently no penalty on refunds</span></span>
- <span data-ttu-id="7c350-150">سيؤدي هذا إلغاء إلى خصم $87.74 من ان الحد الأقصى لمبلغ الاسترداد هو $50,000</span><span class="sxs-lookup"><span data-stu-id="7c350-150">This cancellation will deduct $87.74 from you’re the $50,000 refund limit</span></span>
- <span data-ttu-id="7c350-151">إذا كان الأمر "تبادل" ، فيجب ان تكون القيمة الاجماليه لعمليه الشراء الجديدة أكبر من $87.74</span><span class="sxs-lookup"><span data-stu-id="7c350-151">If exchanging, the total value of new purchase should be greater than $87.74</span></span>

<span data-ttu-id="7c350-152">**المستندات المستحسنة**</span><span class="sxs-lookup"><span data-stu-id="7c350-152">**Recommended Documents**</span></span>

- [<span data-ttu-id="7c350-153">كيفيه معالجه حركات المرتجعات والتبادل</span><span class="sxs-lookup"><span data-stu-id="7c350-153">How return and exchange transactions are processed</span></span>](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed)
- [<span data-ttu-id="7c350-154">سياسات Exchange و الاسترداد</span><span class="sxs-lookup"><span data-stu-id="7c350-154">Exchange and Refund policies</span></span>](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies)