---
title: 设置 iOS 设备管理
titleSuffix: Intune for Education
description: 启用 iOS 设备管理同步并从 Intune for Education 门户管理 iOS 设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/09/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 7f581e8dcfc870c8b5b9994dab3b2f7a9a9428dc
ms.sourcegitcommit: fe8359eaaf216ca4938332fa7ef91d200ea72f7c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/08/2019
ms.locfileid: "67622844"
---
# <a name="setup-ios-device-management"></a><span data-ttu-id="be711-103">设置 iOS 设备管理</span><span class="sxs-lookup"><span data-stu-id="be711-103">Setup iOS device management</span></span> 

<span data-ttu-id="be711-104">可以管理或分配给学生和教师的 iOS 设备之前，必须设置 Intune for Education 中的 iOS 设备管理。</span><span class="sxs-lookup"><span data-stu-id="be711-104">Before you can manage or assign iOS devices to students and teachers, you must set up iOS device management in Intune for Education.</span></span> <span data-ttu-id="be711-105">此安装程序需要在添加 MDM Push Certificate 和配置至少一个 MDM Server 令牌 （也称为一个 DEP 令牌）。</span><span class="sxs-lookup"><span data-stu-id="be711-105">This setup requires that you add an MDM Push Certificate and configure at least one MDM Server Token (also known as a DEP token).</span></span>  

  ![租户设置、 iOS 设备管理页面，显示令牌，MDM Push Certificate，MDM 服务器上的绿色圆圈，白色复选标记和 VPP 令牌卡的屏幕截图。](./media/set-up-ios-management-landing-1807.png)   

<span data-ttu-id="be711-109">安装过程中，您将使用你的 Apple School Manager 帐户连接你的 Intune for Education 帐户。</span><span class="sxs-lookup"><span data-stu-id="be711-109">During setup, you'll connect your Intune for Education account with your Apple School Manager account.</span></span> <span data-ttu-id="be711-110">连接可确保 Intune for Education 始终提供有关已购买的 iOS 设备的最新详细信息。</span><span class="sxs-lookup"><span data-stu-id="be711-110">The connection makes sure that Intune for Education always has the most current details about your purchased iOS devices.</span></span>

<span data-ttu-id="be711-111">本文介绍如何：</span><span class="sxs-lookup"><span data-stu-id="be711-111">This article describes how to:</span></span>

* <span data-ttu-id="be711-112">添加 Apple MDM Push certificate。</span><span class="sxs-lookup"><span data-stu-id="be711-112">Add an Apple MDM Push certificate.</span></span>
* <span data-ttu-id="be711-113">配置和同步 Apple MDM Server 令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-113">Configure and sync an Apple MDM Server token.</span></span>
* <span data-ttu-id="be711-114">配置一个 Apple VPP 令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-114">Configure an Apple VPP token.</span></span>

## <a name="what-happens-after-i-set-up-device-management"></a><span data-ttu-id="be711-115">我设置了设备管理后，会发生什么情况？</span><span class="sxs-lookup"><span data-stu-id="be711-115">What happens after I set up device management?</span></span>
<span data-ttu-id="be711-116">已设置了 iOS 设备管理后，你可以使用 Intune for Education 管理的应用和 iOS 设备上的设置。</span><span class="sxs-lookup"><span data-stu-id="be711-116">After you've set up iOS device management, you'll be able to use Intune for Education to manage apps and settings on your iOS devices.</span></span> <span data-ttu-id="be711-117">此外将有权的报告和操作，因此可以解决冲突任意位置。</span><span class="sxs-lookup"><span data-stu-id="be711-117">You'll also have access to reports and actions so you can troubleshoot conflicts anywhere.</span></span>  

<span data-ttu-id="be711-118">学生和教师在您的学校中将能够安全地访问学校网站和电子邮件。</span><span class="sxs-lookup"><span data-stu-id="be711-118">Students and teachers in your school will be able to securely access school websites and email.</span></span>  

