---
title: 注册 iOS 设备进行管理
titleSuffix: Intune for Education
description: 了解如何适用于教育的 Intune 设置 Windows 10 设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 05/16/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 944840d0bfaa05fdcb5e099513fc5b7836068f7b
ms.sourcegitcommit: 370c0b29e905c25204a72fd5877000698ac859a9
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/16/2019
ms.locfileid: "65813872"
---
# <a name="enroll-ios-devices-in-intune-for-education"></a><span data-ttu-id="5b571-103">注册 iOS 设备在 Intune 教育版</span><span class="sxs-lookup"><span data-stu-id="5b571-103">Enroll iOS devices in Intune for Education</span></span>

<span data-ttu-id="5b571-104">设备已准备好开机和管理中注册后：</span><span class="sxs-lookup"><span data-stu-id="5b571-104">Devices are ready to power on and enroll in management after you:</span></span>

* <span data-ttu-id="5b571-105">设置 Intune for Education[学校信息](what-is-school-data-sync.md)— 如学生记录、 应用和设备的设置。</span><span class="sxs-lookup"><span data-stu-id="5b571-105">Set up Intune for Education [with school information](what-is-school-data-sync.md) — such as student records, apps, and settings for devices.</span></span>
* <span data-ttu-id="5b571-106">启用 Intune 以进行管理的 iOS 设备[设置 Apple 推送 MDM 证书和 Apple MDM Server 令牌](setup-ios-device-management.md#add-an-mdm-push-certificate)。</span><span class="sxs-lookup"><span data-stu-id="5b571-106">Enable Intune for iOS device management by [setting up the Apple Push MDM certificate and Apple MDM Server tokens](setup-ios-device-management.md#add-an-mdm-push-certificate).</span></span>
* <span data-ttu-id="5b571-107">[同步 Apple MDM Server 令牌](setup-ios-device-management.md#sync-managed-devices)使用 Intune 教育版和已准备注册设备的列表，请参阅。</span><span class="sxs-lookup"><span data-stu-id="5b571-107">[Sync your Apple MDM Server tokens](setup-ios-device-management.md#sync-managed-devices) with Intune for Education and see a list of ready-to-enroll devices.</span></span>  

> [!NOTE]
> <span data-ttu-id="5b571-108">请确保你的设备连接到 Internet，并且你的帐户具有足够 Intune for Education 设备许可证，若要完成安装。</span><span class="sxs-lookup"><span data-stu-id="5b571-108">Make sure your devices are connected to the Internet and your account has enough Intune for Education device licenses to complete setup.</span></span> <span data-ttu-id="5b571-109">详细了解中的许可[向用户分配许可证](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)。</span><span class="sxs-lookup"><span data-stu-id="5b571-109">Find out more about licensing in [Assign licenses to users](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).</span></span>

## <a name="preconfigured-enrollment-profile"></a><span data-ttu-id="5b571-110">预配置的注册配置文件</span><span class="sxs-lookup"><span data-stu-id="5b571-110">Preconfigured enrollment profile</span></span>  
<span data-ttu-id="5b571-111">Intune for Education 创建并分配学校优化注册配置文件的每个已同步的设备。</span><span class="sxs-lookup"><span data-stu-id="5b571-111">Intune for Education creates and assigns each synced device a school-optimized enrollment profile.</span></span>  

<span data-ttu-id="5b571-112">注册配置文件配置为让如何本身设置和管理中注册的设备。</span><span class="sxs-lookup"><span data-stu-id="5b571-112">Enrollment profiles are configured to tell the device how to set itself up and enroll in management.</span></span> <span data-ttu-id="5b571-113">Intune 配置的设置，以帮助加快你的注册。</span><span class="sxs-lookup"><span data-stu-id="5b571-113">Intune configures the settings to help speed up your enrollment.</span></span>  <span data-ttu-id="5b571-114">当开启设备时，将注册配置文件会立即开始设置你的设备。</span><span class="sxs-lookup"><span data-stu-id="5b571-114">When you power on the device, the enrollment profile immediately begins setting up your device.</span></span>

## <a name="preconfigured-settings"></a><span data-ttu-id="5b571-115">预先配置的设置</span><span class="sxs-lookup"><span data-stu-id="5b571-115">Preconfigured settings</span></span>  
<span data-ttu-id="5b571-116">初次设置设备，设备注册配置如下：</span><span class="sxs-lookup"><span data-stu-id="5b571-116">During initial device setup, devices enroll with the following configurations:</span></span>

* <span data-ttu-id="5b571-117">无用户关联</span><span class="sxs-lookup"><span data-stu-id="5b571-117">No user affinity</span></span>
* <span data-ttu-id="5b571-118">启用受监督的模式</span><span class="sxs-lookup"><span data-stu-id="5b571-118">Supervised mode enabled</span></span>
* <span data-ttu-id="5b571-119">阻止同步或与其他设备配对</span><span class="sxs-lookup"><span data-stu-id="5b571-119">Blocked from syncing or pairing with other devices</span></span>
* <span data-ttu-id="5b571-120">锁定的注册，含义用户不能更改其设备上的管理设置</span><span class="sxs-lookup"><span data-stu-id="5b571-120">Locked enrollment, meaning users can't change management settings on their devices</span></span>  

<span data-ttu-id="5b571-121">Intune for Education 适用于通过 MDM server 令牌注册的设备命名方案。</span><span class="sxs-lookup"><span data-stu-id="5b571-121">Intune for Education applies a naming scheme to devices that you enroll with an MDM server token.</span></span> <span data-ttu-id="5b571-122">默认情况下，设备是名为其设备序列号。</span><span class="sxs-lookup"><span data-stu-id="5b571-122">By default, devices are named with their device serial number.</span></span> <span data-ttu-id="5b571-123">设置你的 MDM server 令牌时，还可以添加自定义设备名称。</span><span class="sxs-lookup"><span data-stu-id="5b571-123">You can also add on a custom device name when you set up your MDM server token.</span></span>  

<span data-ttu-id="5b571-124">以下设置助理设置隐藏在注册过程：</span><span class="sxs-lookup"><span data-stu-id="5b571-124">The following Setup Assistant settings are hidden during enrollment:</span></span>
* <span data-ttu-id="5b571-125">密码设置</span><span class="sxs-lookup"><span data-stu-id="5b571-125">Passcode setup</span></span>
* <span data-ttu-id="5b571-126">位置服务</span><span class="sxs-lookup"><span data-stu-id="5b571-126">Location Services</span></span>
* <span data-ttu-id="5b571-127">设备还原</span><span class="sxs-lookup"><span data-stu-id="5b571-127">Device restore</span></span>
* <span data-ttu-id="5b571-128">iCloud 和 Apple ID</span><span class="sxs-lookup"><span data-stu-id="5b571-128">iCloud & Apple ID</span></span>
* <span data-ttu-id="5b571-129">Touch ID 设置</span><span class="sxs-lookup"><span data-stu-id="5b571-129">Touch ID setup</span></span>
* <span data-ttu-id="5b571-130">Apple Pay 安装程序</span><span class="sxs-lookup"><span data-stu-id="5b571-130">Apple Pay setup</span></span>
* <span data-ttu-id="5b571-131">显示缩放选项</span><span class="sxs-lookup"><span data-stu-id="5b571-131">Display Zoom options</span></span>
* <span data-ttu-id="5b571-132">使用 Siri 安装程序</span><span class="sxs-lookup"><span data-stu-id="5b571-132">Siri setup</span></span>
* <span data-ttu-id="5b571-133">诊断数据选项</span><span class="sxs-lookup"><span data-stu-id="5b571-133">Diagnostics Data options</span></span>  


<span data-ttu-id="5b571-134">以下设置助理设置是在注册过程中所示：</span><span class="sxs-lookup"><span data-stu-id="5b571-134">The following Setup Assistant setting is shown during enrollment:</span></span>
* <span data-ttu-id="5b571-135">条款和条件</span><span class="sxs-lookup"><span data-stu-id="5b571-135">Terms and Conditions</span></span>

### <a name="what-is-setup-assistant"></a><span data-ttu-id="5b571-136">设置助理是什么？</span><span class="sxs-lookup"><span data-stu-id="5b571-136">What is Setup Assistant?</span></span>
<span data-ttu-id="5b571-137">第一次打开设备，Intune 教育版将启动 iOS 开箱体验，称为*设置助理*。</span><span class="sxs-lookup"><span data-stu-id="5b571-137">The first time that you turn on your device, Intune for Education launches the iOS out-of-box experience, called *Setup Assistant*.</span></span> <span data-ttu-id="5b571-138">设置助理将指导你完成一系列屏幕，并准备你的学校使用的设备。</span><span class="sxs-lookup"><span data-stu-id="5b571-138">Setup Assistant walks you through a series of screens and prepares your device for school use.</span></span>  

## <a name="enroll-a-device"></a><span data-ttu-id="5b571-139">注册设备</span><span class="sxs-lookup"><span data-stu-id="5b571-139">Enroll a device</span></span>

<span data-ttu-id="5b571-140">完成以下步骤引导完成设备注册。</span><span class="sxs-lookup"><span data-stu-id="5b571-140">Walk through the following steps to complete device enrollment.</span></span>

1. <span data-ttu-id="5b571-141">打开 iOS 设备。</span><span class="sxs-lookup"><span data-stu-id="5b571-141">Turn on your iOS device.</span></span> 
2. <span data-ttu-id="5b571-142">选择“语言”后，请将设备连接 Wi-Fi。</span><span class="sxs-lookup"><span data-stu-id="5b571-142">After you select your **Language**, connect your device to Wi-Fi.</span></span>
3. <span data-ttu-id="5b571-143">上**设置 iOS 设备**屏幕上，选择你**国家/地区**。</span><span class="sxs-lookup"><span data-stu-id="5b571-143">On the **Set up iOS device** screen, select your **Country/Region**.</span></span>
4. <span data-ttu-id="5b571-144">若要自动或手动连接到 Wi-fi 的屏幕上按照的说明。</span><span class="sxs-lookup"><span data-stu-id="5b571-144">Follow the instructions on screen to automatically or manually connect to Wi-Fi.</span></span> <span data-ttu-id="5b571-145">连接后，**配置**屏幕出现时，使用注册详细信息。</span><span class="sxs-lookup"><span data-stu-id="5b571-145">After you're connected, the **Configuration** screen appears, with enrollment details.</span></span>  
5. <span data-ttu-id="5b571-146">同意**条款和条件**。</span><span class="sxs-lookup"><span data-stu-id="5b571-146">Agree to the **Terms and Conditions**.</span></span> <span data-ttu-id="5b571-147">然后决定您是否想要向 Apple 发送诊断信息。</span><span class="sxs-lookup"><span data-stu-id="5b571-147">Then decide if you want to send diagnostic information to Apple.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="5b571-148">后续步骤</span><span class="sxs-lookup"><span data-stu-id="5b571-148">Next steps</span></span>
<span data-ttu-id="5b571-149">现在，设备学校用于设置并准备就绪后，了解如何更新、 监视和解决这些问题。</span><span class="sxs-lookup"><span data-stu-id="5b571-149">Now that devices are set up and ready for school use, learn how to update, monitor, and troubleshoot them.</span></span>   
* <span data-ttu-id="5b571-150">添加更多[免费](add-apps-ios.md)并[VPP](add-vpp-apps-ios.md)学校全年的 iOS 应用</span><span class="sxs-lookup"><span data-stu-id="5b571-150">Add more [free](add-apps-ios.md) and [VPP](add-vpp-apps-ios.md) iOS apps throughout the school year</span></span>
* <span data-ttu-id="5b571-151">将分配[组管理员](group-admin-delegate.md)可帮助您管理您的学校内或跨地区的教室设置</span><span class="sxs-lookup"><span data-stu-id="5b571-151">Assign [group admins](group-admin-delegate.md) to help you manage classroom settings within your school or across the district</span></span>
* <span data-ttu-id="5b571-152">了解如何[设置继承](settings-inheritance.md)影响新组</span><span class="sxs-lookup"><span data-stu-id="5b571-152">Learn how [settings inheritance](settings-inheritance.md) affects new groups</span></span>
* <span data-ttu-id="5b571-153">审阅[报表](what-are-reports.md)地找出并对错误进行故障排除</span><span class="sxs-lookup"><span data-stu-id="5b571-153">Review [reports](what-are-reports.md) to pinpoint and troubleshoot errors</span></span> 
* <span data-ttu-id="5b571-154">续订[iOS 证书和令牌](renew-ios-certificate-token.md)每年</span><span class="sxs-lookup"><span data-stu-id="5b571-154">Renew [iOS certificates and tokens](renew-ios-certificate-token.md) every year</span></span>
