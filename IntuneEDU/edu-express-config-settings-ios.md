---
title: 快速配置中的默认 iOS 设置
titleSuffix: Intune for Education
description: 列出使用快速配置时设置的默认设置名称和行为。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/19/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4b1d0141eb9ad0f581c47b963607f88227a1d4fa
ms.sourcegitcommit: f9aea851d80c2bbbe70fbea5666f07b9992dc975
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/02/2019
ms.locfileid: "68740476"
---
# <a name="default-ios-settings-in-express-configuration"></a><span data-ttu-id="2d1f0-103">快速配置中的默认 iOS 设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-103">Default iOS settings in Express Configuration</span></span>
<span data-ttu-id="2d1f0-104">快速配置是预配置的 iOS 设置建议, 可帮助你快速设置一组设备或用户。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-104">Express Configuration is preset with iOS setting suggestions to help you quickly set up a group of devices or users.</span></span> <span data-ttu-id="2d1f0-105">Intune for Education 选择同时为 Microsoft 推荐的和最适用于 school 环境的设置。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-105">Intune for Education chooses settings that are both Microsoft-recommended and best for school environments.</span></span> <span data-ttu-id="2d1f0-106">更改以适合你的学校的规则和策略, 或单击 "设置" 页面以应用建议。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-106">Make changes to fit your school's rules and policies, or click straight through the settings page to apply our recommendations.</span></span> 

<span data-ttu-id="2d1f0-107">有关设置和说明的完整列表, 请参阅[Intune for Education 中的所有 iOS 设置](all-edu-settings-ios.md)。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-107">For the complete list of settings and descriptions, see [All iOS settings in Intune for Education](all-edu-settings-ios.md).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="2d1f0-108">如果在启动快速配置时禁用了 iOS 配置, 请检查以确保已设置 MDM Apple Push certificate 和 DEP 令牌。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-108">If iOS configurations are disabled when you launch Express Configuration, check to make sure you've set up both your MDM Apple Push certificate and DEP token.</span></span> <span data-ttu-id="2d1f0-109">如果有这两种方法, 请确保它们都不会过期。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-109">If you have both of these, make sure that neither has expired.</span></span> <span data-ttu-id="2d1f0-110">有关设置 iOS 设备管理的详细信息, 请参阅[设置 ios 设备管理](setup-ios-device-management.md)</span><span class="sxs-lookup"><span data-stu-id="2d1f0-110">For more information about setting up iOS device management, see [Set up iOS device management](setup-ios-device-management.md)</span></span>


## <a name="app-store-itunes-store-and-book-store"></a><span data-ttu-id="2d1f0-111">应用商店、iTunes 商店和书籍商店</span><span class="sxs-lookup"><span data-stu-id="2d1f0-111">App Store, iTunes Store, and Book Store</span></span>  
<span data-ttu-id="2d1f0-112">设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-112">Setting</span></span>|<span data-ttu-id="2d1f0-113">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-113">What it does</span></span>|  
|---|---|
|<span data-ttu-id="2d1f0-114">阻止应用商店</span><span class="sxs-lookup"><span data-stu-id="2d1f0-114">Block App Store</span></span>|<span data-ttu-id="2d1f0-115">阻止学生访问学校设备上的应用商店。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-115">Block students from accessing the App Store on school devices.</span></span>|
|<span data-ttu-id="2d1f0-116">阻止应用内购买</span><span class="sxs-lookup"><span data-stu-id="2d1f0-116">Block in-app purchases</span></span>|<span data-ttu-id="2d1f0-117">阻止在正在运行的应用中进行存储购买。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-117">Block attempts to make store purchases from within a running app.</span></span>|
|<span data-ttu-id="2d1f0-118">阻止应用商店和 iTunes 应用商店中的显式内容</span><span class="sxs-lookup"><span data-stu-id="2d1f0-118">Block explicit content in App Store and iTunes Store</span></span>|<span data-ttu-id="2d1f0-119">阻止学生访问应用商店中分级为成人的内容。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-119">Block students from accessing content rated as adult in the App Store.</span></span>|
|<span data-ttu-id="2d1f0-120">阻止下载标记为 erotica 的 Apple 书籍内容</span><span class="sxs-lookup"><span data-stu-id="2d1f0-120">Block downloading Apple Books content flagged as erotica</span></span>|<span data-ttu-id="2d1f0-121">阻止学生下载归类为 erotica 的书籍。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-121">Block students from downloading books classified as erotica.</span></span>|  

