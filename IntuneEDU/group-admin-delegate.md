---
title: 委派的管理员权限组
titleSuffix: Intune for Education
description: 了解如何管理 Intune for Education 中的组的角色。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/20/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 9319be2e-cb7e-43c1-98fe-64281c8c09fd
searchScope:
- IntuneEDU
ms.openlocfilehash: 6538520b0364b6ecf4b7ec45d57a465d49907778
ms.sourcegitcommit: c766ef357fb0257951f4e35f6ec6f53d63de811e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/20/2019
ms.locfileid: "67285168"
---
# <a name="delegate-admin-permissions-to-groups"></a>委派的管理员权限组
您和您的 IT 员工在您的学校整个中管理多个组的学生、 教师和管理员。  

与 IT 人员不同管理员组只能管理向其分配的组。 当您向合格人员的组的管理员权限时，有助于降低未经授权或意外的更改的风险。  

## <a name="group-admin-permissions"></a>组管理员权限 

组管理员分配 Intune for Education 中，并且有权管理学校设备和应用。 组管理员可以：  

- 查看有关设备、 用户和应用程序的信息。
- 分配、 创建、 删除、 查看和更新设备和用户设置。
- 分配、 创建、 删除、 查看和更新应用。
- 查看报表。
- 包括重置为出厂设置、 重新启动、 未锁定的设备，锁定和强制同步的设备上执行远程操作。  
- 创建、 删除、 查看和更新 iOS MDM Push Certificate、 iOS MDM server 令牌和 iOS VPP 令牌。   

> [!TIP]
> 修改管理员权限是一项高级的任务。 如果你想要更改的权限或创建一组自定义的权限，则需要转到[完整管理体验中 Intune](https://docs.microsoft.com/intune/role-based-access-control)。 这些权限包含在 Intune 中内置的学校的管理员角色。 

## <a name="assign-an-admin-group"></a>将分配一个管理组

1. 从 Intune for Education 仪表板，单击**组**。
2. 选择的组。 此组将是你的管理员管理。
3. 单击**Admins**选项卡 >**添加管理员**。
4. 选择要为其提供管理应用和设置的管理员权限的组。
5. 单击**选择组**。

## <a name="remove-an-admin-group"></a>删除一个管理组
1. 从 Intune for Education 仪表板，单击**组**。
2. 选择的组。 此组将从管理中删除一个管理组的一个。
3. 单击**管理员**选项卡。
4. 从管理员的列表中选择一个或多个组。 然后单击**删除管理员**。  
