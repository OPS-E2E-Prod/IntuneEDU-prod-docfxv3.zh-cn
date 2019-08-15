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
# <a name="what-is-settings-inheritance"></a><span data-ttu-id="89e7a-103">什么是设置继承？</span><span class="sxs-lookup"><span data-stu-id="89e7a-103">What is settings inheritance?</span></span>

<span data-ttu-id="89e7a-104">设置应用于组中。</span><span class="sxs-lookup"><span data-stu-id="89e7a-104">Settings are applied to groups.</span></span> <span data-ttu-id="89e7a-105">因为组将设置为层次结构，与上面另一个组及其子组由继承应用于组的所有设置。</span><span class="sxs-lookup"><span data-stu-id="89e7a-105">Since groups are set up as hierarchies, with one group above another, all settings applied to a group are inherited by its subgroups.</span></span> <span data-ttu-id="89e7a-106">您对其上方的组发生更改时自动执行子组。</span><span class="sxs-lookup"><span data-stu-id="89e7a-106">Subgroups automatically take on the changes you make to the group above it.</span></span> <span data-ttu-id="89e7a-107">此操作称为_继承_。</span><span class="sxs-lookup"><span data-stu-id="89e7a-107">This action is called _inheritance_.</span></span> <span data-ttu-id="89e7a-108">设置继承 ia 想要将设置应用于大量用户和设备时，很有帮助。</span><span class="sxs-lookup"><span data-stu-id="89e7a-108">Settings inheritance ia helpful when you want to apply settings to large groups of users and devices.</span></span>  


  ![组和子组的树。](./media/groups-002-inheritance.png)  


## <a name="configure-subgroups-individually"></a><span data-ttu-id="89e7a-110">单独配置子组</span><span class="sxs-lookup"><span data-stu-id="89e7a-110">Configure subgroups individually</span></span>  

<span data-ttu-id="89e7a-111">若要覆盖最近继承的设置，直接转到子组。</span><span class="sxs-lookup"><span data-stu-id="89e7a-111">To override recently inherited settings, go directly to the subgroup.</span></span> <span data-ttu-id="89e7a-112">它单独配置通过删除或添加设置。</span><span class="sxs-lookup"><span data-stu-id="89e7a-112">Configure it individually by removing or adding settings.</span></span> <span data-ttu-id="89e7a-113">然后保存所做的更改。</span><span class="sxs-lookup"><span data-stu-id="89e7a-113">Then save your changes.</span></span>

## <a name="settings-in-conflict"></a><span data-ttu-id="89e7a-114">发生冲突的设置</span><span class="sxs-lookup"><span data-stu-id="89e7a-114">Settings in conflict</span></span>  

<span data-ttu-id="89e7a-115">如果将冲突的设置应用到相同的组，Intune 将单独分析每个。</span><span class="sxs-lookup"><span data-stu-id="89e7a-115">If you apply conflicting settings to the same group, Intune will analyze each one individually.</span></span> <span data-ttu-id="89e7a-116">Intune 将始终选择的设置确定，符合学校策略。</span><span class="sxs-lookup"><span data-stu-id="89e7a-116">Intune always chooses the settings that, with certainty, complies with school policies.</span></span>

<span data-ttu-id="89e7a-117">在其他情况下，当 Intune 不能解决该冲突，则应该查看[设置冲突](what-are-reports.md)报表。</span><span class="sxs-lookup"><span data-stu-id="89e7a-117">In other cases, when Intune can't resolve the conflict, you should review the [settings conflict](what-are-reports.md) report.</span></span>

### <a name="example-of-inheritance-conflict"></a><span data-ttu-id="89e7a-118">继承冲突示例</span><span class="sxs-lookup"><span data-stu-id="89e7a-118">Example of inheritance conflict</span></span>  

<span data-ttu-id="89e7a-119">作为示例，请考虑子组，*第 12 年级 AP 计算机科学*。</span><span class="sxs-lookup"><span data-stu-id="89e7a-119">As an example, consider the subgroup, *12th Grade AP Computer Science*.</span></span> <span data-ttu-id="89e7a-120">子组所属的父组中，*第 12 年级*。</span><span class="sxs-lookup"><span data-stu-id="89e7a-120">The subgroup falls under the parent group, *12th grade*.</span></span> <span data-ttu-id="89e7a-121">分配严格的安全扫描的所有文件的要求和应用程序被下载中的设备*第 12 年级*组。</span><span class="sxs-lookup"><span data-stu-id="89e7a-121">You assign a strict security scanning requirement to all files and apps downloaded devices in the *12th grade* group.</span></span>

<span data-ttu-id="89e7a-122">但是，对于即将发布的分配，知道该*第 12 年级 AP 计算机科学*必须下载不需要扫描的 JavaScript 文件。</span><span class="sxs-lookup"><span data-stu-id="89e7a-122">However, you know that for an upcoming assignment, *12th Grade AP Computer Science* must download JavaScript files that don't need to be scanned.</span></span> <span data-ttu-id="89e7a-123">如果不替代更严格的设置继承*第 12 个等级*设置将应用于中的用户*第 12 个等级 AP 计算机科学*。</span><span class="sxs-lookup"><span data-stu-id="89e7a-123">If you don't override settings inheritance, the more restrictive *Twelfth Grade* setting will be applied to the users in *Twelfth Grade AP Computer Science*.</span></span>

## <a name="settings-error-report"></a><span data-ttu-id="89e7a-124">设置错误报告</span><span class="sxs-lookup"><span data-stu-id="89e7a-124">Settings error report</span></span>

<span data-ttu-id="89e7a-125">如果无法解析设置，则会在设置错误报告中。</span><span class="sxs-lookup"><span data-stu-id="89e7a-125">If a setting can't be resolved, it will appear in the Settings error report.</span></span> <span data-ttu-id="89e7a-126">有关报表的详细信息，请参阅[查看和下载报表](what-are-reports.md)。</span><span class="sxs-lookup"><span data-stu-id="89e7a-126">For more information about reports, see [View and download reports](what-are-reports.md).</span></span>  

## <a name="next-steps"></a><span data-ttu-id="89e7a-127">后续步骤</span><span class="sxs-lookup"><span data-stu-id="89e7a-127">Next steps</span></span>  
<span data-ttu-id="89e7a-128">详细了解如何[在 Intune 中的完整组体验](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)。</span><span class="sxs-lookup"><span data-stu-id="89e7a-128">Find out more about the [full groups experience in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune).</span></span>