## <a name="built-in-apps"></a><span data-ttu-id="2d1f0-122">内置应用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-122">Built-in apps</span></span>  
<span data-ttu-id="2d1f0-123">设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-123">Setting</span></span>|<span data-ttu-id="2d1f0-124">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-124">What it does</span></span>|  
|---|---|
|<span data-ttu-id="2d1f0-125">阻止照相机</span><span class="sxs-lookup"><span data-stu-id="2d1f0-125">Block Camera</span></span>|<span data-ttu-id="2d1f0-126">阻止在设备上使用相机。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-126">Block use of the camera on the device.</span></span>|
|<span data-ttu-id="2d1f0-127">阻止 FaceTime</span><span class="sxs-lookup"><span data-stu-id="2d1f0-127">Block FaceTime</span></span>|<span data-ttu-id="2d1f0-128">阻止在设备上使用 FaceTime 应用。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-128">Blocks use of the FaceTime app on the device.</span></span>|
|<span data-ttu-id="2d1f0-129">块 Game Center</span><span class="sxs-lookup"><span data-stu-id="2d1f0-129">Block Game Center</span></span>|<span data-ttu-id="2d1f0-130">阻止在设备上使用 Game Center 应用。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-130">Block use of the Game Center app on devices.</span></span>|  
|<span data-ttu-id="2d1f0-131">块 Apple Music</span><span class="sxs-lookup"><span data-stu-id="2d1f0-131">Block Apple Music</span></span>|<span data-ttu-id="2d1f0-132">阻止在设备上使用 Apple Music 应用的音乐流组件。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-132">Block use of the music streaming component of the Apple Music app on the device.</span></span>|
|<span data-ttu-id="2d1f0-133">阻止消息应用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-133">Block Messages app</span></span>|<span data-ttu-id="2d1f0-134">阻止在设备上使用 "邮件" 应用。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-134">Block use of the Messages app on the device.</span></span>|
|<span data-ttu-id="2d1f0-135">阻止 Apple 书籍</span><span class="sxs-lookup"><span data-stu-id="2d1f0-135">Block Apple Books</span></span>|<span data-ttu-id="2d1f0-136">阻止学生浏览和购买书籍商店中的书籍。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-136">Block students from browsing and purchasing books in the Book Store.</span></span>|  

## <a name="device-restrictions"></a><span data-ttu-id="2d1f0-137">设备限制</span><span class="sxs-lookup"><span data-stu-id="2d1f0-137">Device restrictions</span></span>  
<span data-ttu-id="2d1f0-138">设置名</span><span class="sxs-lookup"><span data-stu-id="2d1f0-138">Setting name</span></span>|<span data-ttu-id="2d1f0-139">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-139">What it does</span></span>|
|---|---|
|<span data-ttu-id="2d1f0-140">阻止更改设备名称</span><span class="sxs-lookup"><span data-stu-id="2d1f0-140">Block changing device name</span></span>|<span data-ttu-id="2d1f0-141">阻止学生更改设备的名称。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-141">Block students from changing the name of the device.</span></span>|
|<span data-ttu-id="2d1f0-142">阻止更改墙纸</span><span class="sxs-lookup"><span data-stu-id="2d1f0-142">Block changing wallpaper</span></span>|<span data-ttu-id="2d1f0-143">阻止学生更改设备锁定屏幕和主屏幕图像。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-143">Blocks students from changing the device lock screen and home screen image.</span></span>|
|<span data-ttu-id="2d1f0-144">阻止更改通知设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-144">Block changing notification settings</span></span>|<span data-ttu-id="2d1f0-145">阻止学生更改设备通知设置。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-145">Block students from changing the device notification settings.</span></span>|
|<span data-ttu-id="2d1f0-146">阻止对内容和隐私限制的更改</span><span class="sxs-lookup"><span data-stu-id="2d1f0-146">Block changes to content and privacy restrictions</span></span>|<span data-ttu-id="2d1f0-147">阻止学生更改设备上的限制 (家长控制) 和屏幕时间设置。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-147">Block students from changing restrictions (parental controls) and Screen Time settings on the device.</span></span>|
|<span data-ttu-id="2d1f0-148">清除所有内容和设置的阻止按钮</span><span class="sxs-lookup"><span data-stu-id="2d1f0-148">Block button that erases all content and settings</span></span>|<span data-ttu-id="2d1f0-149">阻止学生擦除设备上的所有内容和设置。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-149">Block students from erasing all content and settings on the device.</span></span> <span data-ttu-id="2d1f0-150">"清除" 按钮变为不可用, 无法选择。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-150">The erase button becomes unavailable and can't be selected.</span></span>|  

