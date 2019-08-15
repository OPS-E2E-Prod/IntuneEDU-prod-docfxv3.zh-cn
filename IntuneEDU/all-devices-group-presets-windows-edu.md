---
title: Windows 10 所有设备组预设
titleSuffix: Intune for Education
description: 请参阅在注册时预设的 Windows 10 设备设置的列表
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/12/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: a75f06e7ad7538ca8d0412e656bc4452c7bc48a0
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146642"
---
# <a name="all-devices-group-presets-for-windows-10"></a>适用于 Windows 10 所有设备组预设
注册帐户后，Intune for Education 预设中的所有设备组的设置的一些。 这些设置帮助你开始在管理 Windows 10 设备在课堂中。 若要调整设置，请转到 Intune for Education 门户 >**组** > **所有设备** > **Windows 设备设置**。  

列表和所有 Windows 10 设备设置的说明，请参阅[Windows 10 设备设置](all-edu-settings-windows.md)。  

|Category|设置|预设的值|
|---|---|---|
|应用|需要 Microsoft Store for Education 的应用从专用应用商店安装|要求|
|应用|受信任的应用|阻止|  
|应用|不受信任的应用程序|阻止| 
|注册控件|阻止手动取消注册|阻止|
|注册控件|块 Autopilot 重置|启用|
|注册控件|阻止添加预配包|阻止|
|注册控件|阻止删除预配包|阻止|
|Microsoft Edge|阻止不受信任的浏览器扩展 |阻止|
|Microsoft Edge|阻止重写安全警告 |阻止|
|Microsoft Edge|使用 Cookie|用户定义
|网络和连接|阻止蓝牙 Swift 对通知 |阻止
|安全性|阻止用户访问 Windows Defender 设置|启用
|安全性|启用实时监视|启用
|安全性|启用行为监视|启用
|安全性|提示用户提交给 Microsoft 的可疑文件|永远不会发送数据
|安全性|若要执行的系统扫描的类型|快速扫描|
|安全性|每日快速扫描时间|2 凌晨点|
|安全性|扫描所有下载的文件|启用|
|安全性|扫描 Microsoft web 浏览器中运行的脚本|启用|
|安全性|完全扫描期间扫描可移动驱动器|启用|
|安全性|扫描通过网络打开的文件|启用|
|安全性|完全扫描期间扫描远程文件夹|启用|
|安全性|扫描存档文件|启用|
|安全性|扫描传入的电子邮件|启用|
|安全性|打开文件或程序时，恶意软件扫描|监视所有文件|
|安全性|删除已隔离恶意软件之前的天数|0|
|安全性|设置反恶意软件更新频率|8 小时|
|安全性|启用云提供的保护|启用|
|安全性|启用网络检查服务|启用|
|更新和升级 |分支就绪级别|半年频道|
|更新和升级 |配置如何以及何时安装更新|自动安装并重启而无需最终用户控件| 
|更新和升级 |延迟功能更新后变得可用的天数 |0|
|更新和升级 |延迟质量更新变得可用后的天数  |0|
|更新和升级 |传递优化模式|使用对等互连 NAT 的 HTTP |
|更新和升级 |切出 S 模式|将保留在 S 模式|
|用户体验|阻止 Cortana|阻止|
|用户体验|发送诊断数据|基本|
|用户体验|阻止 Windows 聚焦|阻止|  


## <a name="next-steps"></a>后续步骤
Intune for Education 中可用的 Windows 10 设置的完整列表，请参阅[的所有 Windows 10 设置](all-edu-settings-windows.md)。  

自定义设置是在 Azure 门户在 Intune 中可用。 有关详细信息，请参阅[对于 Windows 10 设备使用自定义设置](https://docs.microsoft.com/intune/custom-settings-windows-10)。  