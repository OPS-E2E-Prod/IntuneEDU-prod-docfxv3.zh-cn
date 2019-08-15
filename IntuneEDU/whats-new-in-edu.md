---
title: 新增功能
titleSuffix: Intune for Education
description: 了解 Intune for Education 中最近发布的内容。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 7d8dfd82-8cee-4874-85f6-edaf84e49c4c
searchScope:
- IntuneEDU
.#ms.devlang: ''
ms.openlocfilehash: 258768b919d824e511452c3974b2c86c61c87a3d
ms.sourcegitcommit: 1791319c6f8a8fb2c35cf9620ca4785c421b2071
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/19/2019
ms.locfileid: "68329428"
---
# <a name="whats-new-in-intune-for-education"></a><span data-ttu-id="3d10e-103">Intune for Education 中的新增功能</span><span class="sxs-lookup"><span data-stu-id="3d10e-103">What's new in Intune for Education</span></span>
<span data-ttu-id="3d10e-104">了解 Intune for Education 中的新增功能。</span><span class="sxs-lookup"><span data-stu-id="3d10e-104">Learn what’s new in Intune for Education.</span></span> <span data-ttu-id="3d10e-105">了解以前版本中的即将发生的更改、产品通知和功能。</span><span class="sxs-lookup"><span data-stu-id="3d10e-105">Find out about upcoming changes, product notices, and features from previous releases.</span></span>


## <a name="july-2019"></a><span data-ttu-id="3d10e-106">2019年7月</span><span class="sxs-lookup"><span data-stu-id="3d10e-106">July 2019</span></span>  

### <a name="perform-bulk-rename"></a><span data-ttu-id="3d10e-107">执行批量重命名</span><span class="sxs-lookup"><span data-stu-id="3d10e-107">Perform bulk rename</span></span>  
<span data-ttu-id="3d10e-108">一次最多可重命名100设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-108">Rename up to 100 devices at a time.</span></span> <span data-ttu-id="3d10e-109">若要进行批量选择, 可以从 "设备" 列表中手动选择设备, 或按住**Ctrl**或**Command**键同时选择多个设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-109">To make a bulk selection, you can manually choose devices from the devices list, or hold down the **Ctrl** or **Command** key to select multiple devices at once.</span></span>  

<span data-ttu-id="3d10e-110">然后, 你可以将命名模板应用于所选设备组, 其中包含由唯一标识符追加的自定义前缀。</span><span class="sxs-lookup"><span data-stu-id="3d10e-110">You can then apply a naming template to the group of selected devices, which includes a custom prefix appended by a unique identifier.</span></span> <span data-ttu-id="3d10e-111">唯一标识符可以是序列号、计数器或 Wi-fi MAC 地址。</span><span class="sxs-lookup"><span data-stu-id="3d10e-111">The unique identifier can be a serial number, a counter, or a Wi-Fi MAC address.</span></span>  

 
 ![设备页的屏幕截图, 批量重命名, 选择了计数器标识符。](./media/edu-bulk-rename-1907.png)  


 !["设备" 页的屏幕截图, 正在进行批量重命名, 并且选择了序列号。](./media/edu-bulk-rename-1907-01.png)   


## <a name="june-2019"></a><span data-ttu-id="3d10e-114">2019年6月</span><span class="sxs-lookup"><span data-stu-id="3d10e-114">June 2019</span></span>  

### <a name="perform-bulk-actions"></a><span data-ttu-id="3d10e-115">执行批量操作</span><span class="sxs-lookup"><span data-stu-id="3d10e-115">Perform bulk actions</span></span> 
<span data-ttu-id="3d10e-116">一次对多达100台设备执行某些远程操作。</span><span class="sxs-lookup"><span data-stu-id="3d10e-116">Perform certain remote actions on up to 100 devices at a time.</span></span>  <span data-ttu-id="3d10e-117">若要进行批量选择, 可以从 "设备" 列表中手动选择设备, 或按住**Ctrl**或**Command**键同时选择多个设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-117">To make a bulk selection, you can manually choose devices from the devices list, or hold down the **Ctrl** or **Command** key to select multiple devices at once.</span></span> 
 
 ![选择了多个设备的示例图像和批量重启确认。](./media/1906-remote-bulk.png)  

<span data-ttu-id="3d10e-119">Intune for Education 将为以下设备操作支持批量功能:</span><span class="sxs-lookup"><span data-stu-id="3d10e-119">Intune for Education will support the bulk functionality for the following device actions:</span></span>  

* <span data-ttu-id="3d10e-120">“重新启动”</span><span class="sxs-lookup"><span data-stu-id="3d10e-120">Restart</span></span>  
* <span data-ttu-id="3d10e-121">恢复出厂设置</span><span class="sxs-lookup"><span data-stu-id="3d10e-121">Factory reset</span></span>  
* <span data-ttu-id="3d10e-122">同步</span><span class="sxs-lookup"><span data-stu-id="3d10e-122">Sync</span></span>  
* <span data-ttu-id="3d10e-123">Autopilot 重置</span><span class="sxs-lookup"><span data-stu-id="3d10e-123">Autopilot Reset</span></span>  
* <span data-ttu-id="3d10e-124">DELETE</span><span class="sxs-lookup"><span data-stu-id="3d10e-124">Delete</span></span>   

 ![批量同步确认的示例图像。](./media/1906-remote-bulk-selection.png)  

### <a name="easier-migration-to-intune-for-education-licenses"></a><span data-ttu-id="3d10e-126">更轻松地迁移到 Intune for Education 许可证</span><span class="sxs-lookup"><span data-stu-id="3d10e-126">Easier migration to Intune for Education licenses</span></span>  
<span data-ttu-id="3d10e-127">注册 Intune for Education 之后, Intune 会自动将 "所有设备" 组中的某些设置配置为学校推荐的值。</span><span class="sxs-lookup"><span data-stu-id="3d10e-127">After you sign up for Intune for Education, Intune automatically configures some settings in the All devices group with values that are recommended for schools.</span></span> <span data-ttu-id="3d10e-128">现在, 当你将 Intune for Education 添加到已具有 Intune 订阅的租户时, 你将看到推荐的策略, 但 Intune 将不会自动分配它们。</span><span class="sxs-lookup"><span data-stu-id="3d10e-128">Now when you add Intune for Education to a tenant that already has an Intune subscription, you'll see the recommended policies, but Intune won't assign them automatically.</span></span> <span data-ttu-id="3d10e-129">此更改将确保不会对现有环境进行不必要的更改。</span><span class="sxs-lookup"><span data-stu-id="3d10e-129">This change will ensure that no unwanted changes are made to your existing environment.</span></span>  

