---
title: Intune for Education 中的远程设备操作
titleSuffix: Intune for Education
description: 了解如何使用远程操作排除故障并管理存有一定距离的设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/30/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: df7cabf2-1723-4817-b16c-800407a0c753
searchScope:
- IntuneEDU
ms.openlocfilehash: f19a24c78ad3a155b33ccc05bc266160fce7387e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146765"
---
# <a name="manage-devices-remotely"></a><span data-ttu-id="1b43a-103">远程管理设备</span><span class="sxs-lookup"><span data-stu-id="1b43a-103">Manage devices remotely</span></span>  

<span data-ttu-id="1b43a-104">如果你是在不同的位置不是设备或其用户，并且需要帮助他们进行故障排除，远程操作在中使用 Intune 教育版。</span><span class="sxs-lookup"><span data-stu-id="1b43a-104">If you're in a different location than a device or its user, and need to help them troubleshoot, use the remote actions in Intune for Education.</span></span>  


## <a name="remote-actions-for-devices"></a><span data-ttu-id="1b43a-105">适用于设备的远程操作</span><span class="sxs-lookup"><span data-stu-id="1b43a-105">Remote actions for devices</span></span>  

![示例屏幕截图： 显示 Intune 教育版的 7 的远程操作。](./media/1812_Intune_EDU_Manage_Remote.png)  

<span data-ttu-id="1b43a-107">从仪表板中，转到**设备**。</span><span class="sxs-lookup"><span data-stu-id="1b43a-107">From the dashboard, go to **Devices**.</span></span> <span data-ttu-id="1b43a-108">选择你想要管理的设备。</span><span class="sxs-lookup"><span data-stu-id="1b43a-108">Select the device that you want to manage.</span></span> <span data-ttu-id="1b43a-109">在页面的底部，选择任何以下操作：</span><span class="sxs-lookup"><span data-stu-id="1b43a-109">At the bottom of the page, select any of the following actions:</span></span>

- <span data-ttu-id="1b43a-110">**重新启动**:关闭设备提供支持，并重新启动它。</span><span class="sxs-lookup"><span data-stu-id="1b43a-110">**Restart**: Powers off the device and restarts it.</span></span>
- <span data-ttu-id="1b43a-111">**恢复出厂设置**：从 Intune 管理删除设备并删除设备上的所有数据和设置。</span><span class="sxs-lookup"><span data-stu-id="1b43a-111">**Factory reset**: Removes the device from Intune management and removes all data and settings from the device.</span></span> 
- <span data-ttu-id="1b43a-112">**同步设备**:确保该设备具有最新的设置、 应用分配和组成员身份。</span><span class="sxs-lookup"><span data-stu-id="1b43a-112">**Sync device**: Ensures that device has up-to-date settings, app assignments, and group memberships.</span></span> <span data-ttu-id="1b43a-113">如果您正在尝试进行设备进行故障排除，可帮助此操作。</span><span class="sxs-lookup"><span data-stu-id="1b43a-113">This action can help if you're trying to troubleshoot a device.</span></span>  
- <span data-ttu-id="1b43a-114">**Autopilot 重置**:删除所有用户数据&ndash;包括用户已安装的应用和个人设置&ndash;并保持在 Intune 中注册 Windows 10 设备。</span><span class="sxs-lookup"><span data-stu-id="1b43a-114">**Autopilot Reset**: Removes all user data&ndash;including user-installed apps and personal settings&ndash;and keeps the Windows 10 device enrolled in Intune.</span></span> <span data-ttu-id="1b43a-115">设备保持最新的应用、 策略和设置与最新。</span><span class="sxs-lookup"><span data-stu-id="1b43a-115">The device is kept up-to-date with the latest apps, policies, and settings.</span></span> <span data-ttu-id="1b43a-116">当开始重置时，会显示通知。</span><span class="sxs-lookup"><span data-stu-id="1b43a-116">A notification appears when the reset is initiated.</span></span> <span data-ttu-id="1b43a-117">设备重置的下次连接到 internet。</span><span class="sxs-lookup"><span data-stu-id="1b43a-117">The device resets the next time it connects to the internet.</span></span>  
- <span data-ttu-id="1b43a-118">**重命名设备**:为设备提供新名称。</span><span class="sxs-lookup"><span data-stu-id="1b43a-118">**Rename device**: Gives the device a new name.</span></span> <span data-ttu-id="1b43a-119">新名称更新在 Intune 中和本地设备上。</span><span class="sxs-lookup"><span data-stu-id="1b43a-119">The new name updates in Intune and locally, on the device.</span></span> <span data-ttu-id="1b43a-120">您必须重新启动 Windows 设备的新名称才会生效。</span><span class="sxs-lookup"><span data-stu-id="1b43a-120">You must restart your Windows device for the new name to take effect.</span></span>  
- <span data-ttu-id="1b43a-121">**删除设备**:取消注册设备从 Intune 教育版和从 Azure Active Directory 中删除设备。</span><span class="sxs-lookup"><span data-stu-id="1b43a-121">**Delete device**: Unenrolls the device from Intune for Education and removes the device from Azure Active Directory.</span></span> <span data-ttu-id="1b43a-122">已删除的设备不再可以访问您的学校资源。</span><span class="sxs-lookup"><span data-stu-id="1b43a-122">A deleted device can no longer access your school's resources.</span></span> 

## <a name="remote-actions-for-users"></a><span data-ttu-id="1b43a-123">用户的远程操作</span><span class="sxs-lookup"><span data-stu-id="1b43a-123">Remote actions for users</span></span>  

<span data-ttu-id="1b43a-124">从仪表板中，转到**用户**。</span><span class="sxs-lookup"><span data-stu-id="1b43a-124">From the dashboard, go to **Users**.</span></span> <span data-ttu-id="1b43a-125">选择你想要管理的用户。</span><span class="sxs-lookup"><span data-stu-id="1b43a-125">Select the user that you want to manage.</span></span> <span data-ttu-id="1b43a-126">在页面底部，选择**重置密码**。</span><span class="sxs-lookup"><span data-stu-id="1b43a-126">At the bottom of the page, select **Reset password**.</span></span> <span data-ttu-id="1b43a-127">此操作将在用户设备上的旧、 丢失或忘记了密码重置。</span><span class="sxs-lookup"><span data-stu-id="1b43a-127">This action resets an old, lost, or forgotten password on the user's device.</span></span>  
