---
title: 添加 VPP 购买的应用
titleSuffix: Intune for Education
description: 了解如何将购买的 VPP 应用添加到 Intune for Education。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.openlocfilehash: 69af75f14afb144bfed01919b1cba65d34a440f2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146558"
---
# <a name="add-vpp-purchased-ios-apps-to-intune"></a><span data-ttu-id="2dd43-103">将 VPP 购买的 iOS 应用添加到 Intune</span><span class="sxs-lookup"><span data-stu-id="2dd43-103">Add VPP-purchased iOS apps to Intune</span></span>

<span data-ttu-id="2dd43-104">从 Intune for Education 门户添加 iOS Volume Purchase Program (VPP) 应用。</span><span class="sxs-lookup"><span data-stu-id="2dd43-104">Add Volume Purchase Program (VPP) iOS apps from the Intune for Education portal.</span></span> <span data-ttu-id="2dd43-105">本文介绍如何管理已同步到 Microsoft Intune 的 VPP 购买的应用。</span><span class="sxs-lookup"><span data-stu-id="2dd43-105">This article describes how to manage VPP-purchased apps that have been synced to Microsoft Intune.</span></span>

<span data-ttu-id="2dd43-106">免费和付费应用是可用于通过 App Store 批量购买。</span><span class="sxs-lookup"><span data-stu-id="2dd43-106">Both free and paid-for apps are available to buy in volume through the App Store.</span></span> <span data-ttu-id="2dd43-107">若要安装的免费 iOS 应用*而无需 VPP 令牌*，请参阅如何[在 Intune 中添加免费 iOS 应用](add-apps-ios.md)。</span><span class="sxs-lookup"><span data-stu-id="2dd43-107">To install free iOS apps *without a VPP token*, see how to [add free iOS apps in Intune](add-apps-ios.md).</span></span>  

## <a name="what-is-the-volume-purchase-program"></a><span data-ttu-id="2dd43-108">Volume Purchase Program 是什么？</span><span class="sxs-lookup"><span data-stu-id="2dd43-108">What is the Volume Purchase Program?</span></span>
<span data-ttu-id="2dd43-109">Apple Volume Purchase Program 可让组织购买应用许可证中大容量，并通过其移动设备管理器 (MDM) 管理它们。</span><span class="sxs-lookup"><span data-stu-id="2dd43-109">The Apple Volume Purchase Program lets organizations buy app licenses in bulk and manage them through their mobile device manager (MDM).</span></span> <span data-ttu-id="2dd43-110">与 MDM，如 Intune for Education，可以管理许可证的大小，然后以无提示方式将其部署到学生设备无线。</span><span class="sxs-lookup"><span data-stu-id="2dd43-110">With an MDM, such as Intune for Education, licenses can be managed and then silently deployed over-the-air to student devices.</span></span> <span data-ttu-id="2dd43-111">在教室和多个设备需要同一应用程序的位置的组织中的 VPP/MDM 合作关系是理想选择。</span><span class="sxs-lookup"><span data-stu-id="2dd43-111">A VPP/MDM partnership is ideal in classrooms and organizations where the same app is needed on many devices.</span></span> 

