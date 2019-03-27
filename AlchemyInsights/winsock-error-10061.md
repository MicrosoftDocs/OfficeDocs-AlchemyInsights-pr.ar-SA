---
title: خطأ Winsock 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ar-SA
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772429"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="092d8-102">خطأ Winsock 10061</span><span class="sxs-lookup"><span data-stu-id="092d8-102">Winsock error 10061</span></span>

<span data-ttu-id="092d8-103">رمز الخطأ هذا يعني أن Office 365 تعذر إنشاء مأخذ توصيل TCP (اتصال) مع المضيف الهدف.</span><span class="sxs-lookup"><span data-stu-id="092d8-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="092d8-104">السبب المحتمل لهذا الخطأ مشكلة في تكوين جدار الحماية الخاص بك.</span><span class="sxs-lookup"><span data-stu-id="092d8-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="092d8-105">لحل هذه المشكلة، تحقق من هذه الإعدادات:</span><span class="sxs-lookup"><span data-stu-id="092d8-105">To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="092d8-106">تحقق من تكوين جدار الحماية الخاص بك باستخدام المعلومات الموجودة في [Office 365 URLs ونطاقات عناوين IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="092d8-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="092d8-107">إذا كان الخطأ خاص إلى Exchange عبر إنترنت الحماية (البرنامج)، قد يجب أن تم مسبقاً إعلامك لتغيير [عناوين IP في حماية Exchange عبر إنترنت](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="092d8-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="092d8-108">تأكد من أن موفر خدمة إنترنت (ISP) لا يقوم بحظر المنفذ.</span><span class="sxs-lookup"><span data-stu-id="092d8-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="092d8-109">تحقق من إعدادات الخادم المضيف والهدف الذكية في الموصلات.</span><span class="sxs-lookup"><span data-stu-id="092d8-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="092d8-110">لاحظ أن Office 365 لا منع الاتصالات *الواردة* على هذا النحو.</span><span class="sxs-lookup"><span data-stu-id="092d8-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  
