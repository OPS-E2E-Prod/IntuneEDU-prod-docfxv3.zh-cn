---
title: 添加注册管理器
titleSuffix: Intune for Education
description: 了解如何在 Intune for Education 中添加注册管理器。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 08/30/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope:
- IntuneEDU
ms.openlocfilehash: 26b9a9c6eaabe85dbe77acd9a52f7b86b8a99d4d
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146969"
---
# <a name="add-enrollment-managers"></a><span data-ttu-id="9d5b0-103">添加注册管理器</span><span class="sxs-lookup"><span data-stu-id="9d5b0-103">Add enrollment managers</span></span>  

<span data-ttu-id="9d5b0-104">向你的现有用户的设备的注册权限。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-104">Give device enrollment permissions to your existing users.</span></span> <span data-ttu-id="9d5b0-105">使用设备注册管理器帐户的用户可以注册最多 1000 个中 Intune 教育版的 Windows 10 设备。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-105">Users with device enrollment manager accounts can enroll up to 1000 Windows 10 devices in Intune for Education.</span></span>

 <span data-ttu-id="9d5b0-106">注册管理员帐户是有成千上万个共享要注册的 Windows 10 设备的大型组织中有帮助。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-106">Enrollment manager accounts are helpful in large organizations that have thousands of shared Windows 10 devices to enroll.</span></span>  

## <a name="requirements"></a><span data-ttu-id="9d5b0-107">要求</span><span class="sxs-lookup"><span data-stu-id="9d5b0-107">Requirements</span></span>  

<span data-ttu-id="9d5b0-108">用户必须在 Azure 门户中存在才能添加为设备注册管理器。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-108">Users must exist in the Azure portal to be added as device enrollment managers.</span></span>

<span data-ttu-id="9d5b0-109">设备注册权限不能与以下其他注册方法结合使用：Apple Configurator 与设置助理、 Apple Configurator 与直接注册、 Apple School Manager (ASM) 或设备注册计划 (DEP)。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-109">Device enrollment permissions cannot be used with these other enrollment methods: Apple Configurator with Setup Assistant, Apple Configurator with direct enrollment, Apple School Manager (ASM), or Device Enrollment Program (DEP).</span></span>  

## <a name="assign-enrollment-permissions"></a><span data-ttu-id="9d5b0-110">分配注册权限</span><span class="sxs-lookup"><span data-stu-id="9d5b0-110">Assign enrollment permissions</span></span>  

1. <span data-ttu-id="9d5b0-111">从 Intune for Education 仪表板，单击**注册管理器**。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-111">From the Intune for Education dashboard, click **Enrollment Managers**.</span></span>
2. <span data-ttu-id="9d5b0-112">**单击分配注册权限**。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-112">**Click Assign enrollment permissions**.</span></span>
3. <span data-ttu-id="9d5b0-113">选择你想要向其分配权限的用户。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-113">Choose the user that you want to assign permissions to.</span></span> <span data-ttu-id="9d5b0-114">如果您知道用户的名称，您可以在搜索字段搜索它们。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-114">If you know the name of the user, you can search for them in the search field.</span></span>
4. <span data-ttu-id="9d5b0-115">单击“保存” 。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-115">Click **Save**.</span></span>

## <a name="remove-enrollment-permissions"></a><span data-ttu-id="9d5b0-116">删除注册权限</span><span class="sxs-lookup"><span data-stu-id="9d5b0-116">Remove enrollment permissions</span></span>  
1. <span data-ttu-id="9d5b0-117">从**注册管理器**，请转到屏幕的左侧，并选择用户。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-117">From **Enrollment Managers**, go to the left side of the screen and choose a user.</span></span> 
2. <span data-ttu-id="9d5b0-118">单击**删除注册权限**。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-118">Click **Remove enrollment permissions**.</span></span>
3. <span data-ttu-id="9d5b0-119">单击**删除**来确认你的操作。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-119">Click **Remove** to confirm your action.</span></span> <span data-ttu-id="9d5b0-120">删除设备注册管理器不会影响已注册的设备。</span><span class="sxs-lookup"><span data-stu-id="9d5b0-120">Removing a device enrollment manager does not affect enrolled devices.</span></span>
  <span data-ttu-id="9d5b0-121">![删除注册权限按钮处于选中状态时查看一个单独的注册管理器的页](./media/enroll-mgrs-003-remove-enrollment-permissions.png)</span><span class="sxs-lookup"><span data-stu-id="9d5b0-121">![Remove enrollment permissions button selected while viewing an individual Enrollment Manager's page](./media/enroll-mgrs-003-remove-enrollment-permissions.png)</span></span>
