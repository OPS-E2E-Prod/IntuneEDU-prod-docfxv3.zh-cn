---
title: 如何安装应用？
titleSuffix: Intune for Education
description: 了解如何使用 Intune for Education 管理的应用。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 635a5cc7-7dd4-45f9-9b18-3eddb76d0c74
searchScope:
- IntuneEDU
ms.openlocfilehash: 260679748d8ddb891d042abd6e0d7d0f5f698b34
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146512"
---
# <a name="installing-apps-on-school-devices"></a><span data-ttu-id="60dba-103">在学校设备上安装应用</span><span class="sxs-lookup"><span data-stu-id="60dba-103">Installing apps on school devices</span></span>

<span data-ttu-id="60dba-104">若要在学校设备上安装的应用，必须首先将其分配给一个组。</span><span class="sxs-lookup"><span data-stu-id="60dba-104">To install an app on a school device, you have to first assign it to a group.</span></span> <span data-ttu-id="60dba-105">本文介绍三种方法可以将应用分配到学生教师。</span><span class="sxs-lookup"><span data-stu-id="60dba-105">This article describes three ways to assign apps to student teachers.</span></span>  

<span data-ttu-id="60dba-106">分配应用后，应用程序发送到相应的设备。</span><span class="sxs-lookup"><span data-stu-id="60dba-106">After you assign an app, the app is sent to the appropriate device.</span></span> <span data-ttu-id="60dba-107">在设备签入到 Intune for Education 时启动应用程序安装。</span><span class="sxs-lookup"><span data-stu-id="60dba-107">App installation is initiated when the device checks in to Intune for Education.</span></span> 

## <a name="add-apps-to-intune-for-education-inventory"></a><span data-ttu-id="60dba-108">将应用添加到 Intune 教育版清单</span><span class="sxs-lookup"><span data-stu-id="60dba-108">Add apps to Intune for Education inventory</span></span>
<span data-ttu-id="60dba-109">默认情况下，受欢迎的应用是 Intune for Education 中可用于直接分配。</span><span class="sxs-lookup"><span data-stu-id="60dba-109">By default, popular apps are available in Intune for Education for immediate assignment.</span></span> <span data-ttu-id="60dba-110">如果想要分配的应用不在你的清单，了解如何将其添加到 Intune for Education 与以下文章之一：</span><span class="sxs-lookup"><span data-stu-id="60dba-110">If the app you want to assign isn't in your inventory, learn how to add it to Intune for Education with one of the following articles:</span></span>
* [<span data-ttu-id="60dba-111">Microsoft Store for Education 的应用</span><span class="sxs-lookup"><span data-stu-id="60dba-111">Microsoft Store for Education apps</span></span>](acquire-store-apps.md)
* [<span data-ttu-id="60dba-112">免费 iOS App Store 应用</span><span class="sxs-lookup"><span data-stu-id="60dba-112">Free iOS App Store apps</span></span>](add-apps-ios.md)
* [<span data-ttu-id="60dba-113">iOS VPP 应用</span><span class="sxs-lookup"><span data-stu-id="60dba-113">iOS VPP apps</span></span>](add-vpp-apps-ios.md)
* [<span data-ttu-id="60dba-114">Windows 10 桌面应用程序</span><span class="sxs-lookup"><span data-stu-id="60dba-114">Windows 10 desktop apps</span></span>](add-desktop-apps-edu.md)
* [<span data-ttu-id="60dba-115">Web 应用</span><span class="sxs-lookup"><span data-stu-id="60dba-115">Web apps</span></span>](add-web-apps-edu.md)  

## <a name="assign-apps-with-express-configuration"></a><span data-ttu-id="60dba-116">分配应用快速配置</span><span class="sxs-lookup"><span data-stu-id="60dba-116">Assign apps with Express Configuration</span></span>
<span data-ttu-id="60dba-117">转到[快速配置](Express-configuration-intune-edu.md)将多个应用分配给单个组。</span><span class="sxs-lookup"><span data-stu-id="60dba-117">Go to [express configuration](Express-configuration-intune-edu.md) to assign multiple apps to a single group.</span></span> 