## <a name="before-you-begin"></a><span data-ttu-id="2dd43-112">在开始之前</span><span class="sxs-lookup"><span data-stu-id="2dd43-112">Before you begin</span></span>
<span data-ttu-id="2dd43-113">若要查看和管理许可证从 Intune for Education 门户，你首先必须：</span><span class="sxs-lookup"><span data-stu-id="2dd43-113">To view and manage licenses from the Intune for Education portal, you must first:</span></span>  
* <span data-ttu-id="2dd43-114">配置[VPP 令牌](setup-ios-device-management.md)。</span><span class="sxs-lookup"><span data-stu-id="2dd43-114">Configure a [VPP token](setup-ios-device-management.md).</span></span>
* <span data-ttu-id="2dd43-115">购买应用的 Apple VPP 供应商通过或通过 Apple School Manager > 应用商店应用和书籍。</span><span class="sxs-lookup"><span data-stu-id="2dd43-115">Purchase apps through an Apple VPP vendor or through the Apple School Manager > Apps and Books store.</span></span>
* <span data-ttu-id="2dd43-116">现有的传输购买许可证分配给相应的 Intune VPP 令牌。</span><span class="sxs-lookup"><span data-stu-id="2dd43-116">Transfer existing purchased licenses to the appropriate Intune VPP token.</span></span> <span data-ttu-id="2dd43-117">请参阅[Apple 教育支持站点](https://support.apple.com/education)若要了解如何传送许可证。</span><span class="sxs-lookup"><span data-stu-id="2dd43-117">See the [Apple education support site](https://support.apple.com/education) to learn how to transfer licenses.</span></span> 

## <a name="search-and-add-apps"></a><span data-ttu-id="2dd43-118">搜索并添加应用</span><span class="sxs-lookup"><span data-stu-id="2dd43-118">Search and add apps</span></span>
<span data-ttu-id="2dd43-119">完成以下步骤以搜索并添加付费的 iOS 应用从 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="2dd43-119">Complete the following steps to search and add paid-for iOS apps from the Intune for Education portal.</span></span> 

<span data-ttu-id="2dd43-120">免费的应用程序都可直接从门户购买。</span><span class="sxs-lookup"><span data-stu-id="2dd43-120">Free apps are made available for purchase directly from the portal.</span></span> <span data-ttu-id="2dd43-121">但是，这些应用程序都可用，以便 VPP 帐户的情况下用户可以轻松地获取它们。</span><span class="sxs-lookup"><span data-stu-id="2dd43-121">However, these apps are made available so that users without a VPP account can easily get them.</span></span> <span data-ttu-id="2dd43-122">如果你打算将免费的应用程序以无提示方式和在卷部署到您的学校的设备，应通过 Apple VPP 或 Apple School Manager 网站进行购买。</span><span class="sxs-lookup"><span data-stu-id="2dd43-122">If you plan to deploy free apps silently and in volume to your school's devices, you should purchase them through the Apple VPP or Apple School Manager websites.</span></span>

1. <span data-ttu-id="2dd43-123">登录到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="2dd43-123">Sign in to the Intune for Education portal.</span></span>
2. <span data-ttu-id="2dd43-124">单击“应用”。</span><span class="sxs-lookup"><span data-stu-id="2dd43-124">Click **Apps**.</span></span>
3. <span data-ttu-id="2dd43-125">从应用列表中下, **iOS 应用**，单击**新的应用程序**。</span><span class="sxs-lookup"><span data-stu-id="2dd43-125">From the app list, under **iOS Apps**, click **New app**.</span></span>
4. <span data-ttu-id="2dd43-126">从您打算在其中购买应用程序中选择国家/地区。</span><span class="sxs-lookup"><span data-stu-id="2dd43-126">Select the country from where you're purchasing the app.</span></span>
5. <span data-ttu-id="2dd43-127">键入应用程序的完整或部分名称。</span><span class="sxs-lookup"><span data-stu-id="2dd43-127">Type in the app's full or partial name.</span></span> <span data-ttu-id="2dd43-128">Intune 从应用商店中返回相关结果的列表。</span><span class="sxs-lookup"><span data-stu-id="2dd43-128">Intune returns a list of relevant results from the App Store.</span></span> 
6. <span data-ttu-id="2dd43-129">选择的应用。</span><span class="sxs-lookup"><span data-stu-id="2dd43-129">Select the app.</span></span> 
7. <span data-ttu-id="2dd43-130">一条消息出现，提示你完成购买通过 Apple School Manager。</span><span class="sxs-lookup"><span data-stu-id="2dd43-130">A message appears that prompts you to complete your purchase through Apple School Manager.</span></span> <span data-ttu-id="2dd43-131">单击链接以转到 Apple School Manager。</span><span class="sxs-lookup"><span data-stu-id="2dd43-131">Click the link to go to Apple School Manager.</span></span>
8. <span data-ttu-id="2dd43-132">按照完成购买的 Apple School Manager 中的步骤。</span><span class="sxs-lookup"><span data-stu-id="2dd43-132">Follow the steps in Apple School Manager to complete your purchase.</span></span> <span data-ttu-id="2dd43-133">系统将提示您要将你的许可证分配到相应的位置。</span><span class="sxs-lookup"><span data-stu-id="2dd43-133">You'll be prompted to assign your licenses to the appropriate location.</span></span>
9. <span data-ttu-id="2dd43-134">返回到 Intune for Education >**应用**。</span><span class="sxs-lookup"><span data-stu-id="2dd43-134">Return to Intune for Education > **Apps**.</span></span> <span data-ttu-id="2dd43-135">您的应用程序将出现在**iOS 应用**列表。</span><span class="sxs-lookup"><span data-stu-id="2dd43-135">Your app will appear in the **iOS Apps** list.</span></span> <span data-ttu-id="2dd43-136">如果没有立即看到它，等待几分钟并刷新页面。</span><span class="sxs-lookup"><span data-stu-id="2dd43-136">If you don't see it right away, wait a few minutes and refresh your page.</span></span>

### <a name="view-app-details"></a><span data-ttu-id="2dd43-137">查看应用详细信息</span><span class="sxs-lookup"><span data-stu-id="2dd43-137">View app details</span></span>
<span data-ttu-id="2dd43-138">应用在应用程序列表中，在出现**iOS 应用**。</span><span class="sxs-lookup"><span data-stu-id="2dd43-138">Apps appear in the app list, under **iOS Apps**.</span></span> <span data-ttu-id="2dd43-139">单击应用程序以查看其：</span><span class="sxs-lookup"><span data-stu-id="2dd43-139">Click the app to view its:</span></span>

* <span data-ttu-id="2dd43-140">**概述**：列出了应用程序名称、 发布者和日期添加到 Intune。</span><span class="sxs-lookup"><span data-stu-id="2dd43-140">**Overview**: Lists app name, publisher, and date you added it to Intune.</span></span> <span data-ttu-id="2dd43-141">此外列出了可供分配的许可证数目。</span><span class="sxs-lookup"><span data-stu-id="2dd43-141">Also lists the number of licenses available to assign.</span></span>
* <span data-ttu-id="2dd43-142">**组**：列出所有分配有该应用的组。</span><span class="sxs-lookup"><span data-stu-id="2dd43-142">**Groups**: Lists all groups that are assigned the app.</span></span> <span data-ttu-id="2dd43-143">更改组分配给或转到特定组的详细信息页。</span><span class="sxs-lookup"><span data-stu-id="2dd43-143">Change group assignments here or go to the details page for a specific group.</span></span>
* <span data-ttu-id="2dd43-144">**安装状态**:显示有关应用程序的安装，如已分配给设备的详细信息。</span><span class="sxs-lookup"><span data-stu-id="2dd43-144">**Install status**: Shows details about the app's installation, such as the device it was assigned to.</span></span> <span data-ttu-id="2dd43-145">上次签入的时间和安装是否成功、 失败还是仍正在进行中，还列出了状态。</span><span class="sxs-lookup"><span data-stu-id="2dd43-145">The status also lists last check-in time and if the installation was a success, failure, or still-in-progress.</span></span>

## <a name="reassign-vpp-purchased-licenses"></a><span data-ttu-id="2dd43-146">重新分配 VPP 购买的许可证</span><span class="sxs-lookup"><span data-stu-id="2dd43-146">Reassign VPP-purchased licenses</span></span>
<span data-ttu-id="2dd43-147">无法从 Intune for Education 删除 VPP 购买的应用。</span><span class="sxs-lookup"><span data-stu-id="2dd43-147">VPP-purchased apps can't be deleted from Intune for Education.</span></span> <span data-ttu-id="2dd43-148">但是，可以从已分配组中删除用户或从分配中删除整个组。</span><span class="sxs-lookup"><span data-stu-id="2dd43-148">However, you can remove a user from an assigned group, or remove the entire group from assignment.</span></span>  

