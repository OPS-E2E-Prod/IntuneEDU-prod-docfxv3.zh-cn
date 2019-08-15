---
title: 组设置有哪些？
titleSuffix: Intune for Education
description: 了解如何通过管理设置 Intune 教育版策略。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.openlocfilehash: 998b207bdfc0f8d48cd7eddff3020d00673377a2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145966"
---
# <a name="what-are-group-settings"></a><span data-ttu-id="73f61-103">组设置有哪些？</span><span class="sxs-lookup"><span data-stu-id="73f61-103">What are group settings?</span></span>

<span data-ttu-id="73f61-104">配置组设置以管理学生、 教师，以及设备在您的学校中的工作原理。</span><span class="sxs-lookup"><span data-stu-id="73f61-104">Configure group settings to manage how students, teachers, and devices work in your school.</span></span>

<span data-ttu-id="73f61-105">设置分配给用户，将按照无论他们使用哪些设备的用户。</span><span class="sxs-lookup"><span data-stu-id="73f61-105">Settings that you assign to users, will follow the users no matter what devices they use.</span></span> <span data-ttu-id="73f61-106">同样，你将分配给设备的设置将遵循的设备，无论使用者。</span><span class="sxs-lookup"><span data-stu-id="73f61-106">Similarly, settings that you assign to devices,will follow the devices, no matter who uses them.</span></span>

<span data-ttu-id="73f61-107">设置应用于组中。</span><span class="sxs-lookup"><span data-stu-id="73f61-107">Settings are applied to groups.</span></span> <span data-ttu-id="73f61-108">因为组将设置为层次结构，与上面另一个组任何[设置应用于组及其所有子组由继承](settings-inheritance.md)。</span><span class="sxs-lookup"><span data-stu-id="73f61-108">Since groups are set up as hierarchies, with one group above another, any [settings applied to a group are inherited by all of its subgroups](settings-inheritance.md).</span></span> <span data-ttu-id="73f61-109">继承使得更轻松地将设置应用于用户、 应用和设备的大规模群体。</span><span class="sxs-lookup"><span data-stu-id="73f61-109">Inheritance makes it easier to apply settings to large groups of users, apps, and devices.</span></span>  

<span data-ttu-id="73f61-110">有两种方法来管理 Intune for Education 中的组设置：</span><span class="sxs-lookup"><span data-stu-id="73f61-110">There are two ways to manage group settings in Intune for Education:</span></span>  

* <span data-ttu-id="73f61-111">__快速配置__:配置最常使用的学校设置的选择。</span><span class="sxs-lookup"><span data-stu-id="73f61-111">__Express configuration__: Configure a selection of the most commonly used school settings.</span></span> <span data-ttu-id="73f61-112">[快速配置](Express-configuration-intune-edu.md)是可帮助你选择和分配组设置的演练样式设置快速。</span><span class="sxs-lookup"><span data-stu-id="73f61-112">[Express configuration](Express-configuration-intune-edu.md) is a walkthrough-style setup that helps you select and assign group settings quickly.</span></span> <span data-ttu-id="73f61-113">设置为 Microsoft 建议的值进行了预配置，但可以更改以适应您的学校的策略。</span><span class="sxs-lookup"><span data-stu-id="73f61-113">Settings are preconfigured to Microsoft-recommended values but can be changed to fit your school's policies.</span></span> 

* <span data-ttu-id="73f61-114">__组__：配置设备或用户的任何组的所有设置。</span><span class="sxs-lookup"><span data-stu-id="73f61-114">__Groups__: Configure all settings for any group of devices or users.</span></span> <span data-ttu-id="73f61-115">在中**组**选项卡上，将看到在门户中的可用设置的完整列表。</span><span class="sxs-lookup"><span data-stu-id="73f61-115">In the **Groups** tab, you'll see the full list of settings available in the portal.</span></span> <span data-ttu-id="73f61-116">请参阅是可用于设置[Windows](all-edu-settings-windows.md)和有关[iOS](all-edu-settings-ios.md)组。</span><span class="sxs-lookup"><span data-stu-id="73f61-116">See are the settings available for [Windows](all-edu-settings-windows.md) and for [iOS](all-edu-settings-ios.md) groups.</span></span>  

## <a name="configure-express-configuration-settings"></a><span data-ttu-id="73f61-117">配置快速配置设置</span><span class="sxs-lookup"><span data-stu-id="73f61-117">Configure express configuration settings</span></span>  

<span data-ttu-id="73f61-118">可以是快速配置时使用：</span><span class="sxs-lookup"><span data-stu-id="73f61-118">Express configuration can be used when:</span></span>
* <span data-ttu-id="73f61-119">您只需在门户中开始。</span><span class="sxs-lookup"><span data-stu-id="73f61-119">You're just getting started in the portal.</span></span>
* <span data-ttu-id="73f61-120">你一直在使用它一段时间，并想要进行快速更改。</span><span class="sxs-lookup"><span data-stu-id="73f61-120">You've been using it for a while and want to make quick changes.</span></span>   

