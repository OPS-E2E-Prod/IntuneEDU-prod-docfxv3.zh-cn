---
title: Intune for Education 中的远程设备操作
titleSuffix: Intune for Education
description: 了解如何使用远程操作排除故障并管理存有一定距离的设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/30/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: df7cabf2-1723-4817-b16c-800407a0c753
searchScope:
- IntuneEDU
ms.openlocfilehash: f19a24c78ad3a155b33ccc05bc266160fce7387e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146765"
---
# <a name="manage-devices-remotely"></a>远程管理设备  

如果你是在不同的位置不是设备或其用户，并且需要帮助他们进行故障排除，远程操作在中使用 Intune 教育版。  


## <a name="remote-actions-for-devices"></a>适用于设备的远程操作  

![示例屏幕截图： 显示 Intune 教育版的 7 的远程操作。](./media/1812_Intune_EDU_Manage_Remote.png)  

从仪表板中，转到**设备**。 选择你想要管理的设备。 在页面的底部，选择任何以下操作：

- **重新启动**:关闭设备提供支持，并重新启动它。
- **恢复出厂设置**：从 Intune 管理删除设备并删除设备上的所有数据和设置。 
- **同步设备**:确保该设备具有最新的设置、 应用分配和组成员身份。 如果您正在尝试进行设备进行故障排除，可帮助此操作。  
- **Autopilot 重置**:删除所有用户数据&ndash;包括用户已安装的应用和个人设置&ndash;并保持在 Intune 中注册 Windows 10 设备。 设备保持最新的应用、 策略和设置与最新。 当开始重置时，会显示通知。 设备重置的下次连接到 internet。  
- **重命名设备**:为设备提供新名称。 新名称更新在 Intune 中和本地设备上。 您必须重新启动 Windows 设备的新名称才会生效。  
- **删除设备**:取消注册设备从 Intune 教育版和从 Azure Active Directory 中删除设备。 已删除的设备不再可以访问您的学校资源。 

## <a name="remote-actions-for-users"></a>用户的远程操作  

从仪表板中，转到**用户**。 选择你想要管理的用户。 在页面底部，选择**重置密码**。 此操作将在用户设备上的旧、 丢失或忘记了密码重置。  
