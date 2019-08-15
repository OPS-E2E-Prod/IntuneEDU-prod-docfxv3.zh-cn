---
title: 什么是设置继承？
titleSuffix: Intune for Education
description: 了解如何管理使用 Intune for Education 设备组的设置。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 09/26/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope:
- IntuneEDU
ms.openlocfilehash: 5a981fb8916dc0318cc1599002ebe9001f1ef41b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146896"
---
# <a name="what-is-settings-inheritance"></a>什么是设置继承？

设置应用于组中。 因为组将设置为层次结构，与上面另一个组及其子组由继承应用于组的所有设置。 您对其上方的组发生更改时自动执行子组。 此操作称为_继承_。 设置继承 ia 想要将设置应用于大量用户和设备时，很有帮助。  


  ![组和子组的树。](./media/groups-002-inheritance.png)  


## <a name="configure-subgroups-individually"></a>单独配置子组  

若要覆盖最近继承的设置，直接转到子组。 它单独配置通过删除或添加设置。 然后保存所做的更改。

## <a name="settings-in-conflict"></a>发生冲突的设置  

如果将冲突的设置应用到相同的组，Intune 将单独分析每个。 Intune 将始终选择的设置确定，符合学校策略。

在其他情况下，当 Intune 不能解决该冲突，则应该查看[设置冲突](what-are-reports.md)报表。

### <a name="example-of-inheritance-conflict"></a>继承冲突示例  

作为示例，请考虑子组，*第 12 年级 AP 计算机科学*。 子组所属的父组中，*第 12 年级*。 分配严格的安全扫描的所有文件的要求和应用程序被下载中的设备*第 12 年级*组。

但是，对于即将发布的分配，知道该*第 12 年级 AP 计算机科学*必须下载不需要扫描的 JavaScript 文件。 如果不替代更严格的设置继承*第 12 个等级*设置将应用于中的用户*第 12 个等级 AP 计算机科学*。

## <a name="settings-error-report"></a>设置错误报告

如果无法解析设置，则会在设置错误报告中。 有关报表的详细信息，请参阅[查看和下载报表](what-are-reports.md)。  

## <a name="next-steps"></a>后续步骤  
详细了解如何[在 Intune 中的完整组体验](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)。
