---
title: 在 Intune for Education 中创建组
titleSuffix: Intune for Education
description: 了解如何管理使用 Intune for Education 的设备组。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: 1008314a0c9737736ce6e7768f704cd316c252fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146717"
---
# <a name="create-groups-in-intune"></a>在 Intune 中创建组

在 Intune 中的组功能允许您管理用户、 应用和设备管理要求基本相似。 使用组，可以减少单独管理和故障排除的设备所花费的时间。 

## <a name="default-groups"></a>默认组  
-现成可用，Intune for Education 附带使你能够管理的默认组：  
* “所有设备”
* 所有用户

如果您使用学校数据同步将学校记录导入，将创建两个额外的默认组。 它们使您能够管理：  
* 所有教师
* 所有学生

这些默认组表示最广泛类别的用户和设备在您的学校和不能更改或删除。

## <a name="custom-groups"></a>自定义组  

将特定的或基于方案的配置应用于自定义创建的组。 如果您的学校中必须使用 Windows 10 和 iOS 设备，创建组，如所有 Ipad 和所有 Windows 10 电脑。 这样一来，你将能够更轻松地识别组和分发的设置。 

此外可以将应用和设置分配给特定组的学生。 例如，第 8 个的等级课程可能需要不同的应用程序比第六级课程。 您可以创建两个，特定于级的组和分配应用和设置适用于学生的每个集。  
## <a name="group-types"></a>组类型  

有两种类型的可用于组织用户和设备在 Intune for Education 的组： 分配的组和动态组。

### <a name="assigned-groups"></a>已分配的组  

当你想要手动将用户或设备添加到组时使用已分配的组。  就像将档案系统放在一起： 将使用您自己的逻辑或分组方法的特定文件夹到文件特定的文章。 当您需要这些文章时，您就知道确切的文件夹，以转到。 

同样，您可以创建文件夹中的文件夹或*子组*，以便进一步组织到可管理的大小更大的组。

若要了解如何手动分配或删除成员，请参阅[编辑组](edit-groups-intune-for-edu.md)。


### <a name="dynamic-groups"></a>动态组  
动态组引用创建将学生或设备分配到组的规则。 规则的条件在初始组创建过程中指定并创建组后，可以编辑。

例如，可以创建一组特定于 2019年学校年结束时从 Contoso 高毕业的学员。 而是不是通过和手动分配每个学生，Intune for Education 将到基于学校和毕业日期组筛选学生。

如果在组中的一名学生传输超出 Contoso 高和到另一个学校，您学区，将无法从动态组中手动删除。 相反，您需要更新，以便 Intune 知道，他们知道不再满足成员资格的组条件的学生的学校名称。

由于动态组只能包含其规则定义，因此不能创建在其下的子组。

若要了解如何编辑组规则，请参阅[编辑组](edit-groups-intune-for-edu.md)。

> [!TIP]
> 使用动态规则来筛选通过相似的组或最近登记组的设备，如*DeviceType_School_Grade_0001*。 动态组是非常适用于管理大量设备或大型学区中的用户。 它们减少时间和手动遍历学校的清单或员工所需的成本。  


## <a name="plan-your-groups"></a>规划组
若要开始，计划的设置和应用程序所需的学区、 学生、 教师和设备。 设置分配给组，并且一些组需要的特定设置和应用程序。   

例如：  
* 对于所有的设备，阻止应用使用位置服务。 
* 有关 AP 计算机科学中，分配学生应用来编辑代码。
* 对于第 12 年级历史记录学生，来启用 web 浏览以便他们可以访问学术文章。
* 对于摄影学生来启用设备照相机。


## <a name="create-a-group"></a>创建组  
组只能创建一个时间。 安装过程中，你将选择要创建为任一用户或设备组。

1. 从 Intune for Education 仪表板，单击**组** > **创建组**。
2. 输入描述性的组名称。
3. 选择组类型。 有关更多有关分配和动态组的详细信息，请参阅[类型分组](## Group types)   
    a. 分配：手动添加和删除这些组中的用户和设备。 如果选择此选项，请转到步骤 5。
   b. 动态：实现规则自动添加和删除用户和设备。 如果选择此选项，请转到步骤 4。
4. 选择以管理设备或学生。
    a. 设备：如果选择此选项，则会显示命名规则。 创建一个规则，以将启动或包含您输入的文本的设备自动分配。 键入时，将在页面底部填充成员的预览。
    b. 学生：如果选择学生，将出现的位置和标识规则。 创建一个规则以自动分配转到你的租户中特定学校的学生。 然后选择此选项将学生组合在按等级或毕业年份。 输入所有字段后，将在页面底部填充成员的预览。
5. 在页面底部，单击**创建组**。

## <a name="create-a-subgroup"></a>创建子组  
设置组在 Intune 中为层次结构。 父组是在层次结构的顶部和[应用到此组的任何设置由其下的组继承](settings-inheritance.md)。 此概念称为*设置继承*。  设置继承，可以更轻松地将设置应用于一支庞大的用户和设备。 

只能在创建子组*下*为其分配组。 

 ![创建子组页面上的，具有子组创建两个位置，在组名称和侧栏的顶部 — 圈定的红色](./media/groups-007-create-subgroup.png)

1. 转到**组**，然后选择一个组。 此组将你的子组的父级。
2. 单击**创建子组**。
3. 输入**组名称**。 
4. 选择组类型。 有关组类型的更多详细信息，请参阅的步骤[创建一个组](#create-a-group)上面。
5. 单击**创建组**。  

## <a name="next-steps"></a>后续步骤 
[委派的权限](group-admin-delegate.md)以允许管理员组来管理父级别的组和子组。  

[了解完整](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)组在 Intune 中的管理体验。
