---
title: 组设置有哪些？
titleSuffix: Intune for Education
description: 了解如何通过管理设置 Intune 教育版策略。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.openlocfilehash: 998b207bdfc0f8d48cd7eddff3020d00673377a2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145966"
---
# <a name="what-are-group-settings"></a>组设置有哪些？

配置组设置以管理学生、 教师，以及设备在您的学校中的工作原理。

设置分配给用户，将按照无论他们使用哪些设备的用户。 同样，你将分配给设备的设置将遵循的设备，无论使用者。

设置应用于组中。 因为组将设置为层次结构，与上面另一个组任何[设置应用于组及其所有子组由继承](settings-inheritance.md)。 继承使得更轻松地将设置应用于用户、 应用和设备的大规模群体。  

有两种方法来管理 Intune for Education 中的组设置：  

* __快速配置__:配置最常使用的学校设置的选择。 [快速配置](Express-configuration-intune-edu.md)是可帮助你选择和分配组设置的演练样式设置快速。 设置为 Microsoft 建议的值进行了预配置，但可以更改以适应您的学校的策略。 

* __组__：配置设备或用户的任何组的所有设置。 在中**组**选项卡上，将看到在门户中的可用设置的完整列表。 请参阅是可用于设置[Windows](all-edu-settings-windows.md)和有关[iOS](all-edu-settings-ios.md)组。  

## <a name="configure-express-configuration-settings"></a>配置快速配置设置  

可以是快速配置时使用：
* 您只需在门户中开始。
* 你一直在使用它一段时间，并想要进行快速更改。   

快速配置步骤的详细信息，请参阅[快速配置 Intune for Education 中的](Express-configuration-intune-edu.md)。

  ![快速配置设置解决](./media/express-config-006-choose-settings.png)  

## <a name="configure-settings-in-groups"></a>在组中配置设置

以下步骤介绍如何将从设置分配**组**Intune for Education 中的页。 从此页中，您将看到设备限制和功能的完整列表。  
1. 从 Intune for Education 仪表板，单击**组**。
2. 选择你想要配置的组。
3. 单击**设置**若要查看可用的设置的完整列表。
4. 展开每个类别可修改各种设置的所选组。
5. 完成后，单击“保存”。 在组中的所有设备上自动更新设置。  

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>我曾经可以使用不能同时使用的设置？

很可能不兼容的设置应用于同一个组。 这些不一致会导致错误，用户或设备正在设置时使用不同的设置在多个位置。 当用户或设备成员属于多个组时，会发生冲突。

例如，Esperanza 是的成员*第六级*组，也称为组的成员*地球科学*。 如果配置主页设置，并将分配给*第 6 个等级*，并配置不同的主页设置并将其分配给*地球科学*，Esperanza 现在具有两个冲突的主页设置分配对她。 不一致的设置赋值将导致错误。 若要解决此问题，你想要查看组[设置错误报表](what-are-reports.md)。  

## <a name="next-steps"></a>后续步骤
[创建用户和设备组](what-are-groups.md)Intune for Education 中，以便可以开始配置其设置。  

[了解有关如何保护应用和数据与 Intune 中的完整管理体验的详细信息](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
