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
# <a name="troubleshooting-group-actions"></a><span data-ttu-id="05970-103">故障排除组操作</span><span class="sxs-lookup"><span data-stu-id="05970-103">Troubleshooting group actions</span></span>

<span data-ttu-id="05970-104">本文回答了有关创建和编辑 Intune for Education 中的组的常见问题。</span><span class="sxs-lookup"><span data-stu-id="05970-104">This article answers common questions about creating and editing groups in Intune for Education.</span></span>

## <a name="why-cant-i-edit-the-default-groups"></a><span data-ttu-id="05970-105">为什么无法编辑默认组？</span><span class="sxs-lookup"><span data-stu-id="05970-105">Why can't I edit the default groups?</span></span>

<span data-ttu-id="05970-106">在创建你的帐户时，Intune for Education 创建一组默认情况下，租户级别的组。</span><span class="sxs-lookup"><span data-stu-id="05970-106">At the time that you create your account, Intune for Education creates a set of default, tenant-level groups.</span></span> <span data-ttu-id="05970-107">这些组&ndash;**的所有用户**并**所有设备**&ndash;不能更改。</span><span class="sxs-lookup"><span data-stu-id="05970-107">These groups&ndash;**All Users** and **All Devices**&ndash;can't be changed.</span></span> <span data-ttu-id="05970-108">Intune 从学校数据同步中导入你的学校和教师记录后，创建更多的组，称为**所有教师**并**的所有学生**。</span><span class="sxs-lookup"><span data-stu-id="05970-108">After you import your school and teacher records from School Data Sync, Intune creates additional groups, called **All Teachers** and **All Students**.</span></span> <span data-ttu-id="05970-109">这些组也无法更改。</span><span class="sxs-lookup"><span data-stu-id="05970-109">These groups can't be changed either.</span></span>

<span data-ttu-id="05970-110">在极少数情况下，您可能会得到下面两个组的相同子组。</span><span class="sxs-lookup"><span data-stu-id="05970-110">In rare situations, you might end up with the same subgroup underneath two groups.</span></span> <span data-ttu-id="05970-111">如果出现此问题，请移动其中一个子组上方的顶级组。</span><span class="sxs-lookup"><span data-stu-id="05970-111">If this problem occurs, move one of the top-level groups above the subgroup.</span></span>

## <a name="why-cant-i-edit-dynamic-groups"></a><span data-ttu-id="05970-112">为什么不能编辑动态组？</span><span class="sxs-lookup"><span data-stu-id="05970-112">Why can't I edit dynamic groups?</span></span>

<span data-ttu-id="05970-113">Intune for Education，你选择从 Intune 的完整的管理门户中的动态属性的子集。</span><span class="sxs-lookup"><span data-stu-id="05970-113">Intune for Education lets you pick from a subset of dynamic attributes in Intune's full management portal.</span></span> <span data-ttu-id="05970-114">如果你想要编辑的属性不是 Intune for Education 门户中可见的则你必须在 Azure 门户或 Azure Active Directory 中而在 Intune 中进行编辑。</span><span class="sxs-lookup"><span data-stu-id="05970-114">If the attribute that you want to edit is not visible in the Intune for Education portal, you must edit it in Intune in the Azure portal or Azure Active Directory.</span></span>

## <a name="why-cant-i-edit-a-specific-group"></a><span data-ttu-id="05970-115">为什么不能编辑特定的组？</span><span class="sxs-lookup"><span data-stu-id="05970-115">Why can't I edit a specific group?</span></span>  

<span data-ttu-id="05970-116">Intune for Education 旨在作为管理你的学校中的设备的简单办法。</span><span class="sxs-lookup"><span data-stu-id="05970-116">Intune for Education is designed to be an easy way to manage devices in your schools.</span></span> <span data-ttu-id="05970-117">它使用[Azure 门户中的 Intune](https://docs.microsoft.com/intune/what-is-intune)&ndash;企业产品&ndash;来管理应用程序和组。</span><span class="sxs-lookup"><span data-stu-id="05970-117">It uses [Intune in the Azure portal](https://docs.microsoft.com/intune/what-is-intune)&ndash;an enterprise product&ndash;to manage apps and groups.</span></span> <span data-ttu-id="05970-118">你的组织中的某些管理员有权使用 Azure 门户中的 Intune 和 Intune for Education 创建特殊的组。</span><span class="sxs-lookup"><span data-stu-id="05970-118">Certain admins in your organization have permission to use both Intune in the Azure portal and Intune for Education to create special groups.</span></span> <span data-ttu-id="05970-119">如果您不能编辑组，则可能在 Intune 中创建在 Azure 门户中，并且你没有权限来修改组。</span><span class="sxs-lookup"><span data-stu-id="05970-119">If you can't edit a group, it's likely that it was created in Intune in the Azure portal, and you don't have permissions to modify the group.</span></span>  