### <a name="new-permissions-for-assigned-group-admins"></a><span data-ttu-id="3d10e-130">已分配的组管理员的新权限</span><span class="sxs-lookup"><span data-stu-id="3d10e-130">New permissions for assigned group admins</span></span>  
<span data-ttu-id="3d10e-131">Intune 的内置学校管理员角色现在具有对托管应用程序的创建、读取、更新和删除 (CRUD) 权限。</span><span class="sxs-lookup"><span data-stu-id="3d10e-131">Intune's built-in School Administrator role now has create, read, update, and delete (CRUD) permissions for Managed Apps.</span></span> <span data-ttu-id="3d10e-132">此更新意味着, 如果将分配为 Intune for Education 中的组管理员, 则现在可以创建、查看、更新和删除 iOS MDM Push Certificate、iOS MDM 服务器令牌和 iOS VPP 令牌以及[拥有的所有现有权限](https://docs.microsoft.com/intune-education/group-admin-delegate#group-admin-permissions)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-132">This update means that if you're assigned as a group admin in Intune for Education, you can now create, view, update, and delete the iOS MDM Push Certificate, iOS MDM server tokens, and iOS VPP tokens along with [all of the existing permissions you have](https://docs.microsoft.com/intune-education/group-admin-delegate#group-admin-permissions).</span></span> <span data-ttu-id="3d10e-133">若要执行这些操作, 请转到**租户设置** > **iOS 设备管理**。</span><span class="sxs-lookup"><span data-stu-id="3d10e-133">To take any of these actions, go to **Tenant settings** > **iOS Device Management**.</span></span>  

### <a name="new-deployment-documentation"></a><span data-ttu-id="3d10e-134">新的部署文档</span><span class="sxs-lookup"><span data-stu-id="3d10e-134">New deployment documentation</span></span>  
<span data-ttu-id="3d10e-135">在我们文档的 "[注册" 部分](https://docs.microsoft.com/intune-education/add-devices-windows)中, 你将找到一些新信息, 帮助你根据你的学校环境和设置需求比较设置 School Pc 和 Windows Autopilot。</span><span class="sxs-lookup"><span data-stu-id="3d10e-135">In the [enrollment section](https://docs.microsoft.com/intune-education/add-devices-windows) of our documentation, you'll find new information to help you compare Set up School PCs and Windows Autopilot based on your school’s environment and setup needs.</span></span> <span data-ttu-id="3d10e-136">使用此信息来确定何时为设备设置使用每个选项, 或同时使用这两种选项。</span><span class="sxs-lookup"><span data-stu-id="3d10e-136">Use this information to decide when to use each option, or both, for device setup.</span></span> 

## <a name="may-2019"></a><span data-ttu-id="3d10e-137">可能为2019</span><span class="sxs-lookup"><span data-stu-id="3d10e-137">May 2019</span></span>   

### <a name="distinguish-between-online-and-offline-licensed-microsoft-store-for-education-apps"></a><span data-ttu-id="3d10e-138">区分 Microsoft Store 教育应用的联机和脱机许可</span><span class="sxs-lookup"><span data-stu-id="3d10e-138">Distinguish between online and offline-licensed Microsoft Store for Education apps</span></span>   

<span data-ttu-id="3d10e-139">你将能够查看教育应用 Microsoft Store 是否具有联机或脱机许可证。</span><span class="sxs-lookup"><span data-stu-id="3d10e-139">You'll be able to see if a Microsoft Store for Education app has an online or offline license.</span></span> <span data-ttu-id="3d10e-140">Intune for Education 将在快速配置和应用的详细信息页上显示许可证类型, 使你能够更轻松地管理应用并将其部署到正确的组。</span><span class="sxs-lookup"><span data-stu-id="3d10e-140">Intune for Education will show the license type in Express Configuration and on the app's details page, making it easier for you to manage and deploy apps to the correct groups.</span></span> <span data-ttu-id="3d10e-141">在用户登录设备并需要连接到 Microsoft Store 以使用时, 具有联机许可证的应用会开始安装。</span><span class="sxs-lookup"><span data-stu-id="3d10e-141">Apps with online licenses begin installing after a user signs in to a device and require a connection to Microsoft Store to use.</span></span> <span data-ttu-id="3d10e-142">在无需用户登录的情况下安装具有脱机许可证的应用, 并且无需连接到 Microsoft Store 即可使用。</span><span class="sxs-lookup"><span data-stu-id="3d10e-142">Apps with offline licenses install without the need for user sign-in and don't require a connection to Microsoft Store to use.</span></span>  

### <a name="new-ios-settings"></a><span data-ttu-id="3d10e-143">新 iOS 设置</span><span class="sxs-lookup"><span data-stu-id="3d10e-143">New iOS settings</span></span>  

<span data-ttu-id="3d10e-144">添加了新设置, 使你能够更好地控制 iOS 课堂应用。</span><span class="sxs-lookup"><span data-stu-id="3d10e-144">New settings have been added to give you more control over the iOS Classroom app.</span></span>  

### <a name="apply-an-ios-device-naming-template"></a><span data-ttu-id="3d10e-145">应用 iOS 设备命名模板</span><span class="sxs-lookup"><span data-stu-id="3d10e-145">Apply an iOS device naming template</span></span>  

<span data-ttu-id="3d10e-146">我们添加了新的命名设置, 以帮助你对 iOS 设备进行分组和标识。</span><span class="sxs-lookup"><span data-stu-id="3d10e-146">We've added new naming settings to help you group and identify your iOS devices.</span></span> <span data-ttu-id="3d10e-147">在 iOS 注册和 MDM 服务器令牌安装期间, Intune for Education 会自动将每个设备的名称命名为唯一的设备序列号。</span><span class="sxs-lookup"><span data-stu-id="3d10e-147">During iOS enrollment and MDM server token setup, Intune for Education will automatically name each of your devices with their unique device serial number.</span></span> <span data-ttu-id="3d10e-148">然后, 可以将自定义名称 (如 Contoso 或 Math1) 添加到前缀。</span><span class="sxs-lookup"><span data-stu-id="3d10e-148">You can then add a custom name, such as  Contoso or Math1, to the prefix.</span></span> <span data-ttu-id="3d10e-149">如果自定义名称, 则设备序列号会附加到其末尾。</span><span class="sxs-lookup"><span data-stu-id="3d10e-149">If you customize the name, the device serial number is attached to the end of it.</span></span> <span data-ttu-id="3d10e-150">例如：Contoso012a345b67c8.</span><span class="sxs-lookup"><span data-stu-id="3d10e-150">For example: Contoso012a345b67c8.</span></span> <span data-ttu-id="3d10e-151">配置或更新 MDM 服务器令牌的命名模板时, 与该令牌关联的所有设备都将重命名–现有设备和在应用命名模板之后注册的设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-151">When you configure or update a naming template for an MDM Server Token, all devices associated with that token are renamed – both existing devices and those enrolled after the naming template is applied.</span></span> 

## <a name="april-2019"></a><span data-ttu-id="3d10e-152">2019年4月</span><span class="sxs-lookup"><span data-stu-id="3d10e-152">April 2019</span></span>  

### <a name="updated-ios-settings-names-and-added-more-tooltips"></a><span data-ttu-id="3d10e-153">更新了 iOS 设置名称并添加了更多工具提示</span><span class="sxs-lookup"><span data-stu-id="3d10e-153">Updated iOS settings names and added more tooltips</span></span>  
<span data-ttu-id="3d10e-154">在 Intune for Education 中修改了许多 iOS 设置名称、工具提示和类别, 使设置更易于查找和理解。</span><span class="sxs-lookup"><span data-stu-id="3d10e-154">We revised many of the iOS setting names, tooltips, and categories in Intune for Education to make settings easier to find and understand.</span></span> <span data-ttu-id="3d10e-155">有关这些设置的详细列表, 请参阅[Intune for Education 中的 iOS 设备设置](all-edu-settings-ios.md)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-155">For a detailed list of these settings, see [iOS device settings in Intune for Education](all-edu-settings-ios.md).</span></span>  

### <a name="refined-list-of-ios-settings-in-express-configuration"></a><span data-ttu-id="3d10e-156">快速配置中 iOS 设置的精选列表</span><span class="sxs-lookup"><span data-stu-id="3d10e-156">Refined list of iOS settings in Express Configuration</span></span>   
<span data-ttu-id="3d10e-157">我们调整了[快速配置中 iOS 设置的列表](edu-express-config-settings-ios.md), 以便你可以更快地设置设备和组。</span><span class="sxs-lookup"><span data-stu-id="3d10e-157">We adjusted the [list of iOS settings in Express Configuration](edu-express-config-settings-ios.md) so that you can get your devices and groups set up even faster.</span></span> <span data-ttu-id="3d10e-158">你会看到, 一些设置已移出快速配置, 并在中移动了新设置。</span><span class="sxs-lookup"><span data-stu-id="3d10e-158">You'll see that some settings moved out of Express Configuration, and new settings moved in.</span></span> <span data-ttu-id="3d10e-159">你仍可以在 "**设置** > **iOS 设备设置**"**组** > 中配置已删除的设置。</span><span class="sxs-lookup"><span data-stu-id="3d10e-159">The removed settings are still available for you to configure in **Groups** > **Settings** > **iOS Device Settings**.</span></span> <span data-ttu-id="3d10e-160">有关 Intune for Education 中的设备设置的完整列表, 请参阅[iOS 设备设置](all-edu-settings-ios.md)和[Windows 10 设备设置](all-edu-settings-windows.md)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-160">For the full list of device settings in Intune for Education, see [iOS device settings](all-edu-settings-ios.md) and [Windows 10 device settings](all-edu-settings-windows.md).</span></span>  

###  <a name="new-settings-for-windows-10-devices"></a><span data-ttu-id="3d10e-161">适用于 Windows 10 设备的新设置</span><span class="sxs-lookup"><span data-stu-id="3d10e-161">New settings for Windows 10 devices</span></span>  
<span data-ttu-id="3d10e-162">有几个新的 Windows 10 设备设置。</span><span class="sxs-lookup"><span data-stu-id="3d10e-162">There are several new Windows 10 device settings.</span></span> <span data-ttu-id="3d10e-163">下面是一些你现在可以在 Intune for Education 中配置的设置:</span><span class="sxs-lookup"><span data-stu-id="3d10e-163">Here's just a few of the settings you can now configure in Intune for Education:</span></span>
* <span data-ttu-id="3d10e-164">Windows 更新通知:此设置允许你选择用户是否看到有关 Windows 更新的通知。</span><span class="sxs-lookup"><span data-stu-id="3d10e-164">Windows Update notifications: This setting lets you choose whether or not users see notifications about Windows Updates.</span></span>  
* <span data-ttu-id="3d10e-165">手动 Windows 更新:此设置允许你选择用户是否有权访问 Windows 更新扫描、下载和安装功能。</span><span class="sxs-lookup"><span data-stu-id="3d10e-165">Manual Windows Update: This setting lets you choose whether or not users have access to the Windows Update scan, download, and install features.</span></span>  


## <a name="february-2019"></a><span data-ttu-id="3d10e-166">2019年2月</span><span class="sxs-lookup"><span data-stu-id="3d10e-166">February 2019</span></span>  

### <a name="set-custom-wallpaper-and-lock-screen-images-for-your-ios-devices"></a><span data-ttu-id="3d10e-167">为 iOS 设备设置自定义墙纸和锁定屏幕图像</span><span class="sxs-lookup"><span data-stu-id="3d10e-167">Set custom wallpaper and lock screen images for your iOS devices</span></span>  
<span data-ttu-id="3d10e-168">你现在可以使用 Intune for Education 在学校设备上设置自定义墙纸和锁定屏幕图像。</span><span class="sxs-lookup"><span data-stu-id="3d10e-168">You can now use Intune for Education to set custom wallpaper and lock screen images on school devices.</span></span> <span data-ttu-id="3d10e-169">若要上传映像, 请参阅对**iOS 设备设置** > **墙纸和锁定屏幕图像**进行**分组** > 。</span><span class="sxs-lookup"><span data-stu-id="3d10e-169">To upload your images, go to **Groups** > **iOS Device Settings** > **Wallpaper and lock screen images**.</span></span>  

   ![IOS 设备设置、自定义墙纸和锁定屏幕图像的屏幕截图。](./media/ios-1901-custom-image-settings.png)  


## <a name="january-2019"></a><span data-ttu-id="3d10e-171">2019年1月</span><span class="sxs-lookup"><span data-stu-id="3d10e-171">January 2019</span></span>  

### <a name="set-up-ios-devices-with-shared-ipad-features"></a><span data-ttu-id="3d10e-172">设置具有共享 iPad 功能的 iOS 设备</span><span class="sxs-lookup"><span data-stu-id="3d10e-172">Set up iOS devices with Shared iPad features</span></span>
<span data-ttu-id="3d10e-173">在 Intune for Education 为 iOS 设备注册配置设置时, 你现在可以选择将 iOS 设备配置为启用共享 iPad 功能注册。</span><span class="sxs-lookup"><span data-stu-id="3d10e-173">When configuring settings in Intune for Education for iOS device enrollment, you now have the option to configure your iOS devices to enroll with Shared iPad features enabled.</span></span>  <span data-ttu-id="3d10e-174">共享 iPad 是一项 iOS 功能, 要求学生和教师使用托管 Apple ID 登录到学校设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-174">Shared iPad is an iOS feature that requires students and teachers to sign in to school devices with a Managed Apple ID.</span></span> <span data-ttu-id="3d10e-175">他们可以登录和注销 school 中任何已启用的设备, 以访问已保存和正在进行的工作、应用程序和任务。</span><span class="sxs-lookup"><span data-stu-id="3d10e-175">They can sign in and out of any enabled device in the school to access saved and in-progress work, apps, and tasks.</span></span> <span data-ttu-id="3d10e-176">有关 Intune for Education 中共享 iPad 的详细信息, 请参阅[共享 ipad 配置](setup-ios-device-management.md#shared-ipad-configuration)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-176">For more information about Shared iPad in Intune for Education, see [Shared iPad configuration](setup-ios-device-management.md#shared-ipad-configuration).</span></span>  

### <a name="new-settings-for-windows-10-devices"></a><span data-ttu-id="3d10e-177">适用于 Windows 10 设备的新设置</span><span class="sxs-lookup"><span data-stu-id="3d10e-177">New settings for Windows 10 devices</span></span>  
<span data-ttu-id="3d10e-178">我们添加了新的设置, 使你能够更好地控制安全性、Windows 更新、设备登录和浏览器体验等区域。</span><span class="sxs-lookup"><span data-stu-id="3d10e-178">We've added new settings to give you more control over areas such as security, Windows updates, device sign-in, and browser experience.</span></span> <span data-ttu-id="3d10e-179">下面只是你将看到的几个新设置:</span><span class="sxs-lookup"><span data-stu-id="3d10e-179">Here are just a few new settings you'll see this month:</span></span>  

* <span data-ttu-id="3d10e-180">**配置首选 Azure Active Directory 租户域**:此设置允许学生登录到无租户域名的设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-180">**Configure preferred Azure Active Directory tenant domain**: This setting permits students to sign in to a device without a tenant domain name.</span></span> <span data-ttu-id="3d10e-181">学生只能用其别名快速轻松地登录。</span><span class="sxs-lookup"><span data-stu-id="3d10e-181">Students can sign in quickly and easily with just their alias.</span></span>  

* <span data-ttu-id="3d10e-182">**配置新选项卡页**:此设置允许你选择学生在 Microsoft Edge 中添加选项卡时打开的页面。</span><span class="sxs-lookup"><span data-stu-id="3d10e-182">**Configure new tab page**: This setting lets you choose the page that opens when students add a tab in Microsoft Edge.</span></span> <span data-ttu-id="3d10e-183">新选项卡可以打开一个空白页或自定义的页, 例如您的学校的主页。</span><span class="sxs-lookup"><span data-stu-id="3d10e-183">New tabs can open a blank page or a custom one, such as your school's home page.</span></span>  

* <span data-ttu-id="3d10e-184">**切换到 S 模式**:此设置使管理员能够在 S 模式下从 Windows 10 切换设备, 或阻止学生将他们自己的设备从 S 模式切换。</span><span class="sxs-lookup"><span data-stu-id="3d10e-184">**Switch out of S Mode**: This setting lets admins switch devices out of Windows 10 in S Mode, or prevents students from switching their own devices out of S Mode.</span></span>    

### <a name="updated-windows-settings-names-and-added-useful-tooltips"></a><span data-ttu-id="3d10e-185">更新了 Windows 设置名称并添加了有用的工具提示</span><span class="sxs-lookup"><span data-stu-id="3d10e-185">Updated Windows settings names and added useful tooltips</span></span>  
<span data-ttu-id="3d10e-186">在 Intune for Education 中修改了许多设置名称和工具提示, 使其更易于查找和理解。</span><span class="sxs-lookup"><span data-stu-id="3d10e-186">We revised many of the setting names and tooltips in Intune for Education to make them easier to find and understand.</span></span> <span data-ttu-id="3d10e-187">有关每个设置的更多详细信息, 请参阅[Intune for Education 中的 Windows 10 设备设置](all-edu-settings-windows.md)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-187">For even more details about each setting, see [Windows 10 device settings in Intune for Education](all-edu-settings-windows.md).</span></span>  

### <a name="rename-windows-devices"></a><span data-ttu-id="3d10e-188">重命名 Windows 设备</span><span class="sxs-lookup"><span data-stu-id="3d10e-188">Rename Windows devices</span></span>  
<span data-ttu-id="3d10e-189">从 Intune for Education 门户远程重命名任何 Windows 10 (版本1803或更高版本) 设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-189">Rename any Windows 10 (version 1803 or later) device remotely from the Intune for Education portal.</span></span> <span data-ttu-id="3d10e-190">若要重命名, 请跳到 "**设备**", 然后选择一个设备 >**重命名设备**。</span><span class="sxs-lookup"><span data-stu-id="3d10e-190">To rename, go to **Devices** and select a device > **Rename device**.</span></span> <span data-ttu-id="3d10e-191">你还可以从 "**设备详细信息**" 页重命名设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-191">You can also rename a device from the **Device details** page.</span></span>  

## <a name="november-2018"></a><span data-ttu-id="3d10e-192">2018年11月</span><span class="sxs-lookup"><span data-stu-id="3d10e-192">November 2018</span></span>  

### <a name="remote-autopilot-reset"></a><span data-ttu-id="3d10e-193">远程 Autopilot 重置</span><span class="sxs-lookup"><span data-stu-id="3d10e-193">Remote Autopilot Reset</span></span> 
<span data-ttu-id="3d10e-194">你现在可以使用 Intune for Education 门户远程调用 Autopilot Reset。</span><span class="sxs-lookup"><span data-stu-id="3d10e-194">You can now invoke Autopilot Reset remotely using the Intune for Education portal.</span></span> <span data-ttu-id="3d10e-195">Autopilot Reset 会删除所有用户数据, 包括用户安装的应用和个人设置并使设备在 Intune 中注册, 使设备与所有最新的应用、策略和设置保持同步。</span><span class="sxs-lookup"><span data-stu-id="3d10e-195">Autopilot Reset removes all user data including user-installed apps and personal settings and keeps the device enrolled in Intune so the device is kept up-to-date with all the latest apps, policies, and settings.</span></span> <span data-ttu-id="3d10e-196">利用此功能, 你可以快速擦除和重新配置学生的 Pc 批量, 为新的一年做好准备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-196">With this feature, you can quickly wipe and reconfigure students' PCs in bulk to prepare them for a new school year.</span></span> <span data-ttu-id="3d10e-197">[在此处](autopilot-reset.md)了解有关 Autopilot 重置的详细信息。</span><span class="sxs-lookup"><span data-stu-id="3d10e-197">Learn more about Autopilot Reset [here](autopilot-reset.md).</span></span>

### <a name="new-features-for-ios-management"></a><span data-ttu-id="3d10e-198">IOS 管理的新增功能</span><span class="sxs-lookup"><span data-stu-id="3d10e-198">New features for iOS management</span></span>
- <span data-ttu-id="3d10e-199">Intune for Education 现在显示你的 Apple School Manager VPP 令牌的位置信息, 因此你可以轻松地从 Intune for Education 和 Apple 学校管理器中识别你的 VPP 令牌。</span><span class="sxs-lookup"><span data-stu-id="3d10e-199">Intune for Education now displays location information for your Apple School Manager VPP tokens, so you can easily identify your VPP tokens from both Intune for Education and Apple School Manager.</span></span> 
- <span data-ttu-id="3d10e-200">可以在 Intune for Education 中提供 VPP 令牌别名, 以便于进行标记和组织。</span><span class="sxs-lookup"><span data-stu-id="3d10e-200">You can give your VPP tokens nicknames in Intune for Education for easy labeling and organization.</span></span> 
- <span data-ttu-id="3d10e-201">设置 MDM 服务器令牌后, 对 iOS 设备进行注册的速度将更快。</span><span class="sxs-lookup"><span data-stu-id="3d10e-201">Enrollment is now even faster for your iOS devices when you set up an MDM Server Token.</span></span> <span data-ttu-id="3d10e-202">Intune for Education 自动配置注册设置, 因此与 MDM 服务器令牌关联的设备具有更少的设置助理屏幕来点击。</span><span class="sxs-lookup"><span data-stu-id="3d10e-202">Intune for Education automatically configures enrollment settings, so the devices associated with the MDM Server Token have fewer Setup Assistant screens to tap through.</span></span> 
 
### <a name="delete-device"></a><span data-ttu-id="3d10e-203">删除设备</span><span class="sxs-lookup"><span data-stu-id="3d10e-203">Delete Device</span></span>
<span data-ttu-id="3d10e-204">你现在可以在 Intune for Education 门户中删除设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-204">You can now delete a device in the Intune for Education portal.</span></span> <span data-ttu-id="3d10e-205">删除设备:</span><span class="sxs-lookup"><span data-stu-id="3d10e-205">Deleting a device:</span></span>
- <span data-ttu-id="3d10e-206">在 Intune 中取消注册设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-206">unenrolls the device in Intune.</span></span>
- <span data-ttu-id="3d10e-207">从 Azure Active Directory 删除设备记录, 因此设备不再属于您的环境。</span><span class="sxs-lookup"><span data-stu-id="3d10e-207">removes the device record from Azure Active Directory so the device is no longer part of your environment.</span></span>
 
### <a name="immersive-reader-for-all-tenants"></a><span data-ttu-id="3d10e-208">适用于所有租户的沉浸式读者</span><span class="sxs-lookup"><span data-stu-id="3d10e-208">Immersive Reader for all Tenants</span></span> 
<span data-ttu-id="3d10e-209">当你注册 Intune for Education 时, 适用于教育清单的 Windows 应用商店将获取沉浸式读者无限制的许可证。</span><span class="sxs-lookup"><span data-stu-id="3d10e-209">Your Windows Store for Education inventory gets unlimited licenses for Immersive reader when you sign up for Intune for Education.</span></span> <span data-ttu-id="3d10e-210">沉浸式读者是一个学习工具, 它为所有年龄和能力的学习者创建了一个具有辅助功能和理解的阅读体验。</span><span class="sxs-lookup"><span data-stu-id="3d10e-210">Immersive Reader is a learning tool that creates a reading experience with accessibility and comprehensions for learners of all ages and abilities.</span></span> <span data-ttu-id="3d10e-211">[在此处](https://www.onenote.com/learningtools)详细了解沉浸式读者。</span><span class="sxs-lookup"><span data-stu-id="3d10e-211">Learn more about Immersive Reader [here](https://www.onenote.com/learningtools).</span></span>
 
### <a name="effective-policy-page"></a><span data-ttu-id="3d10e-212">有效策略页</span><span class="sxs-lookup"><span data-stu-id="3d10e-212">Effective Policy Page</span></span>
<span data-ttu-id="3d10e-213">"有效策略" 页显示基于组成员身份应用于用户/设备组合的所有应用和设置。</span><span class="sxs-lookup"><span data-stu-id="3d10e-213">The effective policy page shows all apps and settings applied to a user/device combination based on group memberships.</span></span> <span data-ttu-id="3d10e-214">在此页中, 可以看到可能存在冲突的设置, 并解决问题。</span><span class="sxs-lookup"><span data-stu-id="3d10e-214">From this page, you can see settings that might be in conflict and troubleshoot the issues.</span></span> <span data-ttu-id="3d10e-215">可以通过两种方式访问 "有效策略" 页:</span><span class="sxs-lookup"><span data-stu-id="3d10e-215">You can reach the effective policy page in two ways:</span></span>
- <span data-ttu-id="3d10e-216">单击用户 >**中转到 "用户详细信息**" > 选择用户最近签入的设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-216">click on a user > **Go to user details** > choose a device that user has recently checked in with.</span></span>
- <span data-ttu-id="3d10e-217">单击设备 > "**中转到设备详细信息**" > 选择最近在该设备上签入的用户。</span><span class="sxs-lookup"><span data-stu-id="3d10e-217">click on a device > **Go to device details** > choose a user that has recently checked in on that device.</span></span>



## <a name="july-2018"></a><span data-ttu-id="3d10e-218">2018 年 7 月</span><span class="sxs-lookup"><span data-stu-id="3d10e-218">July 2018</span></span> 

### <a name="all-new-support-for-ios-classroom-devices"></a><span data-ttu-id="3d10e-219">所有新的 iOS 课堂设备支持</span><span class="sxs-lookup"><span data-stu-id="3d10e-219">All new support for iOS classroom devices</span></span>  

<span data-ttu-id="3d10e-220">Intune for Education 现在支持课堂上的 iOS 设备管理。</span><span class="sxs-lookup"><span data-stu-id="3d10e-220">Intune for Education now supports iOS device management in the classroom.</span></span> <span data-ttu-id="3d10e-221">我们向 Intune for Education 添加了新功能和页面, 使每个人都可以轻松地完成设置和管理过程。</span><span class="sxs-lookup"><span data-stu-id="3d10e-221">We've added new features and pages to Intune for Education to make the setup and management process easy for everyone involved.</span></span> <span data-ttu-id="3d10e-222">在仪表板中, 你将拥有成功设置、配置和注册设备所需的一切。</span><span class="sxs-lookup"><span data-stu-id="3d10e-222">From the dashboard, you'll have everything you need to successfully set up, configure, and enroll devices.</span></span>  

* <span data-ttu-id="3d10e-223">设置 iOS 设备管理:我们已添加了一个新页面, 其中包含[分步指南](setup-ios-device-management.md), 可帮助你快速将 Apple 帐户连接到 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="3d10e-223">Setup iOS device management: We've added a new page with [step-by-step guidance](setup-ios-device-management.md) to help you quickly connect your Apple accounts to Intune for Education.</span></span> <span data-ttu-id="3d10e-224">屏幕指示器使你可以清楚地看到必需和可选的步骤, 即你已成功完成的步骤和即将到期的步骤。</span><span class="sxs-lookup"><span data-stu-id="3d10e-224">On-screen indicators let you clearly see the required and optional steps, the ones you've successfully completed, and the ones that are nearing expiration.</span></span>
* <span data-ttu-id="3d10e-225">快速配置:就像我们的 Windows 10 体验, 但专为 iOS 设备定制一样,[适用于 ios 的 express 配置](express-configuration-intune-edu.md)有助于快速分配和更改应用和设置。</span><span class="sxs-lookup"><span data-stu-id="3d10e-225">Express configuration: Just like our Windows 10 experience, but tailored to iOS devices, [express configuration for iOS](express-configuration-intune-edu.md) helps you quickly assign and change apps and settings.</span></span> <span data-ttu-id="3d10e-226">选择一组用户或设备, 并从 Microsoft 推荐的设置中进行选择。</span><span class="sxs-lookup"><span data-stu-id="3d10e-226">Choose a group of users or devices and select from our Microsoft-recommended settings.</span></span> <span data-ttu-id="3d10e-227">这些[建议是预先](edu-express-config-settings-ios.md)选择的, 但你可以随时对其进行更改, 以匹配你的学校自己的策略。</span><span class="sxs-lookup"><span data-stu-id="3d10e-227">These [recommendations are preselected](edu-express-config-settings-ios.md), but you can change them at any time to match your school's own policies.</span></span>  
* <span data-ttu-id="3d10e-228">应用和设置:我们添加了单独的应用和设备设置视图, 帮助你专注于[iOS](all-edu-settings-ios.md)或[Windows 10](all-edu-settings-windows.md)设备管理。</span><span class="sxs-lookup"><span data-stu-id="3d10e-228">Apps and settings: We've added separate app and device setting views to help you focus on either [iOS](all-edu-settings-ios.md) or [Windows 10](all-edu-settings-windows.md) device management.</span></span> <span data-ttu-id="3d10e-229">添加[APPLE vpp 支持](add-vpp-apps-ios.md)后, 你可以将你的 VPP 购买的应用与 Intune for Education 同步, 并直接从仪表板分配它们。</span><span class="sxs-lookup"><span data-stu-id="3d10e-229">With added [Apple VPP support](add-vpp-apps-ios.md), you can sync your VPP-purchased apps with Intune for Education and assign them directly from the dashboard.</span></span> 
* <span data-ttu-id="3d10e-230">动态分组:现在, 你可以将特定的设备平台规则应用于[动态组](create-groups.md#dynamic-groups)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-230">Dynamic grouping: Now you can apply a specific device platform rule to your [dynamic groups](create-groups.md#dynamic-groups).</span></span> <span data-ttu-id="3d10e-231">创建规则以应用于 Windows 10*或*iOS 设备上的设备或学生。</span><span class="sxs-lookup"><span data-stu-id="3d10e-231">Create a rule to apply to devices or students on Windows 10 *or* iOS devices.</span></span>  

<span data-ttu-id="3d10e-232">获取更多详细信息, 并了解如何在[Intune for Education](what-is-intune-for-education.md)文档中导航新的页面和工作流。</span><span class="sxs-lookup"><span data-stu-id="3d10e-232">Get more details and learn how to navigate new pages and workflows in the [Intune for Education](what-is-intune-for-education.md) documentation.</span></span>   

## <a name="january-2018"></a><span data-ttu-id="3d10e-233">2018 年 1 月</span><span class="sxs-lookup"><span data-stu-id="3d10e-233">January 2018</span></span>

### <a name="history-of-group-actions-taken-by-admins"></a><span data-ttu-id="3d10e-234">管理员执行的组操作的历史记录</span><span class="sxs-lookup"><span data-stu-id="3d10e-234">History of group actions taken by admins</span></span>

<span data-ttu-id="3d10e-235">你现在可以查看管理员用于更改已批准组的组管理员、应用和设置的所有操作的历史记录。</span><span class="sxs-lookup"><span data-stu-id="3d10e-235">You can now view a history of all actions taken by admins to change group admins, apps, and settings for their approved groups.</span></span> <span data-ttu-id="3d10e-236">可以在 "**组** > **历史记录**" 中找到此历史记录的日志。</span><span class="sxs-lookup"><span data-stu-id="3d10e-236">You can find the log of this history in **Groups** > **History**.</span></span>

### <a name="windows-defender-report"></a><span data-ttu-id="3d10e-237">Windows Defender 报表</span><span class="sxs-lookup"><span data-stu-id="3d10e-237">Windows Defender report</span></span>

<span data-ttu-id="3d10e-238">我们添加了一个新报表。</span><span class="sxs-lookup"><span data-stu-id="3d10e-238">We've added a new report.</span></span> <span data-ttu-id="3d10e-239">在 "报表" 页上, 您可以从报表列表中选择 " **Windows Defender 报表**"。</span><span class="sxs-lookup"><span data-stu-id="3d10e-239">On the Reports page, you can select **Windows Defender report** from the list of reports.</span></span> <span data-ttu-id="3d10e-240">这使你可以查看所有设备的 Windows Defender 设备运行状况状态。</span><span class="sxs-lookup"><span data-stu-id="3d10e-240">This lets you view Windows Defender device health status for all your devices.</span></span> <span data-ttu-id="3d10e-241">可以在[什么是报表？](what-are-reports.md) doc 中查看其外观。</span><span class="sxs-lookup"><span data-stu-id="3d10e-241">You can see what this looks like in the [What are reports?](what-are-reports.md) doc.</span></span>

### <a name="use-role-based-access-control-to-enable-group-admins"></a><span data-ttu-id="3d10e-242">使用基于角色的访问控制来启用组管理员</span><span class="sxs-lookup"><span data-stu-id="3d10e-242">Use role-based access control to enable group admins</span></span>

<span data-ttu-id="3d10e-243">你现在可以选择要管理其他组的设置的人员组。</span><span class="sxs-lookup"><span data-stu-id="3d10e-243">You can now choose groups of people to manage settings for other groups.</span></span> <span data-ttu-id="3d10e-244">例如, 你可能有一个名为 "*高中管理员*" 的组, 其中的成员是你所在地区的高中的管理员团队。</span><span class="sxs-lookup"><span data-stu-id="3d10e-244">For example, you could have a group called *High School Admins*, where the members are your team of admins for high schools in your district.</span></span> <span data-ttu-id="3d10e-245">高中*管理员*组可以被授予管理高中学生组设置的权限。</span><span class="sxs-lookup"><span data-stu-id="3d10e-245">The *High School Admins* group could be given permission to manage settings for groups of high school students.</span></span> <span data-ttu-id="3d10e-246">有关详细信息, 请参阅[什么是组？ doc](what-are-groups.md)。</span><span class="sxs-lookup"><span data-stu-id="3d10e-246">Find out more in the [What are groups? doc](what-are-groups.md).</span></span>

### <a name="user-and-device-search"></a><span data-ttu-id="3d10e-247">用户和设备搜索</span><span class="sxs-lookup"><span data-stu-id="3d10e-247">User and device search</span></span>

<span data-ttu-id="3d10e-248">我们已向边栏中添加了两个新选项:**用户**和**设备**。</span><span class="sxs-lookup"><span data-stu-id="3d10e-248">We've added two new options to the sidebar: **Users** and **Devices**.</span></span> <span data-ttu-id="3d10e-249">您可以使用它们搜索各个用户或设备, 并快速打开这些项目的**详细信息**。</span><span class="sxs-lookup"><span data-stu-id="3d10e-249">You can use these to search for individual users or devices, and quickly open the **Details** for these items.</span></span> <span data-ttu-id="3d10e-250">你可以将这些搜索添加到由边栏**查看所有** > **星形按钮 （收藏夹）** 以将它们添加到收藏夹列表中。</span><span class="sxs-lookup"><span data-stu-id="3d10e-250">You can add these searches to the sidebar by **See all** > **Star button (Favorite)** to add them to your favorites list.</span></span>

### <a name="remote-actions"></a><span data-ttu-id="3d10e-251">远程操作</span><span class="sxs-lookup"><span data-stu-id="3d10e-251">Remote actions</span></span>

<span data-ttu-id="3d10e-252">你现在可以对用户和设备执行远程操作。</span><span class="sxs-lookup"><span data-stu-id="3d10e-252">You can now take remote actions on your users and devices.</span></span> <span data-ttu-id="3d10e-253">选择要对其执行操作的设备, 然后从详细信息页中选择以下操作之一:</span><span class="sxs-lookup"><span data-stu-id="3d10e-253">Select the device you want to take action on, then choose one of the following actions from the details page:</span></span>

#### <a name="devices"></a><span data-ttu-id="3d10e-254">设备</span><span class="sxs-lookup"><span data-stu-id="3d10e-254">Devices</span></span>

- <span data-ttu-id="3d10e-255">“重新启动”</span><span class="sxs-lookup"><span data-stu-id="3d10e-255">Restart</span></span>
- <span data-ttu-id="3d10e-256">重置为出厂设置</span><span class="sxs-lookup"><span data-stu-id="3d10e-256">Reset to factory settings</span></span>
- <span data-ttu-id="3d10e-257">同步</span><span class="sxs-lookup"><span data-stu-id="3d10e-257">Sync</span></span>
- <span data-ttu-id="3d10e-258">从管理中删除</span><span class="sxs-lookup"><span data-stu-id="3d10e-258">Remove from management</span></span>

#### <a name="users"></a><span data-ttu-id="3d10e-259">Users</span><span class="sxs-lookup"><span data-stu-id="3d10e-259">Users</span></span>

- <span data-ttu-id="3d10e-260">重置密码</span><span class="sxs-lookup"><span data-stu-id="3d10e-260">Reset password</span></span>

<span data-ttu-id="3d10e-261">了解有关[远程操作](edu-device-remote-actions.md)的详细信息。</span><span class="sxs-lookup"><span data-stu-id="3d10e-261">Find out more about [remote actions](edu-device-remote-actions.md).</span></span>

### <a name="wi-fi-profiles"></a><span data-ttu-id="3d10e-262">Wi-Fi 配置文件</span><span class="sxs-lookup"><span data-stu-id="3d10e-262">Wi-Fi profiles</span></span>

<span data-ttu-id="3d10e-263">我们为**wi-fi 配置文件**的边栏添加了一个新选项。</span><span class="sxs-lookup"><span data-stu-id="3d10e-263">We've added a new option to the sidebar for **Wi-Fi profiles**.</span></span> <span data-ttu-id="3d10e-264">这允许你定义可分配给不同设备、用户和组的 Wi-fi 设置。</span><span class="sxs-lookup"><span data-stu-id="3d10e-264">This lets you define Wi-Fi settings that you can assign to different devices, users, and groups.</span></span>

## <a name="october-2017"></a><span data-ttu-id="3d10e-265">2017 年 10 月</span><span class="sxs-lookup"><span data-stu-id="3d10e-265">October 2017</span></span>

### <a name="dynamic-groups"></a><span data-ttu-id="3d10e-266">动态组</span><span class="sxs-lookup"><span data-stu-id="3d10e-266">Dynamic groups</span></span>

<span data-ttu-id="3d10e-267">定义规则, 我们将创建基于它们自动填充的组。</span><span class="sxs-lookup"><span data-stu-id="3d10e-267">Define rules and we'll create groups that automatically populate based on them.</span></span>

### <a name="new-app-status"></a><span data-ttu-id="3d10e-268">新应用程序状态</span><span class="sxs-lookup"><span data-stu-id="3d10e-268">New app status</span></span>

<span data-ttu-id="3d10e-269">添加应用时, 你现在会看到 "每个设备" 和 "每用户" 的应用安装状态。</span><span class="sxs-lookup"><span data-stu-id="3d10e-269">When adding an app, you'll now see a per-device and per-user status of app installs.</span></span>

### <a name="updated-details-pages"></a><span data-ttu-id="3d10e-270">更新的详细信息页</span><span class="sxs-lookup"><span data-stu-id="3d10e-270">Updated details pages</span></span>

<span data-ttu-id="3d10e-271">选择某个组中的用户或设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-271">Select a user or device in one of your groups.</span></span> <span data-ttu-id="3d10e-272">此时, 窗格将从屏幕的底部向上滑动, 使你可以获取有关该对象的详细信息, 以及已分配给该对象的应用和设置的状态。</span><span class="sxs-lookup"><span data-stu-id="3d10e-272">A pane will now slide up from the bottom of the screen that lets you get more information on that object, and the status of the apps and settings that you've assigned to it.</span></span>

## <a name="may-2017-initial-release"></a><span data-ttu-id="3d10e-273">5月 2017 (初始版本)</span><span class="sxs-lookup"><span data-stu-id="3d10e-273">May 2017 (initial release)</span></span>

### <a name="intune-for-education-is-now-available"></a><span data-ttu-id="3d10e-274">Intune for Education 现已可用!</span><span class="sxs-lookup"><span data-stu-id="3d10e-274">Intune for Education is now available!</span></span>

<span data-ttu-id="3d10e-275">已启动 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="3d10e-275">We have launched the Intune for Education portal.</span></span> <span data-ttu-id="3d10e-276">Intune for Education 是一种简化的体验, 适用于学校和教育组织管理 Windows 10 设备。</span><span class="sxs-lookup"><span data-stu-id="3d10e-276">Intune for Education is a streamlined experience for schools and educational organizations to manage Windows 10 devices.</span></span> <span data-ttu-id="3d10e-277">详细了解这些文档中的 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="3d10e-277">Find out more about Intune for Education in these docs.</span></span>

## <a name="next-steps"></a><span data-ttu-id="3d10e-278">后续步骤</span><span class="sxs-lookup"><span data-stu-id="3d10e-278">Next steps</span></span>

- [<span data-ttu-id="3d10e-279">了解有关 Intune for Education 的详细信息</span><span class="sxs-lookup"><span data-stu-id="3d10e-279">Find out more about Intune for Education</span></span>](what-is-intune-for-education.md)
- [<span data-ttu-id="3d10e-280">了解有关 Intune 的完整设备管理体验的详细信息</span><span class="sxs-lookup"><span data-stu-id="3d10e-280">Find out more about the full device management experience with Intune</span></span>](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)