<span data-ttu-id="73f61-121">快速配置步骤的详细信息，请参阅[快速配置 Intune for Education 中的](Express-configuration-intune-edu.md)。</span><span class="sxs-lookup"><span data-stu-id="73f61-121">For a detailed look at the express configuration steps, see [Express configuration in Intune for Education](Express-configuration-intune-edu.md).</span></span>

  ![快速配置设置解决](./media/express-config-006-choose-settings.png)  

## <a name="configure-settings-in-groups"></a><span data-ttu-id="73f61-123">在组中配置设置</span><span class="sxs-lookup"><span data-stu-id="73f61-123">Configure settings in Groups</span></span>

<span data-ttu-id="73f61-124">以下步骤介绍如何将从设置分配**组**Intune for Education 中的页。</span><span class="sxs-lookup"><span data-stu-id="73f61-124">The following steps describe how to assign settings from the **Groups** page in Intune for Education.</span></span> <span data-ttu-id="73f61-125">从此页中，您将看到设备限制和功能的完整列表。</span><span class="sxs-lookup"><span data-stu-id="73f61-125">From this page, you'll see the complete list of device restrictions and features.</span></span>  
1. <span data-ttu-id="73f61-126">从 Intune for Education 仪表板，单击**组**。</span><span class="sxs-lookup"><span data-stu-id="73f61-126">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="73f61-127">选择你想要配置的组。</span><span class="sxs-lookup"><span data-stu-id="73f61-127">Select the group you want to configure.</span></span>
3. <span data-ttu-id="73f61-128">单击**设置**若要查看可用的设置的完整列表。</span><span class="sxs-lookup"><span data-stu-id="73f61-128">Click **Settings** to view the full list of available settings.</span></span>
4. <span data-ttu-id="73f61-129">展开每个类别可修改各种设置的所选组。</span><span class="sxs-lookup"><span data-stu-id="73f61-129">Expand each category to modify individual settings for the selected group.</span></span>
5. <span data-ttu-id="73f61-130">完成后，单击“保存”。</span><span class="sxs-lookup"><span data-stu-id="73f61-130">When you're done, click **Save**.</span></span> <span data-ttu-id="73f61-131">在组中的所有设备上自动更新设置。</span><span class="sxs-lookup"><span data-stu-id="73f61-131">Settings are automatically updated on all devices in the group.</span></span>  

## <a name="can-i-ever-have-settings-that-dont-work-together"></a><span data-ttu-id="73f61-132">我曾经可以使用不能同时使用的设置？</span><span class="sxs-lookup"><span data-stu-id="73f61-132">Can I ever have settings that don't work together?</span></span>

<span data-ttu-id="73f61-133">很可能不兼容的设置应用于同一个组。</span><span class="sxs-lookup"><span data-stu-id="73f61-133">It is possible for incompatible settings to be applied to the same group.</span></span> <span data-ttu-id="73f61-134">这些不一致会导致错误，用户或设备正在设置时使用不同的设置在多个位置。</span><span class="sxs-lookup"><span data-stu-id="73f61-134">These inconsistences result in errors, when a user or device is being set up with different settings in multiple places.</span></span> <span data-ttu-id="73f61-135">当用户或设备成员属于多个组时，会发生冲突。</span><span class="sxs-lookup"><span data-stu-id="73f61-135">Conflicts happen when user or device members belong to more than one group.</span></span>

<span data-ttu-id="73f61-136">例如，Esperanza 是的成员*第六级*组，也称为组的成员*地球科学*。</span><span class="sxs-lookup"><span data-stu-id="73f61-136">For example, Esperanza is a member of the *6th Grade* group and is also a member of group called *Earth Science*.</span></span> <span data-ttu-id="73f61-137">如果配置主页设置，并将分配给*第 6 个等级*，并配置不同的主页设置并将其分配给*地球科学*，Esperanza 现在具有两个冲突的主页设置分配对她。</span><span class="sxs-lookup"><span data-stu-id="73f61-137">If you configure a homepage setting and assign to *6th Grade*, and you configure a different homepage setting and assign it to *Earth Science*, Esperanza now has two conflicting homepage settings assigned to her.</span></span> <span data-ttu-id="73f61-138">不一致的设置赋值将导致错误。</span><span class="sxs-lookup"><span data-stu-id="73f61-138">The inconsistent setting assignment leads to an error.</span></span> <span data-ttu-id="73f61-139">若要解决此问题，你想要查看组[设置错误报表](what-are-reports.md)。</span><span class="sxs-lookup"><span data-stu-id="73f61-139">To fix this, you'd want to look at the group [settings errors report](what-are-reports.md).</span></span>  

## <a name="next-steps"></a><span data-ttu-id="73f61-140">后续步骤</span><span class="sxs-lookup"><span data-stu-id="73f61-140">Next steps</span></span>
<span data-ttu-id="73f61-141">[创建用户和设备组](what-are-groups.md)Intune for Education 中，以便可以开始配置其设置。</span><span class="sxs-lookup"><span data-stu-id="73f61-141">[Create user and device groups](what-are-groups.md) in Intune for Education so that you can start configuring their settings.</span></span>  

[<span data-ttu-id="73f61-142">了解有关如何保护应用和数据与 Intune 中的完整管理体验的详细信息</span><span class="sxs-lookup"><span data-stu-id="73f61-142">Find out more about how to protect apps and data with the full management experience in Intune</span></span>](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
