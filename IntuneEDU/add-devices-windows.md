---
title: 注册 Windows 10 设备
titleSuffix: Intune for Education
description: 了解如何适用于教育的 Intune 设置 Windows 10 设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 29d4b238fb906eac01f3ffe36dd252f8b657d046
ms.sourcegitcommit: 9c43411a2c210cf1d755c3120015c89611e33613
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/18/2019
ms.locfileid: "67213394"
---
# <a name="enroll-windows-10-devices"></a><span data-ttu-id="b1958-103">注册 Windows 10 设备</span><span class="sxs-lookup"><span data-stu-id="b1958-103">Enroll Windows 10 devices</span></span>

<span data-ttu-id="b1958-104">设置 Intune 教育版设置为与你的信息后，如学生记录、 应用和设备的设置，将设备连接到 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="b1958-104">After you've set up Intune for Education with your information — such as student records, apps, and settings for devices — connect the devices to Intune for Education.</span></span> <span data-ttu-id="b1958-105">对于新的 Windows 10 设备，在初始设备安装过程中建立的连接。</span><span class="sxs-lookup"><span data-stu-id="b1958-105">For new Windows 10 devices, a connection is established during initial device setup.</span></span>   

## <a name="when-to-use-set-up-school-pcs-vs-windows-autopilot"></a><span data-ttu-id="b1958-106">何时使用设置学校 Pc 与 Windows Autopilot</span><span class="sxs-lookup"><span data-stu-id="b1958-106">When to use Set up School PCs vs Windows Autopilot</span></span>  
<span data-ttu-id="b1958-107">下表介绍何时使用学校电脑、 Windows Autopilot 和 / 或用于初始设备安装程序的设置。</span><span class="sxs-lookup"><span data-stu-id="b1958-107">The following table describes when to use Set up School PCs, Windows Autopilot, or both for initial device setup.</span></span> <span data-ttu-id="b1958-108">使用**考虑的要点**列要考虑您自己的学校环境和安装程序需求。</span><span class="sxs-lookup"><span data-stu-id="b1958-108">Use the **Points to consider** column to consider your own school's environment and setup needs.</span></span>  

