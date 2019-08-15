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
# <a name="microsoft-school-data-sync-and-intune-for-education"></a><span data-ttu-id="ad66f-103">Microsoft 学校数据同步和 Intune for Education</span><span class="sxs-lookup"><span data-stu-id="ad66f-103">Microsoft School Data Sync and Intune for Education</span></span>

<span data-ttu-id="ad66f-104">Microsoft 学校数据同步 (SDS) 是一项免费服务中将学校记录导入从你现有的学生信息系统 (SIS) 的 Office 365 教育版。</span><span class="sxs-lookup"><span data-stu-id="ad66f-104">Microsoft School Data Sync (SDS) is a free service in Office 365 Education that imports school records from your existing Student Information System (SIS).</span></span> <span data-ttu-id="ad66f-105">它创建在线教室和组 Microsoft Teams、 Intune 教育版和第三方应用程序。</span><span class="sxs-lookup"><span data-stu-id="ad66f-105">It creates online classrooms and groups for Microsoft Teams, Intune for Education, and third-party applications.</span></span>  

<span data-ttu-id="ad66f-106">转到学校数据同步文档[了解如何部署 SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91)。</span><span class="sxs-lookup"><span data-stu-id="ad66f-106">Go to the School Data Sync documentation to [learn how to deploy SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91).</span></span> 

## <a name="create-groups-from-school-roster"></a><span data-ttu-id="ad66f-107">从学校名册创建组</span><span class="sxs-lookup"><span data-stu-id="ad66f-107">Create groups from school roster</span></span>
<span data-ttu-id="ad66f-108">SDS 将 SIS 从创建信息的副本，并将其存储在 Azure Active Directory (Azure AD) 中。</span><span class="sxs-lookup"><span data-stu-id="ad66f-108">SDS creates copies of the information from your SIS, and stores it in Azure Active Directory (Azure AD).</span></span> <span data-ttu-id="ad66f-109">SDS Intune for Education 可以向其应用设置和应用程序中创建两个组：</span><span class="sxs-lookup"><span data-stu-id="ad66f-109">SDS creates two groups in Intune for Education to which you can apply settings and apps:</span></span>

* <span data-ttu-id="ad66f-110">所有学生</span><span class="sxs-lookup"><span data-stu-id="ad66f-110">All Students</span></span>
* <span data-ttu-id="ad66f-111">所有教师</span><span class="sxs-lookup"><span data-stu-id="ad66f-111">All Teachers</span></span>

<span data-ttu-id="ad66f-112">在 Intune for Education 中创建组的详细信息，请参阅[创建组](create-groups.md)。</span><span class="sxs-lookup"><span data-stu-id="ad66f-112">For more information about creating groups in Intune for Education, see [Create groups](create-groups.md).</span></span>  

## <a name="set-up-dynamic-group-properties"></a><span data-ttu-id="ad66f-113">设置动态组属性</span><span class="sxs-lookup"><span data-stu-id="ad66f-113">Set up dynamic group properties</span></span>
<span data-ttu-id="ad66f-114">当从 SIS 将学生信息导入到 Intune for Education 与学校数据同步，包括以下属性：</span><span class="sxs-lookup"><span data-stu-id="ad66f-114">When importing student information from your SIS into Intune for Education with School Data Sync, include the following properties:</span></span>
*  <span data-ttu-id="ad66f-115">等级</span><span class="sxs-lookup"><span data-stu-id="ad66f-115">Grade</span></span> 
*  <span data-ttu-id="ad66f-116">毕业年份</span><span class="sxs-lookup"><span data-stu-id="ad66f-116">Graduation Year</span></span>  

<span data-ttu-id="ad66f-117">这些属性是创建所需[动态组](create-groups.md#dynamic-groups)学生 Intune for Education 门户中的规则。</span><span class="sxs-lookup"><span data-stu-id="ad66f-117">These properties are necessary to create [dynamic group](create-groups.md#dynamic-groups) rules for students in the Intune for Education portal.</span></span>  <span data-ttu-id="ad66f-118">属性从 SDS 应用配置和中找到__学生选项__ > __选择属性学生__。</span><span class="sxs-lookup"><span data-stu-id="ad66f-118">Properties are configured from the SDS app, and are found in  __Student options__ > __Select student properties__.</span></span>

## <a name="what-is-azure-ad"></a><span data-ttu-id="ad66f-119">什么是 Azure AD？</span><span class="sxs-lookup"><span data-stu-id="ad66f-119">What is Azure AD?</span></span>
<span data-ttu-id="ad66f-120">Azure AD 是与 Intune 集成的 Microsoft 管理系统，可帮助组织学生和设备。</span><span class="sxs-lookup"><span data-stu-id="ad66f-120">Azure AD is a Microsoft management system that integrates with Intune and helps organize students and devices.</span></span> <span data-ttu-id="ad66f-121">它可以创建组超出您的学生和教师，如*第四个时间段生物学*或*Contoso 学区教师*。</span><span class="sxs-lookup"><span data-stu-id="ad66f-121">It lets you create groups out of your students and teachers, such as *4th period Biology* or *Contoso District teachers*.</span></span> <span data-ttu-id="ad66f-122">组所需分配和分发用户或特定于设备的应用、 设置和限制。</span><span class="sxs-lookup"><span data-stu-id="ad66f-122">Groups are necessary to assign and distribute user or device-specific apps, settings, and restrictions.</span></span>

## <a name="next-steps"></a><span data-ttu-id="ad66f-123">后续步骤</span><span class="sxs-lookup"><span data-stu-id="ad66f-123">Next steps</span></span>   
<span data-ttu-id="ad66f-124">与 Intune for Education 同步你的学生和教师信息后，开始使用快速配置[Windows](edu-express-config-settings-windows.md)或[iOS](edu-express-config-settings-ios.md)设备。</span><span class="sxs-lookup"><span data-stu-id="ad66f-124">After your student and teacher information is synced with Intune for Education, get started with express configuration for [Windows](edu-express-config-settings-windows.md) or [iOS](edu-express-config-settings-ios.md) devices.</span></span>  

<span data-ttu-id="ad66f-125">想要了解有关 Microsoft 学校数据同步的详细信息？</span><span class="sxs-lookup"><span data-stu-id="ad66f-125">Want to know more about Microsoft School Data Sync?</span></span> <span data-ttu-id="ad66f-126">请访问[Microsoft 学校数据同步页](https://sds.microsoft.com)有关产品信息。</span><span class="sxs-lookup"><span data-stu-id="ad66f-126">Visit the [Microsoft School Data Sync page](https://sds.microsoft.com) for product information.</span></span> 
