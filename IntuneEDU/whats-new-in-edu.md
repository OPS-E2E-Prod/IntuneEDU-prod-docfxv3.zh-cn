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
# <a name="whats-new-in-intune-for-education"></a>Intune for Education 中的新增功能
了解 Intune for Education 中的新增功能。 了解以前版本中的即将发生的更改、产品通知和功能。


## <a name="july-2019"></a>2019年7月  

### <a name="perform-bulk-rename"></a>执行批量重命名  
一次最多可重命名100设备。 若要进行批量选择, 可以从 "设备" 列表中手动选择设备, 或按住**Ctrl**或**Command**键同时选择多个设备。  

然后, 你可以将命名模板应用于所选设备组, 其中包含由唯一标识符追加的自定义前缀。 唯一标识符可以是序列号、计数器或 Wi-fi MAC 地址。  

 
 ![设备页的屏幕截图, 批量重命名, 选择了计数器标识符。](./media/edu-bulk-rename-1907.png)  


 !["设备" 页的屏幕截图, 正在进行批量重命名, 并且选择了序列号。](./media/edu-bulk-rename-1907-01.png)   


## <a name="june-2019"></a>2019年6月  

### <a name="perform-bulk-actions"></a>执行批量操作 
一次对多达100台设备执行某些远程操作。  若要进行批量选择, 可以从 "设备" 列表中手动选择设备, 或按住**Ctrl**或**Command**键同时选择多个设备。 
 
 ![选择了多个设备的示例图像和批量重启确认。](./media/1906-remote-bulk.png)  

Intune for Education 将为以下设备操作支持批量功能:  

* “重新启动”  
* 恢复出厂设置  
* 同步  
* Autopilot 重置  
* DELETE   

 ![批量同步确认的示例图像。](./media/1906-remote-bulk-selection.png)  

### <a name="easier-migration-to-intune-for-education-licenses"></a>更轻松地迁移到 Intune for Education 许可证  
注册 Intune for Education 之后, Intune 会自动将 "所有设备" 组中的某些设置配置为学校推荐的值。 现在, 当你将 Intune for Education 添加到已具有 Intune 订阅的租户时, 你将看到推荐的策略, 但 Intune 将不会自动分配它们。 此更改将确保不会对现有环境进行不必要的更改。  

