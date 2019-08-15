---
title: 添加适用于 Windows 和 iOS 设备的 Wi-fi 配置文件
titleSuffix: Intune for Education
description: 了解如何在 Intune for Education 中创建你的设备的 Wi-fi 配置文件。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: b09d6128d8b64044165b42328f23bfddbdb3beca
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146533"
---
# <a name="add-a-wi-fi-profile"></a>添加 Wi-fi 配置文件

Wi-fi 配置文件描述了如何连接到您的学校的网络。 时将该配置文件分配给用户或设备组，组可以自动从他们的设备访问您的学校的网络。 配置文件无需为学生和教师手动连接到网络。

本文介绍如何配置 Windows 10 和 iOS 设备的配置文件。

## <a name="supported-device-platforms"></a>支持的设备平台
Windows 10 设备上和通过 Apple dep。 购买的 iOS 设备上支持的 Wi-fi 配置文件 

## <a name="configure-your-profile"></a>配置你的配置文件
Windows 10 和 iOS 的 Wi-fi 配置略有不同。 由于存在差异，必须创建您的学校的 Windows 10 设备的单个的 Wi-fi 配置文件，单个一个用于您的学校的 iOS 设备。
1. 登录到 Intune for Education >**的 Wi-fi 配置文件**。
2. 选择要配置的配置文件的设备平台。  
    a. 若要创建的 Windows 设备的配置文件，请单击**添加 Windows 10 的 Wi-fi 配置文件**。   
    b. 若要创建 iOS 设备的配置文件，请单击**添加 iOS Wi-fi 配置文件**。 
3. 输入您学校的无线网络的详细信息。 使用下表来帮助你填写这些设置。 设置设备平台因此请确保您查看适用于你的设备的表之间存在差异。
4. 完成后，单击“保存”。

### <a name="wi-fi-settings-for-windows-10-devices"></a>适用于 Windows 10 设备的 Wi-fi 设置
|设置 |描述  |
|---------|---------|
|配置文件名称    |  输入你的配置文件的唯一名称。| 
|网络名称 (SSID)    |  输入您的无线连接的显示名称。 在浏览从自己的设备的可用网络的列表时，用户将看到此名称。  |
|安全类型   |  选择要用于对 Wi-fi 网络进行身份验证的安全协议。 Intune for Education 支持 WPA2-Personal 和 Open。 如果您需要访问您的学校网络没有密码，请选择打开。 此类型的网络无安全保护，这意味着任何人都可以访问它。| 
|密码    |  输入你的 Wi-fi 网络的密码。 密码必须为 8 到 63 个字符。 | 
|确认密码| 重新输入你的 Wi-fi 网络的密码。|
|描述| 简要介绍一下该网络是用于或如何使用它。|  

### <a name="wi-fi-settings-for-ios-devices"></a>适用于 iOS 设备的 Wi-fi 设置
|设置 |描述  |
|---------|---------|
|配置文件名称    |  输入你的配置文件的唯一名称。       | 
|网络名称 (SSID)    |  输入您的无线连接的显示名称。 在浏览从自己的设备的可用网络的列表时，用户将看到此名称。        |
|安全类型   |  选择要用于对 Wi-fi 网络进行身份验证的安全协议。 Intune for Education 支持 WPA2-Personal 和 Open。 如果您需要访问您的学校网络没有密码，请选择打开。 此类型的网络无安全保护，这意味着任何人都可以访问它。       |  
|密码    |  输入你的 Wi-fi 网络的密码。 密码必须为 8 到 63 个字符。 | 
|确认密码| 重新输入你的 Wi-fi 网络的密码。|
|自动连接   |  如果启用，将自动连接网络的范围内已分配的设备。 如果未启用，你的学生或教师必须手动在网络从列表中选择可用的网络。       | 
|使隐藏的网络   | 如果启用，你的网络不会显示到可用网络列表中的用户。 他们将需要手动键入网络名称 (SSID) 连接到它。       | 
|配置代理设置| 启用时，可以配置您的学校的网络代理设置。|
|代理设置   |  如果你想要手动配置代理设置，或者如果你想要启用的代理脚本来自动检测设置选择。     | 
|代理服务器地址   | 键入代理服务器的 IP 地址。 如果您选择要自动检测代理设置不适用。      |
|代理服务器端口| 键入代理所在的位置的虚拟端口号。    | 
|代理服务器 URL  | 键入你想要使用自动连接到代理服务器的服务器 URL。 如果你已选择手动配置代理设置不适用。       |   

## <a name="assign-profile-to-groups"></a>将配置文件分配到组
1. 转到侧栏，然后单击**组**。
2. 在组的页上，单击**设置**选项卡。
3. 单击以展开您的操作系统的设备设置的相应组。
4. 单击的 Wi-fi 配置文件，然后选择要分配到组中的配置文件。 取消选择要删除其分配到组的配置文件。
5. 单击“保存” 。  