## <a name="icloud"></a><span data-ttu-id="2d1f0-151">iCloud</span><span class="sxs-lookup"><span data-stu-id="2d1f0-151">iCloud</span></span>
|<span data-ttu-id="2d1f0-152">设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-152">Setting</span></span>|<span data-ttu-id="2d1f0-153">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-153">What it does</span></span>|
|---|---|
|<span data-ttu-id="2d1f0-154">阻止 iCloud 备份</span><span class="sxs-lookup"><span data-stu-id="2d1f0-154">Block iCloud backup</span></span>|<span data-ttu-id="2d1f0-155">阻止学生将设备备份到 iCloud。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-155">Block students from backing up devices to iCloud.</span></span>|
|<span data-ttu-id="2d1f0-156">阻止将文档同步到 iCloud</span><span class="sxs-lookup"><span data-stu-id="2d1f0-156">Block syncing documents to iCloud</span></span>|<span data-ttu-id="2d1f0-157">阻止文档同步到 iCloud 存储空间。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-157">Block documents from syncing to an iCloud storage space.</span></span>|
|<span data-ttu-id="2d1f0-158">阻止 iCloud 照片库</span><span class="sxs-lookup"><span data-stu-id="2d1f0-158">Block iCloud Photo Library</span></span>|<span data-ttu-id="2d1f0-159">阻止学生在云中存储照片和视频。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-159">Block students from storing photos and videos in the cloud.</span></span> <span data-ttu-id="2d1f0-160">尚未从 iCloud 照片库完全下载的照片将从本地存储中删除。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-160">Photos that aren't fully downloaded from iCloud Photo Library are removed from local storage.</span></span>|  

## <a name="lock-screen-and-wallpaper"></a><span data-ttu-id="2d1f0-161">锁定屏幕和墙纸</span><span class="sxs-lookup"><span data-stu-id="2d1f0-161">Lock screen and wallpaper</span></span>
<span data-ttu-id="2d1f0-162">设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-162">Setting</span></span>|<span data-ttu-id="2d1f0-163">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-163">What it does</span></span>|
|---|---|
|<span data-ttu-id="2d1f0-164">锁定屏幕上的阻止通知</span><span class="sxs-lookup"><span data-stu-id="2d1f0-164">Block notifications on lock screen</span></span>|<span data-ttu-id="2d1f0-165">阻止学生在设备锁定时查看通知。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-165">Block students from viewing notifications when the device is locked.</span></span>|
|<span data-ttu-id="2d1f0-166">阻止从锁屏界面访问钱包</span><span class="sxs-lookup"><span data-stu-id="2d1f0-166">Block access to Wallet from lock screen</span></span>|<span data-ttu-id="2d1f0-167">锁定设备时阻止学生访问钱包应用。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-167">Block students from accessing the Wallet app when the device is locked.</span></span>|
|<span data-ttu-id="2d1f0-168">设置设备锁定屏幕图像</span><span class="sxs-lookup"><span data-stu-id="2d1f0-168">Set device lock screen image</span></span>|<span data-ttu-id="2d1f0-169">选择一个自定义映像, 作为设备的锁屏界面的墙纸。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-169">Choose a custom image to appear as the wallpaper for the device's lock screen.</span></span>|
|<span data-ttu-id="2d1f0-170">设置设备主屏幕图像</span><span class="sxs-lookup"><span data-stu-id="2d1f0-170">Set device home screen image</span></span>|<span data-ttu-id="2d1f0-171">选择一个自定义映像, 作为设备主屏幕的墙纸。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-171">Choose a custom image to appear as the wallpaper for the device's home screen.</span></span>|  