### <a name="new-permissions-for-assigned-group-admins"></a>已分配的组管理员的新权限  
Intune 的内置学校管理员角色现在具有对托管应用程序的创建、读取、更新和删除 (CRUD) 权限。 此更新意味着, 如果将分配为 Intune for Education 中的组管理员, 则现在可以创建、查看、更新和删除 iOS MDM Push Certificate、iOS MDM 服务器令牌和 iOS VPP 令牌以及[拥有的所有现有权限](https://docs.microsoft.com/intune-education/group-admin-delegate#group-admin-permissions)。 若要执行这些操作, 请转到**租户设置** > **iOS 设备管理**。  

### <a name="new-deployment-documentation"></a>新的部署文档  
在我们文档的 "[注册" 部分](https://docs.microsoft.com/intune-education/add-devices-windows)中, 你将找到一些新信息, 帮助你根据你的学校环境和设置需求比较设置 School Pc 和 Windows Autopilot。 使用此信息来确定何时为设备设置使用每个选项, 或同时使用这两种选项。 

## <a name="may-2019"></a>可能为2019   

### <a name="distinguish-between-online-and-offline-licensed-microsoft-store-for-education-apps"></a>区分 Microsoft Store 教育应用的联机和脱机许可   

你将能够查看教育应用 Microsoft Store 是否具有联机或脱机许可证。 Intune for Education 将在快速配置和应用的详细信息页上显示许可证类型, 使你能够更轻松地管理应用并将其部署到正确的组。 在用户登录设备并需要连接到 Microsoft Store 以使用时, 具有联机许可证的应用会开始安装。 在无需用户登录的情况下安装具有脱机许可证的应用, 并且无需连接到 Microsoft Store 即可使用。  

### <a name="new-ios-settings"></a>新 iOS 设置  

添加了新设置, 使你能够更好地控制 iOS 课堂应用。  

### <a name="apply-an-ios-device-naming-template"></a>应用 iOS 设备命名模板  

我们添加了新的命名设置, 以帮助你对 iOS 设备进行分组和标识。 在 iOS 注册和 MDM 服务器令牌安装期间, Intune for Education 会自动将每个设备的名称命名为唯一的设备序列号。 然后, 可以将自定义名称 (如 Contoso 或 Math1) 添加到前缀。 如果自定义名称, 则设备序列号会附加到其末尾。 例如：Contoso012a345b67c8. 配置或更新 MDM 服务器令牌的命名模板时, 与该令牌关联的所有设备都将重命名–现有设备和在应用命名模板之后注册的设备。 

## <a name="april-2019"></a>2019年4月  

### <a name="updated-ios-settings-names-and-added-more-tooltips"></a>更新了 iOS 设置名称并添加了更多工具提示  
在 Intune for Education 中修改了许多 iOS 设置名称、工具提示和类别, 使设置更易于查找和理解。 有关这些设置的详细列表, 请参阅[Intune for Education 中的 iOS 设备设置](all-edu-settings-ios.md)。  

### <a name="refined-list-of-ios-settings-in-express-configuration"></a>快速配置中 iOS 设置的精选列表   
我们调整了[快速配置中 iOS 设置的列表](edu-express-config-settings-ios.md), 以便你可以更快地设置设备和组。 你会看到, 一些设置已移出快速配置, 并在中移动了新设置。 你仍可以在 "**设置** > **iOS 设备设置**"**组** > 中配置已删除的设置。 有关 Intune for Education 中的设备设置的完整列表, 请参阅[iOS 设备设置](all-edu-settings-ios.md)和[Windows 10 设备设置](all-edu-settings-windows.md)。  

###  <a name="new-settings-for-windows-10-devices"></a>适用于 Windows 10 设备的新设置  
有几个新的 Windows 10 设备设置。 下面是一些你现在可以在 Intune for Education 中配置的设置:
* Windows 更新通知:此设置允许你选择用户是否看到有关 Windows 更新的通知。  
* 手动 Windows 更新:此设置允许你选择用户是否有权访问 Windows 更新扫描、下载和安装功能。  


## <a name="february-2019"></a>2019年2月  

### <a name="set-custom-wallpaper-and-lock-screen-images-for-your-ios-devices"></a>为 iOS 设备设置自定义墙纸和锁定屏幕图像  
你现在可以使用 Intune for Education 在学校设备上设置自定义墙纸和锁定屏幕图像。 若要上传映像, 请参阅对**iOS 设备设置** > **墙纸和锁定屏幕图像**进行**分组** > 。  

   ![IOS 设备设置、自定义墙纸和锁定屏幕图像的屏幕截图。](./media/ios-1901-custom-image-settings.png)  


## <a name="january-2019"></a>2019年1月  

### <a name="set-up-ios-devices-with-shared-ipad-features"></a>设置具有共享 iPad 功能的 iOS 设备
在 Intune for Education 为 iOS 设备注册配置设置时, 你现在可以选择将 iOS 设备配置为启用共享 iPad 功能注册。  共享 iPad 是一项 iOS 功能, 要求学生和教师使用托管 Apple ID 登录到学校设备。 他们可以登录和注销 school 中任何已启用的设备, 以访问已保存和正在进行的工作、应用程序和任务。 有关 Intune for Education 中共享 iPad 的详细信息, 请参阅[共享 ipad 配置](setup-ios-device-management.md#shared-ipad-configuration)。  

### <a name="new-settings-for-windows-10-devices"></a>适用于 Windows 10 设备的新设置  
我们添加了新的设置, 使你能够更好地控制安全性、Windows 更新、设备登录和浏览器体验等区域。 下面只是你将看到的几个新设置:  

* **配置首选 Azure Active Directory 租户域**:此设置允许学生登录到无租户域名的设备。 学生只能用其别名快速轻松地登录。  

* **配置新选项卡页**:此设置允许你选择学生在 Microsoft Edge 中添加选项卡时打开的页面。 新选项卡可以打开一个空白页或自定义的页, 例如您的学校的主页。  

* **切换到 S 模式**:此设置使管理员能够在 S 模式下从 Windows 10 切换设备, 或阻止学生将他们自己的设备从 S 模式切换。    

### <a name="updated-windows-settings-names-and-added-useful-tooltips"></a>更新了 Windows 设置名称并添加了有用的工具提示  
在 Intune for Education 中修改了许多设置名称和工具提示, 使其更易于查找和理解。 有关每个设置的更多详细信息, 请参阅[Intune for Education 中的 Windows 10 设备设置](all-edu-settings-windows.md)。  

### <a name="rename-windows-devices"></a>重命名 Windows 设备  
从 Intune for Education 门户远程重命名任何 Windows 10 (版本1803或更高版本) 设备。 若要重命名, 请跳到 "**设备**", 然后选择一个设备 >**重命名设备**。 你还可以从 "**设备详细信息**" 页重命名设备。  

## <a name="november-2018"></a>2018年11月  

### <a name="remote-autopilot-reset"></a>远程 Autopilot 重置 
你现在可以使用 Intune for Education 门户远程调用 Autopilot Reset。 Autopilot Reset 会删除所有用户数据, 包括用户安装的应用和个人设置并使设备在 Intune 中注册, 使设备与所有最新的应用、策略和设置保持同步。 利用此功能, 你可以快速擦除和重新配置学生的 Pc 批量, 为新的一年做好准备。 [在此处](autopilot-reset.md)了解有关 Autopilot 重置的详细信息。

### <a name="new-features-for-ios-management"></a>IOS 管理的新增功能
- Intune for Education 现在显示你的 Apple School Manager VPP 令牌的位置信息, 因此你可以轻松地从 Intune for Education 和 Apple 学校管理器中识别你的 VPP 令牌。 
- 可以在 Intune for Education 中提供 VPP 令牌别名, 以便于进行标记和组织。 
- 设置 MDM 服务器令牌后, 对 iOS 设备进行注册的速度将更快。 Intune for Education 自动配置注册设置, 因此与 MDM 服务器令牌关联的设备具有更少的设置助理屏幕来点击。 
 
### <a name="delete-device"></a>删除设备
你现在可以在 Intune for Education 门户中删除设备。 删除设备:
- 在 Intune 中取消注册设备。
- 从 Azure Active Directory 删除设备记录, 因此设备不再属于您的环境。
 
### <a name="immersive-reader-for-all-tenants"></a>适用于所有租户的沉浸式读者 
当你注册 Intune for Education 时, 适用于教育清单的 Windows 应用商店将获取沉浸式读者无限制的许可证。 沉浸式读者是一个学习工具, 它为所有年龄和能力的学习者创建了一个具有辅助功能和理解的阅读体验。 [在此处](https://www.onenote.com/learningtools)详细了解沉浸式读者。
 
### <a name="effective-policy-page"></a>有效策略页
"有效策略" 页显示基于组成员身份应用于用户/设备组合的所有应用和设置。 在此页中, 可以看到可能存在冲突的设置, 并解决问题。 可以通过两种方式访问 "有效策略" 页:
- 单击用户 >**中转到 "用户详细信息**" > 选择用户最近签入的设备。
- 单击设备 > "**中转到设备详细信息**" > 选择最近在该设备上签入的用户。



## <a name="july-2018"></a>2018 年 7 月 

### <a name="all-new-support-for-ios-classroom-devices"></a>所有新的 iOS 课堂设备支持  

Intune for Education 现在支持课堂上的 iOS 设备管理。 我们向 Intune for Education 添加了新功能和页面, 使每个人都可以轻松地完成设置和管理过程。 在仪表板中, 你将拥有成功设置、配置和注册设备所需的一切。  

* 设置 iOS 设备管理:我们已添加了一个新页面, 其中包含[分步指南](setup-ios-device-management.md), 可帮助你快速将 Apple 帐户连接到 Intune for Education。 屏幕指示器使你可以清楚地看到必需和可选的步骤, 即你已成功完成的步骤和即将到期的步骤。
* 快速配置:就像我们的 Windows 10 体验, 但专为 iOS 设备定制一样,[适用于 ios 的 express 配置](express-configuration-intune-edu.md)有助于快速分配和更改应用和设置。 选择一组用户或设备, 并从 Microsoft 推荐的设置中进行选择。 这些[建议是预先](edu-express-config-settings-ios.md)选择的, 但你可以随时对其进行更改, 以匹配你的学校自己的策略。  
* 应用和设置:我们添加了单独的应用和设备设置视图, 帮助你专注于[iOS](all-edu-settings-ios.md)或[Windows 10](all-edu-settings-windows.md)设备管理。 添加[APPLE vpp 支持](add-vpp-apps-ios.md)后, 你可以将你的 VPP 购买的应用与 Intune for Education 同步, 并直接从仪表板分配它们。 
* 动态分组:现在, 你可以将特定的设备平台规则应用于[动态组](create-groups.md#dynamic-groups)。 创建规则以应用于 Windows 10*或*iOS 设备上的设备或学生。  

获取更多详细信息, 并了解如何在[Intune for Education](what-is-intune-for-education.md)文档中导航新的页面和工作流。   

## <a name="january-2018"></a>2018 年 1 月

### <a name="history-of-group-actions-taken-by-admins"></a>管理员执行的组操作的历史记录

你现在可以查看管理员用于更改已批准组的组管理员、应用和设置的所有操作的历史记录。 可以在 "**组** > **历史记录**" 中找到此历史记录的日志。

### <a name="windows-defender-report"></a>Windows Defender 报表

我们添加了一个新报表。 在 "报表" 页上, 您可以从报表列表中选择 " **Windows Defender 报表**"。 这使你可以查看所有设备的 Windows Defender 设备运行状况状态。 可以在[什么是报表？](what-are-reports.md) doc 中查看其外观。

### <a name="use-role-based-access-control-to-enable-group-admins"></a>使用基于角色的访问控制来启用组管理员

你现在可以选择要管理其他组的设置的人员组。 例如, 你可能有一个名为 "*高中管理员*" 的组, 其中的成员是你所在地区的高中的管理员团队。 高中*管理员*组可以被授予管理高中学生组设置的权限。 有关详细信息, 请参阅[什么是组？ doc](what-are-groups.md)。

### <a name="user-and-device-search"></a>用户和设备搜索

我们已向边栏中添加了两个新选项:**用户**和**设备**。 您可以使用它们搜索各个用户或设备, 并快速打开这些项目的**详细信息**。 你可以将这些搜索添加到由边栏**查看所有** > **星形按钮 （收藏夹）** 以将它们添加到收藏夹列表中。

### <a name="remote-actions"></a>远程操作

你现在可以对用户和设备执行远程操作。 选择要对其执行操作的设备, 然后从详细信息页中选择以下操作之一:

#### <a name="devices"></a>设备

- “重新启动”
- 重置为出厂设置
- 同步
- 从管理中删除

#### <a name="users"></a>Users

- 重置密码

了解有关[远程操作](edu-device-remote-actions.md)的详细信息。

### <a name="wi-fi-profiles"></a>Wi-Fi 配置文件

我们为**wi-fi 配置文件**的边栏添加了一个新选项。 这允许你定义可分配给不同设备、用户和组的 Wi-fi 设置。

## <a name="october-2017"></a>2017 年 10 月

### <a name="dynamic-groups"></a>动态组

定义规则, 我们将创建基于它们自动填充的组。

### <a name="new-app-status"></a>新应用程序状态

添加应用时, 你现在会看到 "每个设备" 和 "每用户" 的应用安装状态。

### <a name="updated-details-pages"></a>更新的详细信息页

选择某个组中的用户或设备。 此时, 窗格将从屏幕的底部向上滑动, 使你可以获取有关该对象的详细信息, 以及已分配给该对象的应用和设置的状态。

## <a name="may-2017-initial-release"></a>5月 2017 (初始版本)

### <a name="intune-for-education-is-now-available"></a>Intune for Education 现已可用!

已启动 Intune for Education 门户。 Intune for Education 是一种简化的体验, 适用于学校和教育组织管理 Windows 10 设备。 详细了解这些文档中的 Intune for Education。

## <a name="next-steps"></a>后续步骤

- [了解有关 Intune for Education 的详细信息](what-is-intune-for-education.md)
- [了解有关 Intune 的完整设备管理体验的详细信息](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)
