---
title: 续订 Apple MDM 证书
titleSuffix: Intune for Education
description: 了解如何续订过期的证书或 Intune for Education 门户中的令牌。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: a5989a02466183e4c891851598ffc885588c78fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146562"
---
# <a name="renew-ios-certificate-and-tokens"></a><span data-ttu-id="7f0be-103">续订 iOS 证书和令牌</span><span class="sxs-lookup"><span data-stu-id="7f0be-103">Renew iOS certificate and tokens</span></span>
<span data-ttu-id="7f0be-104">Apple MDM Push 证书、 MDM server 令牌和 VPP 令牌过期后创建它们的 365 天。</span><span class="sxs-lookup"><span data-stu-id="7f0be-104">Apple MDM Push certificates, MDM server tokens, and VPP tokens expire 365 days after you create them.</span></span> <span data-ttu-id="7f0be-105">Intune for Education 将向您发出警报时证书或令牌是接近或已过期。</span><span class="sxs-lookup"><span data-stu-id="7f0be-105">Intune for Education will alert you when a certificate or token is close to or past its expiration date.</span></span> 

<span data-ttu-id="7f0be-106">请确保续订以维护你的 Intune for Education 帐户和 Apple 帐户之间的连接。</span><span class="sxs-lookup"><span data-stu-id="7f0be-106">Make sure to renew them to maintain the connection between your Intune for Education account and Apple account.</span></span>  

## <a name="renew-apple-mdm--certificate"></a><span data-ttu-id="7f0be-107">续订 Apple MDM 证书</span><span class="sxs-lookup"><span data-stu-id="7f0be-107">Renew Apple MDM  certificate</span></span>  
> [!IMPORTANT]
> <span data-ttu-id="7f0be-108">如果 Apple MDM 证书过期或被删除，你将需要重置并重新注册设备的新证书。</span><span class="sxs-lookup"><span data-stu-id="7f0be-108">If the Apple MDM certificate expires or is deleted, you will need to reset and re-enroll devices with a new certificate.</span></span>  

<span data-ttu-id="7f0be-109">MDM push certificate 是与用来创建它的 Apple ID 相关联。</span><span class="sxs-lookup"><span data-stu-id="7f0be-109">The MDM push certificate is associated with the Apple ID you used to create it.</span></span> <span data-ttu-id="7f0be-110">续订证书与此相同的 Apple id。</span><span class="sxs-lookup"><span data-stu-id="7f0be-110">Renew the certificate with this same Apple ID.</span></span>

1. <span data-ttu-id="7f0be-111">从 Intune for Education 仪表板，单击**租户设置** > **iOS 设备管理**。</span><span class="sxs-lookup"><span data-stu-id="7f0be-111">From the Intune for Education dashboard, click **Tenant settings** > **iOS Device Management**.</span></span>
2. <span data-ttu-id="7f0be-112">单击**MDM Push Certificate**选项卡。</span><span class="sxs-lookup"><span data-stu-id="7f0be-112">Click the **MDM Push Certificate** tab.</span></span>
3. <span data-ttu-id="7f0be-113">单击**续订证书**。</span><span class="sxs-lookup"><span data-stu-id="7f0be-113">Click **Renew certificate**.</span></span>
4. <span data-ttu-id="7f0be-114">按照上的说明**MDM Push Certificate**页。</span><span class="sxs-lookup"><span data-stu-id="7f0be-114">Follow the instructions on the **MDM Push Certificate** page.</span></span> <span data-ttu-id="7f0be-115">你将需要访问 Apple 推送证书门户以续订 MDM push Certificate。</span><span class="sxs-lookup"><span data-stu-id="7f0be-115">You'll be required to visit the Apple Push Certificates portal to renew your MDM push Certificate.</span></span> <span data-ttu-id="7f0be-116">请记住，登录到 Apple Push Certificates 门户中使用用来创建原始证书的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="7f0be-116">Remember, sign in to the Apple Push Certificates portal with the Apple ID you used to create your original certificate.</span></span>
5. <span data-ttu-id="7f0be-117">当您在 Apple Push Certificates 门户时，请单击要续订即将过期的证书的选项。</span><span class="sxs-lookup"><span data-stu-id="7f0be-117">When you're in the Apple Push Certificates portal, click the option to renew the expiring certificate.</span></span> 
6. <span data-ttu-id="7f0be-118">完成在 Apple 门户中的步骤。</span><span class="sxs-lookup"><span data-stu-id="7f0be-118">Complete the steps in the Apple portal.</span></span> <span data-ttu-id="7f0be-119">当证书的状态中读取**Active**再次单击以下载并将其保存。</span><span class="sxs-lookup"><span data-stu-id="7f0be-119">When your certificate's status reads **Active** again, click to download and save it.</span></span>
7. <span data-ttu-id="7f0be-120">返回到 Intune for Education 门户，并输入用于登录到 Apple Push Certificates 门户的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="7f0be-120">Return to the Intune for Education portal and enter the Apple ID you used to sign in to the Apple Push Certificates portal.</span></span>
8. <span data-ttu-id="7f0be-121">上载你下载的证书。</span><span class="sxs-lookup"><span data-stu-id="7f0be-121">Upload the certificate you downloaded.</span></span>
9. <span data-ttu-id="7f0be-122">单击“保存” 。</span><span class="sxs-lookup"><span data-stu-id="7f0be-122">Click **Save**.</span></span>

