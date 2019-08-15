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
# <a name="enroll-ios-devices-in-intune-for-education"></a>注册 iOS 设备在 Intune 教育版

设备已准备好开机和管理中注册后：

* 设置 Intune for Education[学校信息](what-is-school-data-sync.md)— 如学生记录、 应用和设备的设置。
* 启用 Intune 以进行管理的 iOS 设备[设置 Apple 推送 MDM 证书和 Apple MDM Server 令牌](setup-ios-device-management.md#add-an-mdm-push-certificate)。
* [同步 Apple MDM Server 令牌](setup-ios-device-management.md#sync-managed-devices)使用 Intune 教育版和已准备注册设备的列表，请参阅。  

> [!NOTE]
> 请确保你的设备连接到 Internet，并且你的帐户具有足够 Intune for Education 设备许可证，若要完成安装。 详细了解中的许可[向用户分配许可证](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)。

## <a name="preconfigured-enrollment-profile"></a>预配置的注册配置文件  
Intune for Education 创建并分配学校优化注册配置文件的每个已同步的设备。  

注册配置文件配置为让如何本身设置和管理中注册的设备。 Intune 配置的设置，以帮助加快你的注册。  当开启设备时，将注册配置文件会立即开始设置你的设备。

## <a name="preconfigured-settings"></a>预先配置的设置  
初次设置设备，设备注册配置如下：

* 无用户关联
* 启用受监督的模式
* 阻止同步或与其他设备配对
* 锁定的注册，含义用户不能更改其设备上的管理设置  

Intune for Education 适用于通过 MDM server 令牌注册的设备命名方案。 默认情况下，设备是名为其设备序列号。 设置你的 MDM server 令牌时，还可以添加自定义设备名称。  

以下设置助理设置隐藏在注册过程：
* 密码设置
* 位置服务
* 设备还原
* iCloud 和 Apple ID
* Touch ID 设置
* Apple Pay 安装程序
* 显示缩放选项
* 使用 Siri 安装程序
* 诊断数据选项  


以下设置助理设置是在注册过程中所示：
* 条款和条件

### <a name="what-is-setup-assistant"></a>设置助理是什么？
第一次打开设备，Intune 教育版将启动 iOS 开箱体验，称为*设置助理*。 设置助理将指导你完成一系列屏幕，并准备你的学校使用的设备。  

## <a name="enroll-a-device"></a>注册设备

完成以下步骤引导完成设备注册。

1. 打开 iOS 设备。 
2. 选择“语言”后，请将设备连接 Wi-Fi。
3. 上**设置 iOS 设备**屏幕上，选择你**国家/地区**。
4. 若要自动或手动连接到 Wi-fi 的屏幕上按照的说明。 连接后，**配置**屏幕出现时，使用注册详细信息。  
5. 同意**条款和条件**。 然后决定您是否想要向 Apple 发送诊断信息。  

## <a name="next-steps"></a>后续步骤
现在，设备学校用于设置并准备就绪后，了解如何更新、 监视和解决这些问题。   
* 添加更多[免费](add-apps-ios.md)并[VPP](add-vpp-apps-ios.md)学校全年的 iOS 应用
* 将分配[组管理员](group-admin-delegate.md)可帮助您管理您的学校内或跨地区的教室设置
* 了解如何[设置继承](settings-inheritance.md)影响新组
* 审阅[报表](what-are-reports.md)地找出并对错误进行故障排除 
* 续订[iOS 证书和令牌](renew-ios-certificate-token.md)每年
