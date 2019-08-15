---
title: 适用于 Windows 10 快速配置默认设备设置
titleSuffix: Intune for Education
description: 列出并描述 Express 配置中的 Windows 10 设置。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 03/14/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: 4aae2a3ad7d411a0212b683430d7416c7318b1a1
ms.sourcegitcommit: 106131761071c33343f6b4e8006f36ae97ee28c7
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/11/2019
ms.locfileid: "66835648"
---
# <a name="default-windows-10-configurations-in-express-configuration"></a>默认 Windows 10 配置中快速配置
快速配置显示最常见的 Windows 设置，以帮助你快速设置你的 Windows 设备。 本文列出了每个设置，并介绍它们执行的操作。

进行更改以适合您的学校的规则和策略，或直接单击设置页以应用预设的建议。

有关设置和说明的完整列表，请参阅[Intune for Education 中的所有 Windows 10 设置](all-edu-settings-windows.md)。 

## <a name="accounts-and-sign-in"></a>帐户和登录 

|设置|其作用|  
|---|---|
|阻止添加和使用个人 Microsoft 帐户登录 |块学生和教师来自添加和登录到设备上的个人 Microsoft 帐户。 个人 Microsoft 帐户，请参阅使用 Microsoft 的域名，但不在您的学校的 Azure Active Directory 租户中的帐户。|  
|阻止添加和使用非 Microsoft 帐户登录|块学生和教师来自添加和登录到非 Microsoft 帐户，如 Google、 Yahoo 和 iCloud。 使用此设置来强制用户只能使用其 Microsoft 帐户电子邮件。|
|配置首选的 Azure Active Directory 租户域|配置您的学校域名，以便用户可以登录到 Windows 没有它。 例如，不使用用户名登录*alain\@contoso.com*，只需登录一名学生*alain*。 配置时，此设置会预填充你租户的域名，但您仍可以编辑它。|   

## <a name="apps"></a>应用   
|设置|其作用|  
|---|---|
|从 Microsoft Store for Education 安装应用程序块|阻止用户从未经授权的位置安装应用。|  
|需要 Microsoft Store for Education 的应用从专用应用商店安装|要求用户只安装你的组织已设置的教育版 Microsoft Store 应用。|  

## <a name="enrollment-controls"></a>注册控件  
|设置|其作用| 
|---|---|
|阻止手动取消注册|阻止用户手动取消注册设备管理。|
|阻止添加预配包|阻止用户添加新的预配包含设备设置的包。|
|阻止删除预配包|阻止用户删除包含设备设置的预配包。|  

## <a name="microsoft-edge-settings"></a>Microsoft Edge 设置  
|设置|其作用|
|---|---|
|配置主页|配置 Microsoft Edge 主页上给学生和教师的显示方式。 **打开自定义页**打开所选的 URL。 在浏览器将打开一个新选项卡添加每个 URL。 **打开上一次会话页**打开浏览器已关闭的最后一个时间处于活动状态的页。 如果未配置此设置，用户可以配置自己的主页。| 
|阻止 InPrivate 浏览|阻止用户从使用 InPrivate 浏览阻止 Microsoft Edge 保存数据，如浏览历史记录和 cookie。|  
|阻止浏览器扩展|阻止用户安装浏览器扩展。|
|阻止的弹出窗口|阻止打开新窗口的网站。|  
|阻止密码管理器|阻止用户使用密码管理器来保存密码。|
|阻止自动填充表单条目|保存在窗体字段中输入的数据块。|
|阻止开发人员工具|阻止用户打开 Microsoft Edge 开发人员工具。 这些工具使用户能够生成和调试的网页。|  

## <a name="user-experience"></a>用户体验 
|设置|其作用| 
|---|---|
|阻止使用相机|阻止使用设备相机。|
|阻止 OneDrive 文件同步|阻止设备同步到 OneDrive 的文件。|
|阻止可移动存储|阻止使用可移动存储，如 U 盘、 SD 卡和外部硬盘的容量。|
|阻止 Cortana|阻止 Cortana，数字助理内置于 Windows 10 可以回答的问题和执行任务。|
|阻止定位服务|阻止应用使用位置服务来访问设备的位置。|  
|块结束任务在任务管理器|阻止用户使用任务管理器强制执行程序、 进程或关闭的任务。|
|阻止更改日期和时间设置|阻止用户更改设备日期和时间设置。|
|阻止更改语言设置|阻止用户更改设备的语言。|
|阻止更改设备区域设置|阻止用户更改区域设置，例如国家/地区和语言。|
|设置自定义锁屏图像|将自定义背景图像添加到设备登录屏幕。 键入.jpg 或.png 图像的大小不超过 20 MB 的 web 链接。|
|设置自定义桌面图像|将自定义背景图像添加到设备的桌面。 键入.jpg 或.png 图像的大小不超过 20 MB 的 web 链接。|
|阻止访问设置应用|阻止用户对整个设置应用程序访问权限。|  

## <a name="reset-default-settings"></a>重置默认设置
若要将所有设置都还原为其默认值，请单击**重置为建议的默认设置**。  