## <a name="passcode-touch-id-and-face-id"></a><span data-ttu-id="2d1f0-172">密码、Touch ID 和人脸 ID</span><span class="sxs-lookup"><span data-stu-id="2d1f0-172">Passcode, Touch ID, and Face ID</span></span>  
<span data-ttu-id="2d1f0-173">设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-173">Setting</span></span>|<span data-ttu-id="2d1f0-174">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-174">What it does</span></span>|
|---|---|  
|<span data-ttu-id="2d1f0-175">需要密码</span><span class="sxs-lookup"><span data-stu-id="2d1f0-175">Require passcode</span></span>|<span data-ttu-id="2d1f0-176">要求学生输入密码来解锁设备。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-176">Require students to enter a passcode to unlock the device.</span></span>|
|<span data-ttu-id="2d1f0-177">阻止更改密码</span><span class="sxs-lookup"><span data-stu-id="2d1f0-177">Block changing passcode</span></span>|<span data-ttu-id="2d1f0-178">阻止学生更改、添加或删除设备密码。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-178">Block students from changing, adding, or removing the device passcode.</span></span>|
|<span data-ttu-id="2d1f0-179">擦除设备前的密码尝试失败次数</span><span class="sxs-lookup"><span data-stu-id="2d1f0-179">Number of failed passcode attempts before wiping device</span></span>|<span data-ttu-id="2d1f0-180">当某人超出允许的登录尝试次数时, 设备将从设备中清除所有内容和设置, 例如个人数据、iOS 软件、电子邮件帐户、系统和应用设置、下载的应用和媒体。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-180">When someone exceeds the allowed number of sign-in attempts, the device erases all content and settings from the device, such as personal data, iOS software, email accounts, system and app settings, downloaded apps, and media.</span></span> <span data-ttu-id="2d1f0-181">设备将还原到首次打开的方式。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-181">The device is restored to the way it was when it was first turned on.</span></span> <span data-ttu-id="2d1f0-182">若要配置此设置, 请输入允许的最大登录尝试次数。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-182">To configure this setting, enter the maximum number of sign-in attempts allowed.</span></span>|
|<span data-ttu-id="2d1f0-183">阻止 Touch ID 和人脸 ID</span><span class="sxs-lookup"><span data-stu-id="2d1f0-183">Block Touch ID and Face ID</span></span>|<span data-ttu-id="2d1f0-184">阻止学生使用指纹或面部识别来解锁设备。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-184">Block students from using a fingerprint or facial recognition to unlock devices.</span></span>|

## <a name="siri-and-search"></a><span data-ttu-id="2d1f0-185">Siri 和搜索</span><span class="sxs-lookup"><span data-stu-id="2d1f0-185">Siri and search</span></span> 
<span data-ttu-id="2d1f0-186">设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-186">Setting</span></span>|<span data-ttu-id="2d1f0-187">其作用</span><span class="sxs-lookup"><span data-stu-id="2d1f0-187">What it does</span></span>|
|---|---|   
|<span data-ttu-id="2d1f0-188">阻止 Siri</span><span class="sxs-lookup"><span data-stu-id="2d1f0-188">Block Siri</span></span>|<span data-ttu-id="2d1f0-189">阻止学生使用 Siri, 即 iOS 语音助手。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-189">Block students from using Siri, the iOS voice assistant.</span></span>|  

## <a name="reset-default-settings"></a><span data-ttu-id="2d1f0-190">重置默认设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-190">Reset default settings</span></span>
<span data-ttu-id="2d1f0-191">若要将所有设置还原为其默认值, 请单击 "**重置为建议的默认**值"。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-191">To restore all settings to their default values, click **Reset to suggested defaults**.</span></span> 

## <a name="next-steps"></a><span data-ttu-id="2d1f0-192">后续步骤</span><span class="sxs-lookup"><span data-stu-id="2d1f0-192">Next steps</span></span>  
<span data-ttu-id="2d1f0-193">在 Intune for Education 中了解有关组、设置和监视冲突的信息。</span><span class="sxs-lookup"><span data-stu-id="2d1f0-193">Learn all about groups, settings, and monitoring conflicts in Intune for Education.</span></span> 
* <span data-ttu-id="2d1f0-194">了解[分配的和动态](create-groups.md)组之间的差异</span><span class="sxs-lookup"><span data-stu-id="2d1f0-194">Find out the difference between [assigned and dynamic](create-groups.md) groups</span></span>
* <span data-ttu-id="2d1f0-195">分配[组管理员](group-admin-delegate.md)以帮助你管理学校内或跨区域的教室设置</span><span class="sxs-lookup"><span data-stu-id="2d1f0-195">Assign [group admins](group-admin-delegate.md) to help you manage classroom settings within your school or across the district</span></span>
* <span data-ttu-id="2d1f0-196">了解[设置继承](settings-inheritance.md)如何影响组分配</span><span class="sxs-lookup"><span data-stu-id="2d1f0-196">Learn how [settings inheritance](settings-inheritance.md) affects group assignments</span></span>
* <span data-ttu-id="2d1f0-197">查看[报表](what-are-reports.md)以确定并解决设置冲突</span><span class="sxs-lookup"><span data-stu-id="2d1f0-197">Review [reports](what-are-reports.md) to pinpoint and troubleshoot setting conflicts</span></span>
