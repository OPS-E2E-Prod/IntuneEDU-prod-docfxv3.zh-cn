---
title: 快速配置
titleSuffix: Intune for Education
description: 使用 Express 配置来设置你 Intune for Education 中的组。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.openlocfilehash: eb3b697973d37d5b4697559b3ba87b64ba9afdb3
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147276"
---
# <a name="express-configuration-in-intune-for-education"></a><span data-ttu-id="c3a90-103">快速配置 Intune for Education 中</span><span class="sxs-lookup"><span data-stu-id="c3a90-103">Express configuration in Intune for Education</span></span>

  ![快速配置磁贴，这表示"启动快速配置，单击此处选择的应用和组的设置。"](./media/express-config-001-launch-tile.png)

<span data-ttu-id="c3a90-105">快速配置，可将设置和应用分配给用户和设备。</span><span class="sxs-lookup"><span data-stu-id="c3a90-105">Express Configuration enables you to assign settings and apps to users and devices.</span></span> <span data-ttu-id="c3a90-106">在首页上找到有关分步演练的启动磁贴[Intune for Education 门户](https://intuneeducation.portal.azure.com)。</span><span class="sxs-lookup"><span data-stu-id="c3a90-106">The launch tile for the step-by-step walkthrough is found on the front page of the [Intune for Education portal](https://intuneeducation.portal.azure.com).</span></span> 

<span data-ttu-id="c3a90-107">当您单击通过每个步骤，您将看到已配置的大多数 Windows 或 iOS 设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-107">As you click through each step, you'll see that most of the Windows or iOS settings are already configured.</span></span> <span data-ttu-id="c3a90-108">这些配置是默认值，并根据建议设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-108">These configurations are the default values and are set as recommendations.</span></span> <span data-ttu-id="c3a90-109">推荐的特定于操作系统的应用还预先选定状态。</span><span class="sxs-lookup"><span data-stu-id="c3a90-109">Recommended OS-specific apps are also preselected.</span></span> <span data-ttu-id="c3a90-110">根据需要为你的学校，请更改默认选择。</span><span class="sxs-lookup"><span data-stu-id="c3a90-110">Change the default selections as needed for your school.</span></span> 

<span data-ttu-id="c3a90-111">每当用户想要对组的设置或应用程序进行更改，则返回到快速配置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-111">Return to express configuration anytime you want to make changes to a group's settings or apps.</span></span> 

## <a name="launch-express-configuration"></a><span data-ttu-id="c3a90-112">启动快速配置</span><span class="sxs-lookup"><span data-stu-id="c3a90-112">Launch express configuration</span></span>
<span data-ttu-id="c3a90-113">本部分介绍如何完成快速配置中的步骤。</span><span class="sxs-lookup"><span data-stu-id="c3a90-113">This section describes how to complete the steps in express configuration.</span></span> <span data-ttu-id="c3a90-114">若要充分利用快速配置，请确保已同步学校数据，或在 Azure AD 中创建组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-114">To get the most out of express configuration, make sure you've synced your school data or created groups in Azure AD.</span></span> 

1. <span data-ttu-id="c3a90-115">登录到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="c3a90-115">Sign in to the Intune for Education portal.</span></span>
2. <span data-ttu-id="c3a90-116">在仪表板中，单击**启动快速配置**。</span><span class="sxs-lookup"><span data-stu-id="c3a90-116">On the dashboard, click **Launch Express Configuration**.</span></span>  

<span data-ttu-id="c3a90-117">如果当你启动快速配置已禁用 iOS 配置：</span><span class="sxs-lookup"><span data-stu-id="c3a90-117">If iOS configurations are disabled when you launch express configuration:</span></span>  
1. <span data-ttu-id="c3a90-118">从仪表板中，选择**查看所有** > **iOS 设备管理**。</span><span class="sxs-lookup"><span data-stu-id="c3a90-118">From the dashboard, select **See all** > **iOS Device Management**.</span></span>
2. <span data-ttu-id="c3a90-119">上传 Apple MDM Push certificate。</span><span class="sxs-lookup"><span data-stu-id="c3a90-119">Upload an Apple MDM Push certificate.</span></span>
3. <span data-ttu-id="c3a90-120">注册[Apple MDM Server 令牌](setup-ios-device-management.md)。</span><span class="sxs-lookup"><span data-stu-id="c3a90-120">Register an [Apple MDM Server token](setup-ios-device-management.md).</span></span>

## <a name="choose-a-group-to-configure"></a><span data-ttu-id="c3a90-121">选择要配置的组</span><span class="sxs-lookup"><span data-stu-id="c3a90-121">Choose a group to configure</span></span>

<span data-ttu-id="c3a90-122">创建和使用你的 Intune for Education 订阅包含一些组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-122">Some groups are created and included with your Intune for Education subscription.</span></span> <span data-ttu-id="c3a90-123">Intune for Education 填充学校记录中的详细信息组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-123">Intune for Education populates the groups with details from school records.</span></span> <span data-ttu-id="c3a90-124">这些组是：</span><span class="sxs-lookup"><span data-stu-id="c3a90-124">These groups are:</span></span>  

 * <span data-ttu-id="c3a90-125">所有设备</span><span class="sxs-lookup"><span data-stu-id="c3a90-125">All Devices</span></span>  
 * <span data-ttu-id="c3a90-126">所有用户</span><span class="sxs-lookup"><span data-stu-id="c3a90-126">All Users</span></span>  
 
<span data-ttu-id="c3a90-127">如果使用学校数据同步 (SDS) 将您的学校记录导入，还可以看到：</span><span class="sxs-lookup"><span data-stu-id="c3a90-127">If you use School Data Sync (SDS) to import your school's records, you'll also see:</span></span>  

 * <span data-ttu-id="c3a90-128">所有教师</span><span class="sxs-lookup"><span data-stu-id="c3a90-128">All Teachers</span></span>  
 * <span data-ttu-id="c3a90-129">所有学生</span><span class="sxs-lookup"><span data-stu-id="c3a90-129">All Students</span></span>  

<span data-ttu-id="c3a90-130">Intune for Education 建议您开始**所有用户**组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-130">Intune for Education recommends that you start with the **All Users** group.</span></span> <span data-ttu-id="c3a90-131">将所有用户必须都具有这些设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-131">Assign the settings that all users must have.</span></span> <span data-ttu-id="c3a90-132">例如，密码要求和弹出限制可能都是相同的所有用户。</span><span class="sxs-lookup"><span data-stu-id="c3a90-132">For example, password requirements and pop-up restrictions are likely the same for all users.</span></span>

  ![选择组屏幕，要求用户选择一个组。](./media/express-config-004-choose-group.png)

<span data-ttu-id="c3a90-134">单击展开/折叠箭头以查看或隐藏所有组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-134">Click the expand/collapse arrow to view or hide all groups.</span></span> <span data-ttu-id="c3a90-135">请记住，当你配置的顶级组及其子组继承其所有设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-135">Remember, when you configure a top-level group, its subgroups inherit all of its settings.</span></span>

## <a name="choose-apps"></a><span data-ttu-id="c3a90-136">选择应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-136">Choose apps</span></span>

<span data-ttu-id="c3a90-137">可以将以下应用类型添加到设备：</span><span class="sxs-lookup"><span data-stu-id="c3a90-137">You can add the following app types to devices:</span></span>
* [<span data-ttu-id="c3a90-138">Web 应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-138">Web apps</span></span>](add-web-apps-edu.md)
* <span data-ttu-id="c3a90-139">Windows 10 应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-139">Windows 10 apps</span></span>
    * [<span data-ttu-id="c3a90-140">Microsoft Office</span><span class="sxs-lookup"><span data-stu-id="c3a90-140">Microsoft Office</span></span>](install-office.md)
    * [<span data-ttu-id="c3a90-141">Microsoft Store for Education 的应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-141">Microsoft Store for Education apps</span></span>](acquire-store-apps.md)
    * [<span data-ttu-id="c3a90-142">桌面应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-142">Desktop apps</span></span>](add-desktop-apps-edu.md)
* <span data-ttu-id="c3a90-143">iOS 应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-143">iOS apps</span></span>
    * [<span data-ttu-id="c3a90-144">免费 iOS App Store 应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-144">Free iOS App Store apps</span></span>](add-apps-ios.md)
    * [<span data-ttu-id="c3a90-145">批量购买计划 (VPP) 应用</span><span class="sxs-lookup"><span data-stu-id="c3a90-145">Volume purchased program (VPP) apps</span></span>](add-vpp-apps-ios.md)

<span data-ttu-id="c3a90-146">选择要分配的一个或多个应用。</span><span class="sxs-lookup"><span data-stu-id="c3a90-146">Select one or more apps to assign.</span></span> <span data-ttu-id="c3a90-147">应用程序将立即分配给你的组在单击后**下一步**。</span><span class="sxs-lookup"><span data-stu-id="c3a90-147">Apps will immediately be assigned to your group after you click **Next**.</span></span>

  ![应用程序分配屏幕中。](./media/express-config-005-choose-apps.png)

<span data-ttu-id="c3a90-150">此外显示 Intune for Education[常用应用程序从 Microsoft Store for Education](add-popular-apps-edu.md)从跨所有 Intune 教育版用户。</span><span class="sxs-lookup"><span data-stu-id="c3a90-150">Intune for Education also displays [popular apps from the Microsoft Store for Education](add-popular-apps-edu.md) from across all Intune for Education users.</span></span>


## <a name="choose-settings"></a><span data-ttu-id="c3a90-151">选择设置</span><span class="sxs-lookup"><span data-stu-id="c3a90-151">Choose settings</span></span>
<span data-ttu-id="c3a90-152">快速配置显示在 Intune 中设备和用户的常见设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-152">Express configuration shows you common settings for devices and users in Intune.</span></span> <span data-ttu-id="c3a90-153">设置可分为特定于操作系统的类别：Windows 设置和 iOS 设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-153">Settings are separated into OS-specific categories: Windows settings and iOS settings.</span></span>

<span data-ttu-id="c3a90-154">使用建议的值是预设的默认设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-154">The default settings are preset with recommended values.</span></span> <span data-ttu-id="c3a90-155">如果你想要坚持使用建议，并不进行任何更改，请单击**下一步**。</span><span class="sxs-lookup"><span data-stu-id="c3a90-155">If you want to stick with the recommendations, and not make any changes, click **Next**.</span></span> <span data-ttu-id="c3a90-156">设置将立即应用于组中。</span><span class="sxs-lookup"><span data-stu-id="c3a90-156">Settings will immediately be applied to your group.</span></span> 

  ![选择设置屏幕中。](./media/express-config-006-choose-settings.png)


<span data-ttu-id="c3a90-159">更改快速配置选项在任何时间以适合您的学校不断变化的策略。</span><span class="sxs-lookup"><span data-stu-id="c3a90-159">Change express configuration selections at any time to fit your school's changing policies.</span></span> <span data-ttu-id="c3a90-160">有关更多自定义 Intune for Education 中，查看的完整列表[Windows 10](all-edu-settings-windows.md)并[iOS](all-edu-settings-ios.md)设备设置。</span><span class="sxs-lookup"><span data-stu-id="c3a90-160">For more customization in Intune for Education, view the full list of [Windows 10](all-edu-settings-windows.md) and [iOS](all-edu-settings-ios.md) device settings.</span></span>

## <a name="review-settings"></a><span data-ttu-id="c3a90-161">查看设置</span><span class="sxs-lookup"><span data-stu-id="c3a90-161">Review settings</span></span>

<span data-ttu-id="c3a90-162">在保存前，查看你的应用和设置选项。</span><span class="sxs-lookup"><span data-stu-id="c3a90-162">Before saving, review your apps and settings selections.</span></span> <span data-ttu-id="c3a90-163">单击**回**进行更改。</span><span class="sxs-lookup"><span data-stu-id="c3a90-163">Click **Back** to make changes.</span></span> <span data-ttu-id="c3a90-164">评审完成后，单击**保存**。</span><span class="sxs-lookup"><span data-stu-id="c3a90-164">When your review is complete, click **Save**.</span></span>

 ![查看你选择的屏幕。](./media/express-config-007-save-changes.png)  

  ![在完成屏幕中。](./media/express-config-008-all-done.png)

## <a name="next-steps"></a><span data-ttu-id="c3a90-170">后续步骤</span><span class="sxs-lookup"><span data-stu-id="c3a90-170">Next steps</span></span>
<span data-ttu-id="c3a90-171">[分配组管理员](group-admin-delegate.md)可帮助您管理刚刚创建的组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-171">[Assign group admins](group-admin-delegate.md) to help you manage the group you just created.</span></span> <span data-ttu-id="c3a90-172">通过再探快速配置来随时编辑你的组。</span><span class="sxs-lookup"><span data-stu-id="c3a90-172">Edit your group anytime by revisiting express configuration.</span></span> <span data-ttu-id="c3a90-173">若要查看更多设置，[访问的组选项卡](create-groups.md)。</span><span class="sxs-lookup"><span data-stu-id="c3a90-173">To view more settings, [visit the Groups tab](create-groups.md).</span></span>

