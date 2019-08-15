---
title: 编辑 Intune for Education 中的组
titleSuffix: Intune for Education
description: 了解如何编辑现有用户和 Intune for Education 中的设备组。
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
ms.openlocfilehash: 5b613975d82da276c9735a713f9bd80d3e3d7a8c
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147002"
---
# <a name="edit-existing-groups"></a>编辑现有组

本文介绍如何从 Intune for Education 门户更改以下的组属性 >**组**页：

* 组名
* 组成员资格
* 列表位置
* 组规则 

## <a name="edit-group-name"></a>编辑组名称   
更改现有组的名称。
1. 单击你想要在中编辑的组你**组列表**。
2. 单击**重命名**。
3. 输入中的新名称**组名称**。
4. 单击 **“确定”**。

## <a name="manually-assign-members-to-groups"></a>手动将成员分配到组 
按照以下过程添加或删除用户和设备到现有的已分配组。

如果添加或删除组的成员，该成员是否为设备或用户，可能会遇到访问权限或权限中的更改。

以下说明详细介绍如何编辑*用户*成员身份。 此外可以执行这些步骤来编辑设备组的成员身份。

1. 转到**组**并选择你想要分配到用户的组。 
2. 单击**编辑用户成员资格**。
3. 若要将用户分配：  
    a. 选择一个或多个成员**所有其他用户**。  
    b. 单击**将用户添加**。  
4. 若要取消分配用户：    
    a. 选择一个或多个成员**组中的用户**。  
    b. 单击**删除用户**。
5. 单击 **“确定”**。

![编辑组中的设备](./media/groups-008-edit-group-membership.png)


## <a name="edit-dynamic-group-rules"></a>编辑动态组规则  
调整动态组规则，以适应新的设备、 位置或学校年。

编辑现有规则可能会删除设备或用户以前曾组的成员。 编辑可能导致这些体验的权限或访问中的更改。 

1. 转到**组**并选择你想要编辑的组。
2. 单击**编辑组规则**。
3. 对规则进行更改。 
4. 单击“保存更改”。  

## <a name="move-a-group"></a>移动组  

将现有的组列表中组向上或向下移动。 如果您将设置分发以不同的方式在组列表中，整个移动组更高版本或更低列表上更改设置其作用域。

通常情况下，组，如在父级别、 更广泛其设置的更高版本的位置。

  ![将移动以红色圈定的分组按钮](./media/groups-010-move-groups.png)

1. 从**组**列表中，选择你想要移动的组。
3. 单击**移动组**。
4. 选择或搜索你想要移动的组的位置。 
5.  单击 **“确定”**。  