1. <span data-ttu-id="60dba-118">从 Intune for Education 仪表板，单击**快速配置**。</span><span class="sxs-lookup"><span data-stu-id="60dba-118">From the Intune for Education dashboard, click **Express Configuration**.</span></span>  
2. <span data-ttu-id="60dba-119">选择你想要将应用添加到的组。</span><span class="sxs-lookup"><span data-stu-id="60dba-119">Choose the group you want to add apps to.</span></span> <span data-ttu-id="60dba-120">然后单击“下一步” 。</span><span class="sxs-lookup"><span data-stu-id="60dba-120">Then click **Next**.</span></span>
3. <span data-ttu-id="60dba-121">选择要部署到你的组的一个或多个应用。</span><span class="sxs-lookup"><span data-stu-id="60dba-121">Choose one or more apps to deploy to your group.</span></span> <span data-ttu-id="60dba-122">然后单击“下一步” 。</span><span class="sxs-lookup"><span data-stu-id="60dba-122">Then click **Next**.</span></span> 
4. <span data-ttu-id="60dba-123">应用将自动分配给你的组。</span><span class="sxs-lookup"><span data-stu-id="60dba-123">The apps will automatically be assigned to your group.</span></span> <span data-ttu-id="60dba-124">继续完成快速配置。</span><span class="sxs-lookup"><span data-stu-id="60dba-124">Continue through express configuration.</span></span>

##  <a name="assign-apps-to-a-single-group"></a><span data-ttu-id="60dba-125">将应用分配到一个组</span><span class="sxs-lookup"><span data-stu-id="60dba-125">Assign apps to a single group</span></span>
<span data-ttu-id="60dba-126">选择一个组和一个或多个应用安装到该组中的设备。</span><span class="sxs-lookup"><span data-stu-id="60dba-126">Select a group and install one or more apps to the devices in that group.</span></span>

1. <span data-ttu-id="60dba-127">从 Intune for Education 仪表板，单击**组**。</span><span class="sxs-lookup"><span data-stu-id="60dba-127">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="60dba-128">选择你想要部署到应用的组。</span><span class="sxs-lookup"><span data-stu-id="60dba-128">Choose the groups you want to deploy the apps to.</span></span>
3. <span data-ttu-id="60dba-129">转到在顶部的任务栏，单击**应用**若要查看可用的应用列表。</span><span class="sxs-lookup"><span data-stu-id="60dba-129">Go to the task bar at the top and click **Apps** to see a list of available apps.</span></span>  
4. <span data-ttu-id="60dba-130">选择要部署到你的组的一个或多个应用。</span><span class="sxs-lookup"><span data-stu-id="60dba-130">Choose one or more apps to deploy to your group.</span></span> 
5. <span data-ttu-id="60dba-131">选择**保存**将所选的应用部署到该组。</span><span class="sxs-lookup"><span data-stu-id="60dba-131">Choose **Save** to deploy the selected apps to that group.</span></span> <span data-ttu-id="60dba-132">设备检查入到 Intune for Education 的下一个时间，将自动开始安装。</span><span class="sxs-lookup"><span data-stu-id="60dba-132">Installation will automatically begin the next time the device checks-in to Intune for Education.</span></span>  

## <a name="asign-apps-to-multiple-groups"></a><span data-ttu-id="60dba-133">Asign 应用到多个组</span><span class="sxs-lookup"><span data-stu-id="60dba-133">Asign apps to multiple groups</span></span>
<span data-ttu-id="60dba-134">选择一个应用并将其分配给一个或多个组进行安装。</span><span class="sxs-lookup"><span data-stu-id="60dba-134">Select an app and assign it to one or more groups for installation.</span></span>

1. <span data-ttu-id="60dba-135">从 Intune for Education 仪表板，单击**应用**。</span><span class="sxs-lookup"><span data-stu-id="60dba-135">From the Intune for Education dashboard, click **Apps**.</span></span>
2. <span data-ttu-id="60dba-136">从左侧上的应用列表中，选择想要分配的应用。</span><span class="sxs-lookup"><span data-stu-id="60dba-136">From the list of apps on the left, choose the app you want to assign.</span></span>
3. <span data-ttu-id="60dba-137">转到在顶部的任务栏，单击**组** > **更改组分配**。</span><span class="sxs-lookup"><span data-stu-id="60dba-137">Go to the task bar at the top and click **Groups** > **Change group assignments**.</span></span> 
4. <span data-ttu-id="60dba-138">选择你想要分配到应用的组。</span><span class="sxs-lookup"><span data-stu-id="60dba-138">Choose the groups you want to assign the app to.</span></span>  