## <a name="renew-mdm-server-token"></a><span data-ttu-id="7f0be-123">续订 MDM server 令牌</span><span class="sxs-lookup"><span data-stu-id="7f0be-123">Renew MDM server token</span></span>

<span data-ttu-id="7f0be-124">续订 MDM server 令牌每年一次以确保 Intune for Education 始终具有 iOS 设备的更新的列表。</span><span class="sxs-lookup"><span data-stu-id="7f0be-124">Renew the MDM server token annually to make sure that Intune for Education always has an updated list of your iOS devices.</span></span>

<span data-ttu-id="7f0be-125">MDM server 令牌是与用来将服务器添加的 Apple ID 相关联。</span><span class="sxs-lookup"><span data-stu-id="7f0be-125">The MDM server token is associated with the Apple ID you used to add the server.</span></span> <span data-ttu-id="7f0be-126">续订令牌与此相同的 Apple id。</span><span class="sxs-lookup"><span data-stu-id="7f0be-126">Renew the token with this same Apple ID.</span></span> 

1. <span data-ttu-id="7f0be-127">从 Intune for Education 仪表板，单击**租户设置** > **iOS 设备管理**。</span><span class="sxs-lookup"><span data-stu-id="7f0be-127">From the Intune for Education dashboard, click **Tenant settings** > **iOS Device Management**.</span></span>
2. <span data-ttu-id="7f0be-128">单击**MDM Server 令牌**选项卡。</span><span class="sxs-lookup"><span data-stu-id="7f0be-128">Click the **MDM Server Tokens** tab.</span></span>
3. <span data-ttu-id="7f0be-129">选择你想要续订的令牌。</span><span class="sxs-lookup"><span data-stu-id="7f0be-129">Select the token that you want to renew.</span></span>
4. <span data-ttu-id="7f0be-130">单击**续订令牌**。</span><span class="sxs-lookup"><span data-stu-id="7f0be-130">Click **Renew token**.</span></span>
5. <span data-ttu-id="7f0be-131">按照上的说明**MDM Server 令牌**页。</span><span class="sxs-lookup"><span data-stu-id="7f0be-131">Follow the instructions on the **MDM Server Tokens** page.</span></span> <span data-ttu-id="7f0be-132">你将需要访问 Apple School Manager 生成新 MDM Server 令牌。</span><span class="sxs-lookup"><span data-stu-id="7f0be-132">You'll be required to visit Apple School Manager to generate a new MDM Server Token.</span></span> <span data-ttu-id="7f0be-133">请记住，登录到 Apple School Manager 与用来获取原始令牌的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="7f0be-133">Remember, sign in to Apple School Manager with the Apple ID you used to get your original token.</span></span>
6. <span data-ttu-id="7f0be-134">下载并保存新的令牌从 Apple School Manager 后，返回到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="7f0be-134">After you download and save the new token from Apple School Manager, return to the Intune for Education portal.</span></span> <span data-ttu-id="7f0be-135">键入用来创建原始令牌的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="7f0be-135">Type in the Apple ID used to create the original token.</span></span>
7. <span data-ttu-id="7f0be-136">上传已下载的令牌。</span><span class="sxs-lookup"><span data-stu-id="7f0be-136">Upload the token you downloaded.</span></span>
8. <span data-ttu-id="7f0be-137">单击“保存” 。</span><span class="sxs-lookup"><span data-stu-id="7f0be-137">Click **Save**.</span></span>


## <a name="renew-vpp-token"></a><span data-ttu-id="7f0be-138">续订 VPP 令牌</span><span class="sxs-lookup"><span data-stu-id="7f0be-138">Renew VPP token</span></span>
<span data-ttu-id="7f0be-139">续订你的 VPP 令牌每年一次以确保你 VPP 购买的应用可以查看和分配 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="7f0be-139">Renew your VPP tokens annually to make sure your VPP-purchased apps can be viewed and assigned from Intune for Education.</span></span>  

<span data-ttu-id="7f0be-140">VPP 令牌是与用来创建它的 Apple ID 相关联。</span><span class="sxs-lookup"><span data-stu-id="7f0be-140">The VPP token is associated with the Apple ID you used to create it.</span></span> <span data-ttu-id="7f0be-141">续订令牌与此相同的 Apple id。</span><span class="sxs-lookup"><span data-stu-id="7f0be-141">Renew the token with this same Apple ID.</span></span>  

