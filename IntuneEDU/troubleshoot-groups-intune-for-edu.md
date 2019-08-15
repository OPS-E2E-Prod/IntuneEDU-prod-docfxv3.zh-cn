---
title: 在 Intune for Education 中创建组
titleSuffix: Intune for Education
description: 了解如何管理使用 Intune for Education 的设备组。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 10/08/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: dc0daff52ab3d0348b7cb0fb9256c6cf480def6b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147468"
---
# <a name="troubleshooting-group-actions"></a>故障排除组操作

本文回答了有关创建和编辑 Intune for Education 中的组的常见问题。

## <a name="why-cant-i-edit-the-default-groups"></a>为什么无法编辑默认组？

在创建你的帐户时，Intune for Education 创建一组默认情况下，租户级别的组。 这些组&ndash;**的所有用户**并**所有设备**&ndash;不能更改。 Intune 从学校数据同步中导入你的学校和教师记录后，创建更多的组，称为**所有教师**并**的所有学生**。 这些组也无法更改。

在极少数情况下，您可能会得到下面两个组的相同子组。 如果出现此问题，请移动其中一个子组上方的顶级组。

## <a name="why-cant-i-edit-dynamic-groups"></a>为什么不能编辑动态组？

Intune for Education，你选择从 Intune 的完整的管理门户中的动态属性的子集。 如果你想要编辑的属性不是 Intune for Education 门户中可见的则你必须在 Azure 门户或 Azure Active Directory 中而在 Intune 中进行编辑。

## <a name="why-cant-i-edit-a-specific-group"></a>为什么不能编辑特定的组？  

Intune for Education 旨在作为管理你的学校中的设备的简单办法。 它使用[Azure 门户中的 Intune](https://docs.microsoft.com/intune/what-is-intune)&ndash;企业产品&ndash;来管理应用程序和组。 你的组织中的某些管理员有权使用 Azure 门户中的 Intune 和 Intune for Education 创建特殊的组。 如果您不能编辑组，则可能在 Intune 中创建在 Azure 门户中，并且你没有权限来修改组。  
