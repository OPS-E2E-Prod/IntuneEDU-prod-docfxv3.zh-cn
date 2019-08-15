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
# <a name="delegate-admin-permissions-to-groups"></a><span data-ttu-id="2f5b7-103">委派的管理员权限组</span><span class="sxs-lookup"><span data-stu-id="2f5b7-103">Delegate admin permissions to groups</span></span>
<span data-ttu-id="2f5b7-104">您和您的 IT 员工在您的学校整个中管理多个组的学生、 教师和管理员。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-104">You and your IT staff manage multiple groups of students, teachers, and administrators throughout your school.</span></span>  

<span data-ttu-id="2f5b7-105">与 IT 人员不同管理员组只能管理向其分配的组。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-105">Unlike IT staff, admin groups only manage the groups you assign to them.</span></span> <span data-ttu-id="2f5b7-106">当您向合格人员的组的管理员权限时，有助于降低未经授权或意外的更改的风险。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-106">When you give admin permissions to a group of qualified individuals, you help reduce the risk of unauthorized or accidental changes.</span></span>  

## <a name="group-admin-permissions"></a><span data-ttu-id="2f5b7-107">组管理员权限</span><span class="sxs-lookup"><span data-stu-id="2f5b7-107">Group admin permissions</span></span> 

<span data-ttu-id="2f5b7-108">组管理员分配 Intune for Education 中，并且有权管理学校设备和应用。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-108">Group admins are assigned in Intune for Education and have permission to manage school devices and apps.</span></span> <span data-ttu-id="2f5b7-109">组管理员可以：</span><span class="sxs-lookup"><span data-stu-id="2f5b7-109">Group admins can:</span></span>  

- <span data-ttu-id="2f5b7-110">查看有关设备、 用户和应用程序的信息。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-110">View information about devices, users, and apps.</span></span>
- <span data-ttu-id="2f5b7-111">分配、 创建、 删除、 查看和更新设备和用户设置。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-111">Assign, create, delete, view, and update device and user settings.</span></span>
- <span data-ttu-id="2f5b7-112">分配、 创建、 删除、 查看和更新应用。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-112">Assign, create, delete, view, and update apps.</span></span>
- <span data-ttu-id="2f5b7-113">查看报表。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-113">View reports.</span></span>
- <span data-ttu-id="2f5b7-114">包括重置为出厂设置、 重新启动、 未锁定的设备，锁定和强制同步的设备上执行远程操作。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-114">Take remote actions on devices, including resetting to factory settings, rebooting, locking an unlocked device, and forcing a sync.</span></span>  
- <span data-ttu-id="2f5b7-115">创建、 删除、 查看和更新 iOS MDM Push Certificate、 iOS MDM server 令牌和 iOS VPP 令牌。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-115">Create, delete, view, and update the iOS MDM Push Certificate, iOS MDM server tokens, and iOS VPP tokens.</span></span>   

> [!TIP]
> <span data-ttu-id="2f5b7-116">修改管理员权限是一项高级的任务。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-116">Modifying admin permissions is an advanced task.</span></span> <span data-ttu-id="2f5b7-117">如果你想要更改的权限或创建一组自定义的权限，则需要转到[完整管理体验中 Intune](https://docs.microsoft.com/intune/role-based-access-control)。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-117">If you want to change the permissions or create a custom set of permissions, then you need to go to [the full management experience in Intune](https://docs.microsoft.com/intune/role-based-access-control).</span></span> <span data-ttu-id="2f5b7-118">这些权限包含在 Intune 中内置的学校的管理员角色。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-118">These permissions comprise the built-in School Administrator role in Intune.</span></span> 

## <a name="assign-an-admin-group"></a><span data-ttu-id="2f5b7-119">将分配一个管理组</span><span class="sxs-lookup"><span data-stu-id="2f5b7-119">Assign an admin group</span></span>

1. <span data-ttu-id="2f5b7-120">从 Intune for Education 仪表板，单击**组**。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-120">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="2f5b7-121">选择的组。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-121">Choose a group.</span></span> <span data-ttu-id="2f5b7-122">此组将是你的管理员管理。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-122">This group will be the one your admins manage.</span></span>
3. <span data-ttu-id="2f5b7-123">单击**Admins**选项卡 >**添加管理员**。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-123">Click the **Admins** tab > **Add Admins**.</span></span>
4. <span data-ttu-id="2f5b7-124">选择要为其提供管理应用和设置的管理员权限的组。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-124">Choose a group to give it admin permission to manage apps and settings.</span></span>
5. <span data-ttu-id="2f5b7-125">单击**选择组**。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-125">Click **Choose group**.</span></span>

## <a name="remove-an-admin-group"></a><span data-ttu-id="2f5b7-126">删除一个管理组</span><span class="sxs-lookup"><span data-stu-id="2f5b7-126">Remove an admin group</span></span>
1. <span data-ttu-id="2f5b7-127">从 Intune for Education 仪表板，单击**组**。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-127">From the Intune for Education dashboard, click **Groups**.</span></span>
2. <span data-ttu-id="2f5b7-128">选择的组。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-128">Choose a group.</span></span> <span data-ttu-id="2f5b7-129">此组将从管理中删除一个管理组的一个。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-129">This group will be the one you remove an admin group from managing.</span></span>
3. <span data-ttu-id="2f5b7-130">单击**管理员**选项卡。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-130">Click the **Admins** tab.</span></span>
4. <span data-ttu-id="2f5b7-131">从管理员的列表中选择一个或多个组。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-131">Select one or more groups from the list of admins.</span></span> <span data-ttu-id="2f5b7-132">然后单击**删除管理员**。</span><span class="sxs-lookup"><span data-stu-id="2f5b7-132">Then click **Remove Admins**.</span></span>  
