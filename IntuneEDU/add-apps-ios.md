---
title: 从 iOS 应用商店添加免费的应用程序
titleSuffix: Intune for Education
description: 了解如何从 iOS 应用商店的免费应用程序添加到 Intune for Education。
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
ms.openlocfilehash: 4d17b0d12758dc781fa89f522f07ace5247cdc2e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145894"
---
# <a name="add-free-ios-apps-to-intune-for-education"></a><span data-ttu-id="930fc-103">向 Intune for Education 添加免费 iOS 应用</span><span class="sxs-lookup"><span data-stu-id="930fc-103">Add free iOS apps to Intune for Education</span></span>  
<span data-ttu-id="930fc-104">搜索并将从 iOS 应用商店的免费应用添加到你的应用程序清单。</span><span class="sxs-lookup"><span data-stu-id="930fc-104">Search for and add free apps from the iOS App Store to your app inventory.</span></span> <span data-ttu-id="930fc-105">本文介绍如何购买免费 iOS 应用，以便可以查看并将其分配 Intune for Education 门户中。</span><span class="sxs-lookup"><span data-stu-id="930fc-105">This article describes how to purchase free iOS apps so that you can view and assign them in the Intune for Education portal.</span></span>
 
<span data-ttu-id="930fc-106">说明仅适用于应用被列为**免费**应用商店中。</span><span class="sxs-lookup"><span data-stu-id="930fc-106">Instructions apply only to apps that are listed as **Free** in the App Store.</span></span> <span data-ttu-id="930fc-107">若要添加的付费应用，请参阅本文中，[添加 VPP 购买的 iOS 应用到 Intune](add-vpp-apps-ios.md)。</span><span class="sxs-lookup"><span data-stu-id="930fc-107">To add a paid-for app, see the article, [Add VPP-purchased iOS apps to Intune](add-vpp-apps-ios.md).</span></span>

## <a name="recommendation-set-up-vpp-token"></a><span data-ttu-id="930fc-108">建议：设置 VPP 令牌</span><span class="sxs-lookup"><span data-stu-id="930fc-108">Recommendation: Set up VPP token</span></span>

<span data-ttu-id="930fc-109">不需要 VPP 令牌，以安装免费的应用程序，但我们建议使用它。</span><span class="sxs-lookup"><span data-stu-id="930fc-109">You do not need a VPP token to install free apps, but we recommended it.</span></span> <span data-ttu-id="930fc-110">VPP 令牌允许您购买的所有应用-免费和付费-通过 VPP 应用商店。</span><span class="sxs-lookup"><span data-stu-id="930fc-110">A VPP token permits you to purchase all apps--free and paid--through the VPP store.</span></span> <span data-ttu-id="930fc-111">Intune 以无提示方式安装 VPP 购买的应用在设备上，并且不需要 Apple ID 进行身份验证。</span><span class="sxs-lookup"><span data-stu-id="930fc-111">Intune silently installs VPP-purchased apps on devices, and does not require an Apple ID to authenticate.</span></span>  

<span data-ttu-id="930fc-112">如果您选择不使用 VPP 令牌购买您的应用程序，将只能够管理 Intune for Education 中的免费应用程序。</span><span class="sxs-lookup"><span data-stu-id="930fc-112">If you choose not to use a VPP token to purchase your app, you will only be able to manage free apps in the Intune for Education.</span></span> <span data-ttu-id="930fc-113">设备用户还需要使用安装分配应用到 Apple ID 登录。</span><span class="sxs-lookup"><span data-stu-id="930fc-113">The device user will also need to sign in with an Apple ID to install assigned apps.</span></span>

## <a name="add-new-ios-app"></a><span data-ttu-id="930fc-114">添加新的 iOS 应用</span><span class="sxs-lookup"><span data-stu-id="930fc-114">Add new iOS app</span></span>
<span data-ttu-id="930fc-115">完成以下步骤以将 iOS 应用添加到 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="930fc-115">Complete the following steps to add an iOS app to Intune for Education.</span></span>
1. <span data-ttu-id="930fc-116">登录到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="930fc-116">Sign in to the Intune for Education portal.</span></span>
2. <span data-ttu-id="930fc-117">单击“应用”。</span><span class="sxs-lookup"><span data-stu-id="930fc-117">Click **Apps**.</span></span>
3. <span data-ttu-id="930fc-118">在左窗格中下, **IOS 应用**，单击**新的应用程序**。</span><span class="sxs-lookup"><span data-stu-id="930fc-118">In the left pane, under **IOS APPS**, click **New app**.</span></span>
5. <span data-ttu-id="930fc-119">在搜索框中，键入应用的完整或部分名称。</span><span class="sxs-lookup"><span data-stu-id="930fc-119">In the search box, type the full or partial name of an app.</span></span>
6. <span data-ttu-id="930fc-120">选择应用程序，然后单击**保存**将应用添加到 Intune 清单。</span><span class="sxs-lookup"><span data-stu-id="930fc-120">Select the app and click **Save** to add the app to your Intune inventory.</span></span>

## <a name="view-app-details-in-intune-for-education"></a><span data-ttu-id="930fc-121">Intune for Education 中查看应用详细信息</span><span class="sxs-lookup"><span data-stu-id="930fc-121">View app details in Intune for Education</span></span>
<span data-ttu-id="930fc-122">添加应用程序在应用程序列表中，在出现**iOS 应用商店**。</span><span class="sxs-lookup"><span data-stu-id="930fc-122">Added apps appear in the app list, under **iOS store**.</span></span> <span data-ttu-id="930fc-123">单击应用程序以查看其：</span><span class="sxs-lookup"><span data-stu-id="930fc-123">Click the app to view its:</span></span>

* <span data-ttu-id="930fc-124">**概述**：列出了应用程序名称、 发布者和日期添加到 Intune。</span><span class="sxs-lookup"><span data-stu-id="930fc-124">**Overview**: Lists app name, publisher, and date you added it to Intune.</span></span> <span data-ttu-id="930fc-125">单击要查看在 iTunes 中的应用的应用名称。</span><span class="sxs-lookup"><span data-stu-id="930fc-125">Click the app name to see the app in iTunes.</span></span>
* <span data-ttu-id="930fc-126">**组**：列出所有分配有该应用的组。</span><span class="sxs-lookup"><span data-stu-id="930fc-126">**Groups**: Lists all groups that are assigned the app.</span></span> <span data-ttu-id="930fc-127">更改组分配给或转到特定组的详细信息页。</span><span class="sxs-lookup"><span data-stu-id="930fc-127">Change group assignments here or go to the details page for a specific group.</span></span>
* <span data-ttu-id="930fc-128">**安装状态**:显示有关应用程序的安装，如已分配给设备的详细信息。</span><span class="sxs-lookup"><span data-stu-id="930fc-128">**Install status**: Shows details about the app's installation, such as the device it was assigned to.</span></span> <span data-ttu-id="930fc-129">上次签入的时间和安装是否成功、 失败还是仍正在进行中，还列出了状态。</span><span class="sxs-lookup"><span data-stu-id="930fc-129">The status also lists last check-in time and if the installation was a success, failure, or still-in-progress.</span></span>  
