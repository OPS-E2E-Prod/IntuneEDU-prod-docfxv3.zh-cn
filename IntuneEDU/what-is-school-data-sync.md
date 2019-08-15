---
title: 学校数据同步使用的学校记录导入
titleSuffix: Intune for Education
description: 使用学校数据同步到 Azure AD 导入学校组和人员。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope:
- IntuneEDU
ms.openlocfilehash: ec80e1b8f8d2851814227420b5026dd3c488277c
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146530"
---
# <a name="microsoft-school-data-sync-and-intune-for-education"></a>Microsoft 学校数据同步和 Intune for Education

Microsoft 学校数据同步 (SDS) 是一项免费服务中将学校记录导入从你现有的学生信息系统 (SIS) 的 Office 365 教育版。 它创建在线教室和组 Microsoft Teams、 Intune 教育版和第三方应用程序。  

转到学校数据同步文档[了解如何部署 SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91)。 

## <a name="create-groups-from-school-roster"></a>从学校名册创建组
SDS 将 SIS 从创建信息的副本，并将其存储在 Azure Active Directory (Azure AD) 中。 SDS Intune for Education 可以向其应用设置和应用程序中创建两个组：

* 所有学生
* 所有教师

在 Intune for Education 中创建组的详细信息，请参阅[创建组](create-groups.md)。  

## <a name="set-up-dynamic-group-properties"></a>设置动态组属性
当从 SIS 将学生信息导入到 Intune for Education 与学校数据同步，包括以下属性：
*  等级 
*  毕业年份  

这些属性是创建所需[动态组](create-groups.md#dynamic-groups)学生 Intune for Education 门户中的规则。  属性从 SDS 应用配置和中找到__学生选项__ > __选择属性学生__。

## <a name="what-is-azure-ad"></a>什么是 Azure AD？
Azure AD 是与 Intune 集成的 Microsoft 管理系统，可帮助组织学生和设备。 它可以创建组超出您的学生和教师，如*第四个时间段生物学*或*Contoso 学区教师*。 组所需分配和分发用户或特定于设备的应用、 设置和限制。

## <a name="next-steps"></a>后续步骤   
与 Intune for Education 同步你的学生和教师信息后，开始使用快速配置[Windows](edu-express-config-settings-windows.md)或[iOS](edu-express-config-settings-ios.md)设备。  

想要了解有关 Microsoft 学校数据同步的详细信息？ 请访问[Microsoft 学校数据同步页](https://sds.microsoft.com)有关产品信息。 