1. <span data-ttu-id="7f0be-142">上**iOS 设备管理**页上，单击**VPP 令牌**选项卡。</span><span class="sxs-lookup"><span data-stu-id="7f0be-142">On the **iOS Device Management** page, click the **VPP Tokens** tab.</span></span>
2. <span data-ttu-id="7f0be-143">选择你想要续订的令牌。</span><span class="sxs-lookup"><span data-stu-id="7f0be-143">Select the token that you want to renew.</span></span>
3. <span data-ttu-id="7f0be-144">下**VPP 令牌：Microsoft Intune**，单击**续订令牌**。</span><span class="sxs-lookup"><span data-stu-id="7f0be-144">Under **VPP Token: Microsoft Intune**, click **Renew token**.</span></span>
4. <span data-ttu-id="7f0be-145">按照上的说明**VPP 令牌**页。</span><span class="sxs-lookup"><span data-stu-id="7f0be-145">Follow the instructions on the **VPP Token** page.</span></span> <span data-ttu-id="7f0be-146">你将需要访问 Apple School Manager，以获取新令牌。</span><span class="sxs-lookup"><span data-stu-id="7f0be-146">You'll be required to visit Apple School Manager to get a new token.</span></span> <span data-ttu-id="7f0be-147">请记住，用于获取原始令牌的 Apple ID 登录。</span><span class="sxs-lookup"><span data-stu-id="7f0be-147">Remember, sign in with the Apple ID you used to get your original token.</span></span>
5. <span data-ttu-id="7f0be-148">按照 Apple School Manager 创建和下载的令牌中的步骤。</span><span class="sxs-lookup"><span data-stu-id="7f0be-148">Follow the steps in Apple School Manager to create and download the token.</span></span> <span data-ttu-id="7f0be-149">然后将令牌保存到您的计算机。</span><span class="sxs-lookup"><span data-stu-id="7f0be-149">Then save the token to your computer.</span></span>
6. <span data-ttu-id="7f0be-150">返回到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="7f0be-150">Return to the Intune for Education portal.</span></span> <span data-ttu-id="7f0be-151">输入用于登录到 Apple School Manager 中的 Apple ID。</span><span class="sxs-lookup"><span data-stu-id="7f0be-151">Enter the Apple ID that you used to sign in to Apple School Manager.</span></span>
7. <span data-ttu-id="7f0be-152">单击文件夹图标，浏览计算机的文件。</span><span class="sxs-lookup"><span data-stu-id="7f0be-152">Click the folder icon to browse your computer's files.</span></span> <span data-ttu-id="7f0be-153">选择你下载和前面保存的令牌文件。</span><span class="sxs-lookup"><span data-stu-id="7f0be-153">Select the token file that you downloaded and saved earlier.</span></span>
8. <span data-ttu-id="7f0be-154">选择您的学校的设备的位置。</span><span class="sxs-lookup"><span data-stu-id="7f0be-154">Choose the location of your school's devices.</span></span>
9. <span data-ttu-id="7f0be-155">如果不想要启用自动应用更新，切换设置来禁用它们。</span><span class="sxs-lookup"><span data-stu-id="7f0be-155">If you don't want to enable automatic app updates, switch the setting to disable them.</span></span> 
10. <span data-ttu-id="7f0be-156">单击“保存” 。</span><span class="sxs-lookup"><span data-stu-id="7f0be-156">Click **Save**.</span></span>

## <a name="next-steps"></a><span data-ttu-id="7f0be-157">后续步骤</span><span class="sxs-lookup"><span data-stu-id="7f0be-157">Next steps</span></span>
<span data-ttu-id="7f0be-158">现在，续订证书和令牌，请确保[组设置](edit-groups-intune-for-edu.md)处于最新状态。</span><span class="sxs-lookup"><span data-stu-id="7f0be-158">Now that your certificates and tokens are renewed, make sure [your group settings](edit-groups-intune-for-edu.md) are up-to-date.</span></span> <span data-ttu-id="7f0be-159">若要查看你在 Intune 中的组的当前状态，了解如何[查看报表](what-are-reports.md)。</span><span class="sxs-lookup"><span data-stu-id="7f0be-159">To see the current status of your groups in Intune, learn how to [view reports](what-are-reports.md).</span></span>  

<span data-ttu-id="7f0be-160">读取[什么是 Intune for Education 中新](whats-new-in-edu.md)要了解有关最新的更新和功能。</span><span class="sxs-lookup"><span data-stu-id="7f0be-160">Read [What's new in Intune for Education](whats-new-in-edu.md) to find out about the latest updates and features.</span></span>