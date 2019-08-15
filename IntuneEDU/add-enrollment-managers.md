---
title: 添加注册管理器
titleSuffix: Intune for Education
description: 了解如何在 Intune for Education 中添加注册管理器。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 08/30/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope:
- IntuneEDU
ms.openlocfilehash: 26b9a9c6eaabe85dbe77acd9a52f7b86b8a99d4d
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146969"
---
# <a name="add-enrollment-managers"></a>添加注册管理器  

向你的现有用户的设备的注册权限。 使用设备注册管理器帐户的用户可以注册最多 1000 个中 Intune 教育版的 Windows 10 设备。

 注册管理员帐户是有成千上万个共享要注册的 Windows 10 设备的大型组织中有帮助。  

## <a name="requirements"></a>要求  

用户必须在 Azure 门户中存在才能添加为设备注册管理器。

设备注册权限不能与以下其他注册方法结合使用：Apple Configurator 与设置助理、 Apple Configurator 与直接注册、 Apple School Manager (ASM) 或设备注册计划 (DEP)。  

## <a name="assign-enrollment-permissions"></a>分配注册权限  

1. 从 Intune for Education 仪表板，单击**注册管理器**。
2. **单击分配注册权限**。
3. 选择你想要向其分配权限的用户。 如果您知道用户的名称，您可以在搜索字段搜索它们。
4. 单击“保存” 。

## <a name="remove-enrollment-permissions"></a>删除注册权限  
1. 从**注册管理器**，请转到屏幕的左侧，并选择用户。 
2. 单击**删除注册权限**。
3. 单击**删除**来确认你的操作。 删除设备注册管理器不会影响已注册的设备。
  ![删除注册权限按钮处于选中状态时查看一个单独的注册管理器的页](./media/enroll-mgrs-003-remove-enrollment-permissions.png)