## <a name="requirements"></a><span data-ttu-id="be711-119">要求</span><span class="sxs-lookup"><span data-stu-id="be711-119">Requirements</span></span>
<span data-ttu-id="be711-120">在开始之前，请确保你有：</span><span class="sxs-lookup"><span data-stu-id="be711-120">Before beginning, make sure you have:</span></span>  
* <span data-ttu-id="be711-121">Internet 连接。</span><span class="sxs-lookup"><span data-stu-id="be711-121">An internet connection.</span></span>
* <span data-ttu-id="be711-122">Apple School Manager 帐户凭据。</span><span class="sxs-lookup"><span data-stu-id="be711-122">Your Apple School Manager account credentials.</span></span>
* <span data-ttu-id="be711-123">Intune for Education 设备许可证。</span><span class="sxs-lookup"><span data-stu-id="be711-123">Intune for Education device licenses.</span></span> <span data-ttu-id="be711-124">详细了解中的设备许可证[Intune 许可证 docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)。</span><span class="sxs-lookup"><span data-stu-id="be711-124">Find out more about the device licenses in the [Intune licenses docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="be711-125">Intune 教育版只支持 iOS 设备注册的设备购买通过 Apple dep。</span><span class="sxs-lookup"><span data-stu-id="be711-125">Intune for Education only supports iOS device enrollment for devices bought through Apple DEP.</span></span> <span data-ttu-id="be711-126">Apple School Manager 有关的详细信息，请参阅[Apple 教育支持站点](https://support.apple.com/education)。</span><span class="sxs-lookup"><span data-stu-id="be711-126">For more information about Apple School Manager, see the [Apple education support site](https://support.apple.com/education).</span></span>  

## <a name="add-an-mdm-push-certificate"></a><span data-ttu-id="be711-127">添加 MDM Push certificate</span><span class="sxs-lookup"><span data-stu-id="be711-127">Add an MDM Push certificate</span></span>
<span data-ttu-id="be711-128">Apple MDM Push certificate 设置了你的 Intune 和 Apple School Manager 帐户之间建立安全连接。</span><span class="sxs-lookup"><span data-stu-id="be711-128">An Apple MDM Push certificate sets up a secure connection between your Intune and Apple School Manager account.</span></span> <span data-ttu-id="be711-129">连接后，Intune 可以不断同步和管理你的 Apple 设备和应用。</span><span class="sxs-lookup"><span data-stu-id="be711-129">When connected, Intune can continually sync and manage your Apple devices and apps.</span></span> 

1. <span data-ttu-id="be711-130">登录到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="be711-130">Sign in to the Intune for Education Portal.</span></span>
2. <span data-ttu-id="be711-131">转到侧栏，然后单击**租户设置** > **iOS 设备管理**。</span><span class="sxs-lookup"><span data-stu-id="be711-131">Go to the sidebar and click **Tenant settings** > **iOS Device Management**.</span></span>
3. <span data-ttu-id="be711-132">单击**MDM Push Certificate**选项卡。</span><span class="sxs-lookup"><span data-stu-id="be711-132">Click the **MDM Push Certificate** tab.</span></span>
4. <span data-ttu-id="be711-133">按照上的说明**MDM Push Certificate**页。</span><span class="sxs-lookup"><span data-stu-id="be711-133">Follow the instructions on the **MDM Push Certificate** page.</span></span> <span data-ttu-id="be711-134">你将需要访问 Apple 推送证书门户来创建 MDM push certificate。</span><span class="sxs-lookup"><span data-stu-id="be711-134">You will be required to visit the Apple Push Certificates portal to create an MDM push certificate.</span></span> <span data-ttu-id="be711-135">登录到您的学校的 Apple ID，一个不在个人的 Apple Push Certificates 门户。</span><span class="sxs-lookup"><span data-stu-id="be711-135">Sign in to the Apple Push Certificates portal with your school's Apple ID, not your personal one.</span></span>
5. <span data-ttu-id="be711-136">完成在 Apple 门户中的步骤。</span><span class="sxs-lookup"><span data-stu-id="be711-136">Complete the steps in the Apple portal.</span></span> <span data-ttu-id="be711-137">创建证书后，单击要下载并保存它。</span><span class="sxs-lookup"><span data-stu-id="be711-137">After you create the certificate, click to download and save it.</span></span>
6. <span data-ttu-id="be711-138">返回到 Intune for Education 门户，并输入用于登录到 Apple Push Certificates 门户的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="be711-138">Return to the Intune for Education portal and enter the Apple ID you used to sign in to Apple Push Certificates portal.</span></span>
7. <span data-ttu-id="be711-139">上载你下载的证书。</span><span class="sxs-lookup"><span data-stu-id="be711-139">Upload the certificate you downloaded.</span></span>
8. <span data-ttu-id="be711-140">单击“保存”  。</span><span class="sxs-lookup"><span data-stu-id="be711-140">Click **Save**.</span></span>  

<span data-ttu-id="be711-141">推送证书到期每个 365 天。</span><span class="sxs-lookup"><span data-stu-id="be711-141">The push certificate expires every 365 days.</span></span> <span data-ttu-id="be711-142">Intune for Education 连接到 Apple School Manager 帐户，因此所需的证书[都需要每年续订](renew-ios-certificate-token.md)。</span><span class="sxs-lookup"><span data-stu-id="be711-142">The certificate is needed to connect Intune for Education to your Apple School Manager account, so [you'll need to renew it yearly](renew-ios-certificate-token.md).</span></span>  


## <a name="configure-mdm-server-token"></a><span data-ttu-id="be711-143">配置 MDM server 令牌</span><span class="sxs-lookup"><span data-stu-id="be711-143">Configure MDM server token</span></span>  
<span data-ttu-id="be711-144">有时称为 DEP 令牌，MDM server 令牌，可以从 Apple School Manager 的 Intune 同步设备详细信息。</span><span class="sxs-lookup"><span data-stu-id="be711-144">Sometimes referred to as a DEP token, the MDM server token lets Intune sync device details from Apple School Manager.</span></span> <span data-ttu-id="be711-145">这些详细信息告知它需要管理的设备的 Intune，并填充 Intune for Education 门户中的应用清单。</span><span class="sxs-lookup"><span data-stu-id="be711-145">These details inform Intune of the devices it needs to manage, and populates your inventory in the Intune for Education portal.</span></span>  

### <a name="shared-ipad-configuration"></a><span data-ttu-id="be711-146">共享的 iPad 配置</span><span class="sxs-lookup"><span data-stu-id="be711-146">Shared iPad configuration</span></span>  
<span data-ttu-id="be711-147">可以配置你的 iOS 设备注册为共享 iPad 设备。</span><span class="sxs-lookup"><span data-stu-id="be711-147">You can configure your iOS devices to enroll as Shared iPad devices.</span></span> <span data-ttu-id="be711-148">使用共享 iPad 的学生和教师登录到您的学校设备其唯一的托管 Apple id。</span><span class="sxs-lookup"><span data-stu-id="be711-148">With Shared iPad, students and teachers sign in to your school's devices with their unique Managed Apple ID.</span></span> <span data-ttu-id="be711-149">随着对象移动设备的应用和数据随之一起移动。</span><span class="sxs-lookup"><span data-stu-id="be711-149">As they move from device to device, their apps and data move with them.</span></span> <span data-ttu-id="be711-150">一名学生可以使用一台设备开始编写一篇，并登录到不同设备更高版本来完成本文。</span><span class="sxs-lookup"><span data-stu-id="be711-150">A student can use one device to begin writing a paper, and then sign in to a different device later to finish the paper.</span></span> <span data-ttu-id="be711-151">若要详细了解*共享 iPad*并*托管 Apple Id*，请访问[Apple 教育网站](https://www.apple.com/education/it/)并[文档](https://go.microsoft.com/fwlink/?linkid=2060097&clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="be711-151">To learn more about *Shared iPad* and *Managed Apple IDs*, visit the [Apple Education website](https://www.apple.com/education/it/) and [documentation](https://go.microsoft.com/fwlink/?linkid=2060097&clcid=0x409).</span></span>  

<span data-ttu-id="be711-152">课堂设备仍在之间，即使没有共享 iPad 的学生共享。</span><span class="sxs-lookup"><span data-stu-id="be711-152">Classroom devices can still be shared between students, even without Shared iPad.</span></span> <span data-ttu-id="be711-153">但是，用户数据不会移动设备之间。</span><span class="sxs-lookup"><span data-stu-id="be711-153">However, user data does not move between devices.</span></span> <span data-ttu-id="be711-154">配置你的服务器令牌之前，将选择你想要启用共享 iPad。</span><span class="sxs-lookup"><span data-stu-id="be711-154">Before you configure your server token, you'll choose if you want to enable Shared iPad.</span></span> 

### <a name="server-token-setup"></a><span data-ttu-id="be711-155">Server 令牌安装程序</span><span class="sxs-lookup"><span data-stu-id="be711-155">Server token setup</span></span>  

<span data-ttu-id="be711-156">以下步骤介绍如何配置你的 MDM Server 令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-156">The following steps describe how to configure your MDM Server Token.</span></span> 

1. <span data-ttu-id="be711-157">转到**租户设置** > **iOS 设备管理**，然后选择**MDM Server 令牌**选项卡。</span><span class="sxs-lookup"><span data-stu-id="be711-157">Go to **Tenant Settings** > **iOS Device Management**, and choose the **MDM Server Tokens** tab.</span></span>
2. <span data-ttu-id="be711-158">选择**设置令牌**。</span><span class="sxs-lookup"><span data-stu-id="be711-158">Select **Set up token**.</span></span>
3. <span data-ttu-id="be711-159">选择你想要注册的设备与新的服务器令牌相关联。</span><span class="sxs-lookup"><span data-stu-id="be711-159">Choose how you want to enroll the devices associated with your new server token.</span></span>  
    * <span data-ttu-id="be711-160">若要配置共享 iPad 此令牌，请选择**用户将登录到其托管 Apple Id 的设备**。</span><span class="sxs-lookup"><span data-stu-id="be711-160">To configure this token for Shared iPad, choose **Users will log in to devices with their Managed Apple IDs**.</span></span> <span data-ttu-id="be711-161">所有设备分配给此令牌都将会设置，以便用户必须登录到其托管 Apple id。</span><span class="sxs-lookup"><span data-stu-id="be711-161">All devices assigned to this token will be set up so that users must sign in to them with a Managed Apple ID.</span></span>  
        > [!IMPORTANT]
        > <span data-ttu-id="be711-162">在创建服务器令牌后，不能更改所选。</span><span class="sxs-lookup"><span data-stu-id="be711-162">You can't change your choice after you create the server token.</span></span> <span data-ttu-id="be711-163">该时间点，如果你想要更改设备的注册方式后，你将需要创建新的服务器令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-163">After that point, if you want to change how devices enroll, you'll need to create a new server token.</span></span>  

        > [!NOTE]
        > <span data-ttu-id="be711-164">如果设置了与共享 iPad 设备时，将获取所有附带共享 iPad，除外的课堂和美术应用的功能。</span><span class="sxs-lookup"><span data-stu-id="be711-164">If you set up a device with Shared iPad, you'll get all of features that come with Shared iPad, except for the Classroom and Schoolwork apps.</span></span> <span data-ttu-id="be711-165">这些应用程序不受 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="be711-165">These apps aren't supported by Intune for Education.</span></span> <span data-ttu-id="be711-166">设置 MDM server 令牌后，所有其他共享 iPad 功能将可供您。</span><span class="sxs-lookup"><span data-stu-id="be711-166">All other Shared iPad features will be available to you after you set up the MDM server token.</span></span>  

    * <span data-ttu-id="be711-167">如果您的学校未使用托管 Apple Id，请选择**任何人都可以取消锁定这些设备...** 设备仍可共享的学生&ndash;他们将只需直接访问，而无需登录。</span><span class="sxs-lookup"><span data-stu-id="be711-167">If your school isn't using Managed Apple IDs, choose **Anyone can unlock these devices...** Devices can still be shared by students&ndash;they'll just be accessed directly, without the need to sign in.</span></span> <span data-ttu-id="be711-168">如果你设置一个，它们可能需要设备密码。</span><span class="sxs-lookup"><span data-stu-id="be711-168">They might require a device passcode, if you set one.</span></span>  

4. <span data-ttu-id="be711-169">选择**下载**用于下载所需的 Intune 公钥。</span><span class="sxs-lookup"><span data-stu-id="be711-169">Select **Download** to download the required Intune public key.</span></span> <span data-ttu-id="be711-170">你将需要上载此文件中 Apple School Manager 创建 MDM server 令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-170">You'll need to upload this file in Apple School Manager to create your MDM server token.</span></span> <span data-ttu-id="be711-171">将文件保存到您的计算机。</span><span class="sxs-lookup"><span data-stu-id="be711-171">Save the file to your computer.</span></span>
5. <span data-ttu-id="be711-172">选择**转到我在 Apple School Manager 中的 MDM 服务器**。</span><span class="sxs-lookup"><span data-stu-id="be711-172">Select **Go to my MDM Servers in Apple School Manager**.</span></span> <span data-ttu-id="be711-173">如果系统提示，请登录到 Apple School Manager 与您的学校的 Apple ID，不是你个人的一个。</span><span class="sxs-lookup"><span data-stu-id="be711-173">If prompted, sign in to Apple School Manager with your school's Apple ID, not your personal one.</span></span>
6. <span data-ttu-id="be711-174">在屏幕创建 MDM 服务器中执行的步骤。</span><span class="sxs-lookup"><span data-stu-id="be711-174">Follow the steps on screen to create an MDM server.</span></span> <span data-ttu-id="be711-175">然后保存所做的更改。</span><span class="sxs-lookup"><span data-stu-id="be711-175">Then save your changes.</span></span> <span data-ttu-id="be711-176">如果没有要完成此步骤的信息，请与您的学校的 Intune 管理员联系。</span><span class="sxs-lookup"><span data-stu-id="be711-176">If you don't have the information to complete this step, contact your school's Intune administrator.</span></span>
7. <span data-ttu-id="be711-177">下载并保存 MDM 服务器的令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-177">Download and save the token for the MDM server.</span></span>
8. <span data-ttu-id="be711-178">保留在 Apple School Manager 中并转到**设备分配**。</span><span class="sxs-lookup"><span data-stu-id="be711-178">Stay in Apple School Manager and go to **Device Assignments**.</span></span> <span data-ttu-id="be711-179">对于每个设备，整个设备购买或以 CSV 文件中的设备的列表的顺序号输入的序列号。</span><span class="sxs-lookup"><span data-stu-id="be711-179">Enter the serial number for each device, the order number for your entire device purchase, or a list of your devices in a CSV file.</span></span>  

  ![Apple School Manager 网站，设备分配页的屏幕截图。](./media/Apple-School-Manager-MDM-Server-token-1807.png)   

9. <span data-ttu-id="be711-183">从下拉列表菜单中选择**将分配给服务器**。</span><span class="sxs-lookup"><span data-stu-id="be711-183">From the drop-down menu, choose **Assign to Server**.</span></span> <span data-ttu-id="be711-184">然后选择刚才创建的 MDM 服务器。</span><span class="sxs-lookup"><span data-stu-id="be711-184">Then choose the MDM server you just created.</span></span>
10. <span data-ttu-id="be711-185">返回到 Intune for Education 门户，并输入用于登录到 Apple School Manager 中的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="be711-185">Return to the Intune for Education portal and enter the Apple ID you used to sign in to Apple School Manager.</span></span>
11. <span data-ttu-id="be711-186">上传已下载的 MDM server 令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-186">Upload the MDM server token you downloaded.</span></span>
12. <span data-ttu-id="be711-187">单击“保存”  。</span><span class="sxs-lookup"><span data-stu-id="be711-187">Click **Save**.</span></span>

<span data-ttu-id="be711-188">MDM server 令牌会过期每个 365 天。</span><span class="sxs-lookup"><span data-stu-id="be711-188">MDM server tokens expire every 365 days.</span></span> <span data-ttu-id="be711-189">若要查看和管理为教育版门户中 Intune 的设备，需要使用令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-189">The token is needed to view and manage your devices in the Intune for Education portal.</span></span> <span data-ttu-id="be711-190">你将需要[每年续订](renew-ios-certificate-token.md)。</span><span class="sxs-lookup"><span data-stu-id="be711-190">You'll need to [renew it yearly](renew-ios-certificate-token.md).</span></span>

### <a name="device-enrollment-profile"></a><span data-ttu-id="be711-191">设备注册配置文件</span><span class="sxs-lookup"><span data-stu-id="be711-191">Device enrollment profile</span></span>
<span data-ttu-id="be711-192">Intune for Education 创建并配置每个 MDM server 令牌应用 iOS 注册配置文件。</span><span class="sxs-lookup"><span data-stu-id="be711-192">Intune for Education creates and applies an iOS enrollment profile to each MDM server token you configure.</span></span>

<span data-ttu-id="be711-193">所有 iOS 设备添加到 Intune 教育版都设置为受监督模式。</span><span class="sxs-lookup"><span data-stu-id="be711-193">All iOS devices added to Intune for Education are set to supervised mode.</span></span> <span data-ttu-id="be711-194">作为管理员，受监督的模式允许您更好地控制您的学校的设备。</span><span class="sxs-lookup"><span data-stu-id="be711-194">As an admin, supervised mode allows you more control over your school's devices.</span></span> <span data-ttu-id="be711-195">例如，您可以将推送新的应用或应用更新以无提示方式到设备。</span><span class="sxs-lookup"><span data-stu-id="be711-195">For example, you can push new apps or app updates silently to a device.</span></span> <span data-ttu-id="be711-196">仅限监督的设备设置的完整列表，请参阅文章[配置需要监督](/intune/device-restrictions-ios#settings-that-require-supervised-mode)。</span><span class="sxs-lookup"><span data-stu-id="be711-196">For a complete list of supervised-only settings, see the article, [Configurations requiring supervision](/intune/device-restrictions-ios#settings-that-require-supervised-mode).</span></span>

<span data-ttu-id="be711-197">Intune for Education 适用于通过 MDM server 令牌注册的设备命名方案。</span><span class="sxs-lookup"><span data-stu-id="be711-197">Intune for Education applies a naming scheme to devices that you enroll with an MDM server token.</span></span> <span data-ttu-id="be711-198">名称将有助于您确定和组的单独设备。</span><span class="sxs-lookup"><span data-stu-id="be711-198">The name will help you identify and group individual devices.</span></span> <span data-ttu-id="be711-199">默认情况下，设备是名为其设备序列号。</span><span class="sxs-lookup"><span data-stu-id="be711-199">By default, devices are named with their device serial number.</span></span> <span data-ttu-id="be711-200">设置你的 MDM server 令牌时，还可以添加自定义设备名称。</span><span class="sxs-lookup"><span data-stu-id="be711-200">You can also add on a custom device name when you set up your MDM server token.</span></span>  

<span data-ttu-id="be711-201">有关注册配置文件的详细信息，查看[配置设置的列表](add-devices-ios-edu.md#preconfigured-settings)在注册过程。</span><span class="sxs-lookup"><span data-stu-id="be711-201">For more details about enrollment profiles, view the [list of settings configured](add-devices-ios-edu.md#preconfigured-settings) during enrollment.</span></span>  

### <a name="sync-managed-devices"></a><span data-ttu-id="be711-202">同步托管设备</span><span class="sxs-lookup"><span data-stu-id="be711-202">Sync managed devices</span></span>
<span data-ttu-id="be711-203">现在，Intune for Education 有权管理的 iOS 设备，以查看你管理的设备列表同步。</span><span class="sxs-lookup"><span data-stu-id="be711-203">Now that Intune for Education has permission to manage your iOS devices, sync with Apple to view a list of your managed devices.</span></span>  
1. <span data-ttu-id="be711-204">登录到 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="be711-204">Sign in to Intune for Education.</span></span>
2. <span data-ttu-id="be711-205">单击**租户设置** > **iOS 设备管理** > **DEP 令牌**。</span><span class="sxs-lookup"><span data-stu-id="be711-205">Click **Tenant settings** > **iOS Device Management** > **DEP Tokens**.</span></span>
3. <span data-ttu-id="be711-206">单击任何列出的令牌。</span><span class="sxs-lookup"><span data-stu-id="be711-206">Click on any of the listed tokens.</span></span>
4. <span data-ttu-id="be711-207">单击**同步设备列表**。</span><span class="sxs-lookup"><span data-stu-id="be711-207">Click **Sync device list**.</span></span> 

<span data-ttu-id="be711-208">显示在列表中的设备已经可供注册。</span><span class="sxs-lookup"><span data-stu-id="be711-208">Devices that appear in the list are ready for enrollment.</span></span> <span data-ttu-id="be711-209">启动它们以开始注册过程。</span><span class="sxs-lookup"><span data-stu-id="be711-209">Power them on to start the enrollment process.</span></span>

## <a name="configure-vpp-tokens"></a><span data-ttu-id="be711-210">配置 VPP 令牌</span><span class="sxs-lookup"><span data-stu-id="be711-210">Configure VPP tokens</span></span>

 <span data-ttu-id="be711-211">VPP 令牌链接到你的 Apple VPP 或 Apple School Manager 帐户的你的 Intune for Education 帐户。</span><span class="sxs-lookup"><span data-stu-id="be711-211">A VPP token links your Intune for Education account to your Apple VPP or Apple School Manager account.</span></span> <span data-ttu-id="be711-212">可以创建单个的 VPP 令牌，以在整个组织; 管理应用也可以创建多个 VPP 令牌以分散到不同的位置或管理员管理。</span><span class="sxs-lookup"><span data-stu-id="be711-212">You can create a single VPP token to manage apps across the entire organization; or you can create multiple VPP tokens to spread management across different locations or admins.</span></span>  

<span data-ttu-id="be711-213">VPP 令牌所需的 Intune 添加到：</span><span class="sxs-lookup"><span data-stu-id="be711-213">VPP tokens are necessary for Intune to:</span></span>  
* <span data-ttu-id="be711-214">Intune for Education 门户中同步应用详细信息。</span><span class="sxs-lookup"><span data-stu-id="be711-214">Sync app details in the Intune for Education portal.</span></span>
* <span data-ttu-id="be711-215">将 VPP 购买的应用分配到组。</span><span class="sxs-lookup"><span data-stu-id="be711-215">Assign VPP-purchased apps to groups.</span></span>
* <span data-ttu-id="be711-216">以无提示方式安装 VPP 购买的应用，学校在设备上，而无需设备用户的 Apple id。</span><span class="sxs-lookup"><span data-stu-id="be711-216">Silently install VPP-purchased apps on school devices, with no need for device user's Apple ID.</span></span>

<span data-ttu-id="be711-217">而无需 VPP 令牌，仍可以搜索并获取[免费 iOS 应用通过 App Store](add-apps-ios.md)。</span><span class="sxs-lookup"><span data-stu-id="be711-217">Without a VPP token, you can still search and get [free iOS apps through the App Store](add-apps-ios.md).</span></span> <span data-ttu-id="be711-218">但是，若要在设备上安装应用，设备用户必须使用登录 Apple id。</span><span class="sxs-lookup"><span data-stu-id="be711-218">However, to install the app on the device, the device user must sign in with an Apple ID.</span></span> 

1. <span data-ttu-id="be711-219">上**iOS 设备管理**页上，单击**VPP 令牌**选项卡。</span><span class="sxs-lookup"><span data-stu-id="be711-219">On the **iOS Device Management** page, click the **VPP Tokens** tab.</span></span>
2. <span data-ttu-id="be711-220">单击**打开 Apple School Manager**并使用您的学校的 Apple ID，一个不在个人登录。</span><span class="sxs-lookup"><span data-stu-id="be711-220">Click **Open Apple School Manager** and sign in with your school's Apple ID, not your personal one.</span></span>
3. <span data-ttu-id="be711-221">按照 Apple School 管理来创建和下载的令牌中的步骤。</span><span class="sxs-lookup"><span data-stu-id="be711-221">Follow the steps in Apple School Manage to create and download the token.</span></span> <span data-ttu-id="be711-222">将令牌保存到本地驱动器。</span><span class="sxs-lookup"><span data-stu-id="be711-222">Save the token to your local drive.</span></span>
4. <span data-ttu-id="be711-223">返回到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="be711-223">Return to the Intune for Education portal.</span></span> <span data-ttu-id="be711-224">输入用于登录到 Apple School Manager 中的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="be711-224">Enter the Apple ID that you used to sign in to Apple School Manager.</span></span>
5. <span data-ttu-id="be711-225">单击文件夹图标，浏览计算机的文件。</span><span class="sxs-lookup"><span data-stu-id="be711-225">Click the folder icon to browse your computer's files.</span></span> <span data-ttu-id="be711-226">选择你下载和前面保存的令牌文件。</span><span class="sxs-lookup"><span data-stu-id="be711-226">Select the token file that you downloaded and saved earlier.</span></span>
6. <span data-ttu-id="be711-227">选择您的学校的设备的位置。</span><span class="sxs-lookup"><span data-stu-id="be711-227">Choose the location of your school's devices.</span></span>
7. <span data-ttu-id="be711-228">如果不想要启用自动应用更新，切换设置来禁用它们。</span><span class="sxs-lookup"><span data-stu-id="be711-228">If you don't want to enable automatic app updates, switch the setting to disable them.</span></span> 
8. <span data-ttu-id="be711-229">单击“保存”  。</span><span class="sxs-lookup"><span data-stu-id="be711-229">Click **Save**.</span></span>

<span data-ttu-id="be711-230">令牌过期每个 365 天。</span><span class="sxs-lookup"><span data-stu-id="be711-230">Tokens expire every 365 days.</span></span> <span data-ttu-id="be711-231">管理 VPP 购买的应用，因此所需的令牌[都需要每年续订](renew-ios-certificate-token.md)。</span><span class="sxs-lookup"><span data-stu-id="be711-231">Tokens are needed to manage VPP-purchased apps, so [you'll need to renew them yearly](renew-ios-certificate-token.md).</span></span>

### <a name="whats-a-managed-device"></a><span data-ttu-id="be711-232">什么是托管的设备？</span><span class="sxs-lookup"><span data-stu-id="be711-232">What's a managed device?</span></span>
<span data-ttu-id="be711-233">为了帮助您了解托管和非托管设备之间的区别，我们看一下下面的方案。</span><span class="sxs-lookup"><span data-stu-id="be711-233">To help you understand the difference between a managed and unmanaged device, let's look at the following scenario.</span></span>

<span data-ttu-id="be711-234">教师为学校带来了个人的 iOS 设备。</span><span class="sxs-lookup"><span data-stu-id="be711-234">A teacher brings a personal iOS device to school.</span></span> <span data-ttu-id="be711-235">在学校时间，教师使用设备，若要安排父会议和跟踪的类分配。</span><span class="sxs-lookup"><span data-stu-id="be711-235">During school hours, the teacher uses the device to schedule parent meetings and to keep track of class assignments.</span></span>  

 <span data-ttu-id="be711-236">设备不被购买通过 Apple DEP 计划学校。</span><span class="sxs-lookup"><span data-stu-id="be711-236">The device wasn't purchased by the school through the Apple DEP program.</span></span> <span data-ttu-id="be711-237">未在 Intune for Education 租户下注册。</span><span class="sxs-lookup"><span data-stu-id="be711-237">It's not enrolled under the Intune for Education tenant.</span></span> <span data-ttu-id="be711-238">因此，没有 Intune 与教师的设备进行通信的方法。</span><span class="sxs-lookup"><span data-stu-id="be711-238">As a result, there's no way for Intune to communicate with the teacher's device.</span></span> <span data-ttu-id="be711-239">设备被视为不托管-IT 管理员已在教师如何使用设备在学校时间内无法控制。</span><span class="sxs-lookup"><span data-stu-id="be711-239">The device is considered not managed -- the IT admin has no control over how the teacher uses the device during school hours.</span></span> 

<span data-ttu-id="be711-240">同样，因为它不是已知的托管设备，教师将无法访问受保护的学校资源，例如电子邮件。</span><span class="sxs-lookup"><span data-stu-id="be711-240">Similarly, since it's not a known, managed device, the teacher won't be able to access protected school resources, such as email.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="be711-241">后续步骤</span><span class="sxs-lookup"><span data-stu-id="be711-241">Next steps</span></span>

<span data-ttu-id="be711-242">采购[免费从应用商店应用](add-apps-ios.md)，或[添加 VPP 购买应用](add-vpp-apps-ios.md)到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="be711-242">Purchase [free apps from the App Store](add-apps-ios.md), or [add your VPP-purchased apps](add-vpp-apps-ios.md) to the Intune for Education portal.</span></span>  

