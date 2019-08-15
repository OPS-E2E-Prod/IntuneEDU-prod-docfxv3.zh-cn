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
# <a name="default-ios-settings-in-express-configuration"></a>快速配置中的默认 iOS 设置
快速配置是预配置的 iOS 设置建议, 可帮助你快速设置一组设备或用户。 Intune for Education 选择同时为 Microsoft 推荐的和最适用于 school 环境的设置。 更改以适合你的学校的规则和策略, 或单击 "设置" 页面以应用建议。 

有关设置和说明的完整列表, 请参阅[Intune for Education 中的所有 iOS 设置](all-edu-settings-ios.md)。 

> [!IMPORTANT]
> 如果在启动快速配置时禁用了 iOS 配置, 请检查以确保已设置 MDM Apple Push certificate 和 DEP 令牌。 如果有这两种方法, 请确保它们都不会过期。 有关设置 iOS 设备管理的详细信息, 请参阅[设置 ios 设备管理](setup-ios-device-management.md)


## <a name="app-store-itunes-store-and-book-store"></a>应用商店、iTunes 商店和书籍商店  
设置|其作用|  
|---|---|
|阻止应用商店|阻止学生访问学校设备上的应用商店。|
|阻止应用内购买|阻止在正在运行的应用中进行存储购买。|
|阻止应用商店和 iTunes 应用商店中的显式内容|阻止学生访问应用商店中分级为成人的内容。|
|阻止下载标记为 erotica 的 Apple 书籍内容|阻止学生下载归类为 erotica 的书籍。|  

## <a name="built-in-apps"></a>内置应用  
设置|其作用|  
|---|---|
|阻止照相机|阻止在设备上使用相机。|
|阻止 FaceTime|阻止在设备上使用 FaceTime 应用。|
|块 Game Center|阻止在设备上使用 Game Center 应用。|  
|块 Apple Music|阻止在设备上使用 Apple Music 应用的音乐流组件。|
|阻止消息应用|阻止在设备上使用 "邮件" 应用。|
|阻止 Apple 书籍|阻止学生浏览和购买书籍商店中的书籍。|  

## <a name="device-restrictions"></a>设备限制  
设置名|其作用|
|---|---|
|阻止更改设备名称|阻止学生更改设备的名称。|
|阻止更改墙纸|阻止学生更改设备锁定屏幕和主屏幕图像。|
|阻止更改通知设置|阻止学生更改设备通知设置。|
|阻止对内容和隐私限制的更改|阻止学生更改设备上的限制 (家长控制) 和屏幕时间设置。|
|清除所有内容和设置的阻止按钮|阻止学生擦除设备上的所有内容和设置。 "清除" 按钮变为不可用, 无法选择。|  

## <a name="icloud"></a>iCloud
|设置|其作用|
|---|---|
|阻止 iCloud 备份|阻止学生将设备备份到 iCloud。|
|阻止将文档同步到 iCloud|阻止文档同步到 iCloud 存储空间。|
|阻止 iCloud 照片库|阻止学生在云中存储照片和视频。 尚未从 iCloud 照片库完全下载的照片将从本地存储中删除。|  

## <a name="lock-screen-and-wallpaper"></a>锁定屏幕和墙纸
设置|其作用|
|---|---|
|锁定屏幕上的阻止通知|阻止学生在设备锁定时查看通知。|
|阻止从锁屏界面访问钱包|锁定设备时阻止学生访问钱包应用。|
|设置设备锁定屏幕图像|选择一个自定义映像, 作为设备的锁屏界面的墙纸。|
|设置设备主屏幕图像|选择一个自定义映像, 作为设备主屏幕的墙纸。|  

## <a name="passcode-touch-id-and-face-id"></a>密码、Touch ID 和人脸 ID  
设置|其作用|
|---|---|  
|需要密码|要求学生输入密码来解锁设备。|
|阻止更改密码|阻止学生更改、添加或删除设备密码。|
|擦除设备前的密码尝试失败次数|当某人超出允许的登录尝试次数时, 设备将从设备中清除所有内容和设置, 例如个人数据、iOS 软件、电子邮件帐户、系统和应用设置、下载的应用和媒体。 设备将还原到首次打开的方式。 若要配置此设置, 请输入允许的最大登录尝试次数。|
|阻止 Touch ID 和人脸 ID|阻止学生使用指纹或面部识别来解锁设备。|

## <a name="siri-and-search"></a>Siri 和搜索 
设置|其作用|
|---|---|   
|阻止 Siri|阻止学生使用 Siri, 即 iOS 语音助手。|  

## <a name="reset-default-settings"></a>重置默认设置
若要将所有设置还原为其默认值, 请单击 "**重置为建议的默认**值"。 

## <a name="next-steps"></a>后续步骤  
在 Intune for Education 中了解有关组、设置和监视冲突的信息。 
* 了解[分配的和动态](create-groups.md)组之间的差异
* 分配[组管理员](group-admin-delegate.md)以帮助你管理学校内或跨区域的教室设置
* 了解[设置继承](settings-inheritance.md)如何影响组分配
* 查看[报表](what-are-reports.md)以确定并解决设置冲突