|<span data-ttu-id="b1958-109">考虑的要点</span><span class="sxs-lookup"><span data-stu-id="b1958-109">Points to consider</span></span>| <span data-ttu-id="b1958-110">设置学校电脑</span><span class="sxs-lookup"><span data-stu-id="b1958-110">Set up School Pcs</span></span> |<span data-ttu-id="b1958-111">Windows Autopilot</span><span class="sxs-lookup"><span data-stu-id="b1958-111">Windows Autopilot</span></span>  |
|---------|---------|---------|  
|<span data-ttu-id="b1958-112">IT 人员</span><span class="sxs-lookup"><span data-stu-id="b1958-112">IT staff</span></span> | <span data-ttu-id="b1958-113">IT 人员执行设备取消装箱，第一个开机，和设备配置的由 IT 人员执行。</span><span class="sxs-lookup"><span data-stu-id="b1958-113">IT staff performs device unboxing, first power-on, and configuration of devices is performed by the IT Staff.</span></span>|<span data-ttu-id="b1958-114">针对从 IT 人员的有限 engagement 优化。</span><span class="sxs-lookup"><span data-stu-id="b1958-114">Optimized for limited engagement from IT staff.</span></span> <span data-ttu-id="b1958-115">学生和教师可以执行设备取消装箱，第一个开机，和初始配置。</span><span class="sxs-lookup"><span data-stu-id="b1958-115">Students and teachers can perform device unboxing, first power-on, and initial configuration.</span></span>|
|<span data-ttu-id="b1958-116">设备用户</span><span class="sxs-lookup"><span data-stu-id="b1958-116">Device user</span></span>|  <span data-ttu-id="b1958-117">最适用于共享设备和面向年轻的学生。</span><span class="sxs-lookup"><span data-stu-id="b1958-117">Best for shared devices and for younger students.</span></span>|<span data-ttu-id="b1958-118">最适用于 1 对 1 设备和面向较旧的学生。</span><span class="sxs-lookup"><span data-stu-id="b1958-118">Best for 1:1 devices and for older students.</span></span>|
|<span data-ttu-id="b1958-119">应用</span><span class="sxs-lookup"><span data-stu-id="b1958-119">Apps</span></span>     | <span data-ttu-id="b1958-120">最适合部署在较慢的网络上同时大型应用程序。</span><span class="sxs-lookup"><span data-stu-id="b1958-120">Best for deploying large apps simultaneously on a slower network.</span></span>|<span data-ttu-id="b1958-121">适用于所有规模的应用。</span><span class="sxs-lookup"><span data-stu-id="b1958-121">Works well with apps of all sizes.</span></span>| 
|<span data-ttu-id="b1958-122">网络</span><span class="sxs-lookup"><span data-stu-id="b1958-122">Network</span></span> | <span data-ttu-id="b1958-123">必选项; 可靠 internet 连接最适合低带宽网络。</span><span class="sxs-lookup"><span data-stu-id="b1958-123">Reliable internet connection required; best for low-bandwidth networks.</span></span>| <span data-ttu-id="b1958-124">必选项; 可靠 internet 连接基于的并发设备设置数量和大小所需应用的网络带宽消耗。</span><span class="sxs-lookup"><span data-stu-id="b1958-124">Reliable internet connection required; network bandwidth consumption based on number of concurrent device setups and size of required apps.</span></span> <span data-ttu-id="b1958-125">学生可以设置其家庭网络上的设备。</span><span class="sxs-lookup"><span data-stu-id="b1958-125">Students can setup devices on their home network.</span></span>|
|<span data-ttu-id="b1958-126">类的第一天</span><span class="sxs-lookup"><span data-stu-id="b1958-126">First day of class</span></span>|<span data-ttu-id="b1958-127">设备准备好进行登录，并立即使用。</span><span class="sxs-lookup"><span data-stu-id="b1958-127">Devices are ready for sign in and use immediately.</span></span>| <span data-ttu-id="b1958-128">学生需要取消装箱并连接到网络;安装程序会自动完成。</span><span class="sxs-lookup"><span data-stu-id="b1958-128">Students need to unbox and connect to network; setup completes automatically.</span></span>|
|<span data-ttu-id="b1958-129">部署时间</span><span class="sxs-lookup"><span data-stu-id="b1958-129">Deployment time</span></span>|<span data-ttu-id="b1958-130">只需 1-2 分钟;时间基于数量的并发设备设置、 网络带宽和需要应用程序的大小增加。</span><span class="sxs-lookup"><span data-stu-id="b1958-130">Can take as little as 1-2 minutes; time increases based on the number of concurrent device setups, network bandwidth, and size of required applications.</span></span>|<span data-ttu-id="b1958-131">只需 1-2 分钟;时间基于数量的并发设备设置、 网络带宽和需要应用程序的大小增加。</span><span class="sxs-lookup"><span data-stu-id="b1958-131">Can take as little as 1-2 minutes; time increases based on the number of concurrent device setups, network bandwidth, and size of required applications.</span></span>|
|<span data-ttu-id="b1958-132">Oem/合作伙伴</span><span class="sxs-lookup"><span data-stu-id="b1958-132">OEMs/Partners</span></span>|<span data-ttu-id="b1958-133">不适用。</span><span class="sxs-lookup"><span data-stu-id="b1958-133">Not applicable.</span></span>  |<span data-ttu-id="b1958-134">需要 Windows Autopilot 服务由合作伙伴 (CSP) 或 OEM 提供程序注册的设备 Id。</span><span class="sxs-lookup"><span data-stu-id="b1958-134">Requires registration of device IDs for the Windows Autopilot service by a partner (CSP) or OEM provider.</span></span> |
|<span data-ttu-id="b1958-135">现有内部部署配置</span><span class="sxs-lookup"><span data-stu-id="b1958-135">Existing on premises configuration</span></span>| <span data-ttu-id="b1958-136">支持使用 Windows 配置设计器。</span><span class="sxs-lookup"><span data-stu-id="b1958-136">Supported with Windows Configuration Designer only.</span></span> | <span data-ttu-id="b1958-137">支持混合 AD 加入;设备必须在 Active Directory 域控制器所在的同一网络上。</span><span class="sxs-lookup"><span data-stu-id="b1958-137">Supports Hybrid AD join; device must be on same network as Active Directory Domain Controller.</span></span>|  
### <a name="setting-up-devices-with-windows-autopilot"></a><span data-ttu-id="b1958-138">设置与 Windows Autopilot 设备</span><span class="sxs-lookup"><span data-stu-id="b1958-138">Setting up devices with Windows Autopilot</span></span>
 <span data-ttu-id="b1958-139">若要设置你的设备与[Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/windows-autopilot-requirements)，请转到[Intune](https://devicemanagement.microsoft.com) > **设备注册** > **Windows 注册**  > **设备**。</span><span class="sxs-lookup"><span data-stu-id="b1958-139">To set up your devices with [Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/windows-autopilot-requirements), go to [Intune](https://devicemanagement.microsoft.com) > **Device enrollment** > **Windows enrollment** > **Devices**.</span></span>   

### <a name="setting-up-devices-with-set-up-school-pcs-app"></a><span data-ttu-id="b1958-140">设置设备使用 Set 学校电脑应用</span><span class="sxs-lookup"><span data-stu-id="b1958-140">Setting up devices with Set up School PCs app</span></span>
<span data-ttu-id="b1958-141">将 Windows 设备添加到 Intune 通过学校电脑应用设置。</span><span class="sxs-lookup"><span data-stu-id="b1958-141">Add Windows devices to Intune through the Set up School PCs app.</span></span> <span data-ttu-id="b1958-142">应用程序将指导完成如何配置并保存单个设备配置文件，可以将分发到多台计算机。</span><span class="sxs-lookup"><span data-stu-id="b1958-142">The app walks you through how to configure and save a single device profile that you can distribute to multiple PCs.</span></span> <span data-ttu-id="b1958-143">USB 驱动器用于保存并在设备安装过程配置文件下载到每个设备。</span><span class="sxs-lookup"><span data-stu-id="b1958-143">A USB drive is used to save and download the profile to each device during device setup.</span></span> 

<span data-ttu-id="b1958-144">有关应用程序的详细信息，请参阅[什么设置学校电脑？](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)一文。</span><span class="sxs-lookup"><span data-stu-id="b1958-144">For more information about the app, see the [What is Set up School PCs?](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) article.</span></span> 

## <a name="setup-windows-devices"></a><span data-ttu-id="b1958-145">设置 Windows 设备</span><span class="sxs-lookup"><span data-stu-id="b1958-145">Setup Windows devices</span></span>  
<span data-ttu-id="b1958-146">完成以下步骤以将 Windows 10 设备添加到 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="b1958-146">Complete the following steps to add your Windows 10 devices to Intune for Education.</span></span> <span data-ttu-id="b1958-147">在安装期间，设备必须具有 Internet 访问权限。</span><span class="sxs-lookup"><span data-stu-id="b1958-147">During setup, devices must have access to the Internet.</span></span> 

1. <span data-ttu-id="b1958-148">在新的 Windows 10 设备上的电源。</span><span class="sxs-lookup"><span data-stu-id="b1958-148">Power on the new Windows 10 device.</span></span> 
2. <span data-ttu-id="b1958-149">在新的或重置设备上，读取第一个安装程序屏幕，**让启动与区域。这是吧？**</span><span class="sxs-lookup"><span data-stu-id="b1958-149">On a new or reset device, the first setup screen reads, **Lets start with region. Is this right?**</span></span> <span data-ttu-id="b1958-150">选择您的 Pc 的位置的区域。</span><span class="sxs-lookup"><span data-stu-id="b1958-150">Select the region where your PCs are located.</span></span> <span data-ttu-id="b1958-151">然后选择**是**。</span><span class="sxs-lookup"><span data-stu-id="b1958-151">Then select **Yes**.</span></span>  

   ![示例中的 Windows 10 OOBE 开始设置屏幕的屏幕截图。](./media/RS5_Choose_Region.png)  

3. <span data-ttu-id="b1958-154">选择键盘布局。</span><span class="sxs-lookup"><span data-stu-id="b1958-154">Choose a keyboard layout.</span></span> <span data-ttu-id="b1958-155">此步骤配置屏幕上的键盘，以匹配您键盘上的物理布局。</span><span class="sxs-lookup"><span data-stu-id="b1958-155">This step configures the onscreen keyboard to match your keyboard's physical layout.</span></span> <span data-ttu-id="b1958-156">它还可以配置语言和键盘字符。</span><span class="sxs-lookup"><span data-stu-id="b1958-156">It also configures language and keyboard characters.</span></span> <span data-ttu-id="b1958-157">选择**是**以继续。</span><span class="sxs-lookup"><span data-stu-id="b1958-157">Select **Yes** to continue.</span></span>  

      ![示例屏幕截图的键盘布局屏幕中，使用美国突出显示为所选的布局。](./media/RS5_Choose_Keyboard.png)  

4. <span data-ttu-id="b1958-159">如果你想要添加其他键盘布局，选择**添加布局**。</span><span class="sxs-lookup"><span data-stu-id="b1958-159">If you want to add another keyboard layout, select **Add layout**.</span></span> <span data-ttu-id="b1958-160">否则，请选择**跳过**。</span><span class="sxs-lookup"><span data-stu-id="b1958-160">Otherwise, select **Skip**.</span></span>   

     ![示例的第二个键盘布局屏幕，通过添加布局并跳到右下角中的选项的屏幕截图。](./media/RS5_Second_keyboard.png)  

5. <span data-ttu-id="b1958-162">选择**设置为工作或学校帐户**。</span><span class="sxs-lookup"><span data-stu-id="b1958-162">Select **Set up for work or school**.</span></span> <span data-ttu-id="b1958-163">然后选择**下一步**。</span><span class="sxs-lookup"><span data-stu-id="b1958-163">Then select **Next**.</span></span>  

     ![示例屏幕截图中的 \* \* 你希望如何设置？ \* \* 屏幕上，突出到集的选项会显示为工作或学校帐户。](./media/RS5_Choose_Setup_Type.png)  

6. <span data-ttu-id="b1958-165">键入电子邮件地址与您的学校管理员或注册管理器帐户相关联。</span><span class="sxs-lookup"><span data-stu-id="b1958-165">Type the email address associated with your school's admin or enrollment manager account.</span></span> <span data-ttu-id="b1958-166">然后选择**下一步**。</span><span class="sxs-lookup"><span data-stu-id="b1958-166">Then select **Next**.</span></span>  

     ![示例屏幕截图中的 \* \* 登录 Microsoft \* \* 屏幕上，使用 Microsoft 徽标和电子邮件字段为空。](./media/RS5_Sign_In.png)  

7. <span data-ttu-id="b1958-168">输入帐户的密码。</span><span class="sxs-lookup"><span data-stu-id="b1958-168">Enter the password for the account.</span></span> <span data-ttu-id="b1958-169">然后选择**下一步**。</span><span class="sxs-lookup"><span data-stu-id="b1958-169">Then select **Next**.</span></span>  

     ![示例屏幕截图中的 \* \* 输入密码 \* \* 屏幕，使用组织的徽标和空密码字段。](./media/RS5_Enter_Password.png)  



8. <span data-ttu-id="b1958-171">选择设备的隐私设置。</span><span class="sxs-lookup"><span data-stu-id="b1958-171">Choose privacy settings for the device.</span></span> <span data-ttu-id="b1958-172">配置这些设置，根据您的学校的策略。</span><span class="sxs-lookup"><span data-stu-id="b1958-172">Configure these settings based on your school's policies.</span></span> <span data-ttu-id="b1958-173">某些设置，如**语音识别**并**位置**默认开启。</span><span class="sxs-lookup"><span data-stu-id="b1958-173">Some of the settings, such as **Speech recognition** and **Location** are turned on by default.</span></span>  

     ![默认情况下打开示例屏幕截图中列出的隐私设置选项，与某些设置。](./media/RS5_Choose_Settings.png)  


9. <span data-ttu-id="b1958-175">选择**接受**以完成设备设置。</span><span class="sxs-lookup"><span data-stu-id="b1958-175">Select **Accept** to finish device setup.</span></span> <span data-ttu-id="b1958-176">可能需要几分钟才能完成安装，请尽情以开始另一台设备上的安装程序。</span><span class="sxs-lookup"><span data-stu-id="b1958-176">It might take a few minutes to complete setup, so feel free to begin setup on another device.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="b1958-177">后续步骤</span><span class="sxs-lookup"><span data-stu-id="b1958-177">Next steps</span></span>
<span data-ttu-id="b1958-178">现在，设备学校用于设置并准备就绪后，了解如何更新、 监视和解决这些问题。</span><span class="sxs-lookup"><span data-stu-id="b1958-178">Now that devices are set up and ready for school use, learn how to update, monitor, and troubleshoot them.</span></span>   
* <span data-ttu-id="b1958-179">将分配[组管理员](group-admin-delegate.md)可帮助您管理您的学校内或跨地区的教室设置</span><span class="sxs-lookup"><span data-stu-id="b1958-179">Assign [group admins](group-admin-delegate.md) to help you manage classroom settings within your school or across the district</span></span>
* <span data-ttu-id="b1958-180">查看所有[Windows 设置](all-edu-settings-windows.md)，可以调整</span><span class="sxs-lookup"><span data-stu-id="b1958-180">Review all [Windows settings](all-edu-settings-windows.md) that you can adjust</span></span>
* <span data-ttu-id="b1958-181">了解如何[设置继承](settings-inheritance.md)影响新组</span><span class="sxs-lookup"><span data-stu-id="b1958-181">Learn how [settings inheritance](settings-inheritance.md) affects new groups</span></span>
* <span data-ttu-id="b1958-182">审阅[报表](what-are-reports.md)地找出并对错误进行故障排除</span><span class="sxs-lookup"><span data-stu-id="b1958-182">Review [reports](what-are-reports.md) to pinpoint and troubleshoot errors</span></span>  

 
