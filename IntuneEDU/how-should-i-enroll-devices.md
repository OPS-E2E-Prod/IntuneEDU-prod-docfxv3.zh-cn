---
title: 如何注册设备？
titleSuffix: Intune for Education
description: 获取有关将设备注册到 Intune for Education 的方法的建议。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 45160df9-126d-4c51-a0d3-0e9fad0fe929
searchScope:
- IntuneEDU
ms.openlocfilehash: 006fa1267566524b86acbf0e5a29235f41eb5ac2
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866729"
---
# <a name="how-should-i-enroll-devices"></a><span data-ttu-id="a3c57-103">如何注册设备？</span><span class="sxs-lookup"><span data-stu-id="a3c57-103">How should I enroll devices?</span></span>

<span data-ttu-id="a3c57-104">了解如何在 Intune for Education 管理下注册设备。</span><span class="sxs-lookup"><span data-stu-id="a3c57-104">Learn how to enroll devices under Intune for Education management.</span></span> <span data-ttu-id="a3c57-105">若要为你的学校选择最佳方法, 请考虑:</span><span class="sxs-lookup"><span data-stu-id="a3c57-105">To choose the best method for your school, consider the:</span></span>  
* <span data-ttu-id="a3c57-106">区域大小。</span><span class="sxs-lookup"><span data-stu-id="a3c57-106">Size of your district.</span></span>    
* <span data-ttu-id="a3c57-107">设备收件人的类型。</span><span class="sxs-lookup"><span data-stu-id="a3c57-107">Type of device recipients.</span></span>    
* <span data-ttu-id="a3c57-108">可用于帮助的员工数。</span><span class="sxs-lookup"><span data-stu-id="a3c57-108">Number of staff available to help.</span></span>   
 
<span data-ttu-id="a3c57-109">请继续阅读, 以确定在学校注册设备的最佳方式。</span><span class="sxs-lookup"><span data-stu-id="a3c57-109">Read on to determine the best way to enroll devices in your school.</span></span>    

## <a name="run-the-set-up-school-pcs-app"></a><span data-ttu-id="a3c57-110">运行 "设置 School Pc" 应用</span><span class="sxs-lookup"><span data-stu-id="a3c57-110">Run the Set up School PCs app</span></span> 
<span data-ttu-id="a3c57-111">将一组学校优化的设置上载到每个 Windows 10 电脑。</span><span class="sxs-lookup"><span data-stu-id="a3c57-111">Upload a single set of school-optimized settings to each of your Windows 10 PCs.</span></span> <span data-ttu-id="a3c57-112">"[设置 School pc" 应用](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)指导您如何创建适合学校的安装包。</span><span class="sxs-lookup"><span data-stu-id="a3c57-112">The [Set up School PCs app](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) guides you through how to create an installation package that's appropriate for schools.</span></span> <span data-ttu-id="a3c57-113">完成配置网络和设备的设置后, 应用会将包保存到 USB 驱动器。</span><span class="sxs-lookup"><span data-stu-id="a3c57-113">After you're done configuring settings for your network and devices, the app saves the package to a USB drive.</span></span> <span data-ttu-id="a3c57-114">将 u 盘直接插入每台学生电脑, 为学生自动设置设备。</span><span class="sxs-lookup"><span data-stu-id="a3c57-114">Insert the USB drive directly in to each student PC to automatically set up the device for your students.</span></span> <span data-ttu-id="a3c57-115">应用在运行 Windows 10 版本1903及更早版本的电脑上兼容。</span><span class="sxs-lookup"><span data-stu-id="a3c57-115">The app is compatible on PCs running Windows 10 version 1903 and earlier.</span></span>

## <a name="give-school-faculty-enrollment-manager-permissions"></a><span data-ttu-id="a3c57-116">为 school 教职员注册管理员权限</span><span class="sxs-lookup"><span data-stu-id="a3c57-116">Give school faculty enrollment manager permissions</span></span>
<span data-ttu-id="a3c57-117">添加注册管理器或注册管理员帐户, 以允许你的员工帮助你注册设备。</span><span class="sxs-lookup"><span data-stu-id="a3c57-117">Add enrollment managers, or an enrollment manager account, to allow your staff to help you enroll devices.</span></span> <span data-ttu-id="a3c57-118">[注册管理员](add-enrollment-managers.md)最多可注册1000设备。</span><span class="sxs-lookup"><span data-stu-id="a3c57-118">[Enrollment managers](add-enrollment-managers.md) can enroll up to 1,000 devices.</span></span>  

## <a name="allow-users-to-enroll-their-own-devices"></a><span data-ttu-id="a3c57-119">允许用户注册其自己的设备</span><span class="sxs-lookup"><span data-stu-id="a3c57-119">Allow users to enroll their own devices</span></span>
<span data-ttu-id="a3c57-120">允许受信任的用户注册其自己的设备。</span><span class="sxs-lookup"><span data-stu-id="a3c57-120">Allow trusted users to enroll their own devices.</span></span> <span data-ttu-id="a3c57-121">这些用户可以自动将其设备加入 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="a3c57-121">These users are able to automatically join their devices to Azure AD.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="a3c57-122">后续步骤</span><span class="sxs-lookup"><span data-stu-id="a3c57-122">Next steps</span></span>  

<span data-ttu-id="a3c57-123">已准备好注册设备？</span><span class="sxs-lookup"><span data-stu-id="a3c57-123">Ready to enroll your devices?</span></span> <span data-ttu-id="a3c57-124">了解如何在 Intune for Education 管理下添加[iOS](add-devices-ios-edu.md)和[Windows 10](add-devices-windows.md)设备。</span><span class="sxs-lookup"><span data-stu-id="a3c57-124">Learn how to add [iOS](add-devices-ios-edu.md) and [Windows 10](add-devices-windows.md) devices under Intune for Education management.</span></span>  

* <span data-ttu-id="a3c57-125">请参阅应用商店文档, 从 Microsoft Store[下载**设置学校电脑**应用](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40)。</span><span class="sxs-lookup"><span data-stu-id="a3c57-125">See the Store documentation to [download the **Set Up School PCs** app](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40) from the Microsoft Store.</span></span> 
* <span data-ttu-id="a3c57-126">若要深入[了解如何在学校中设置 windows 设备](https://docs.microsoft.com/education/windows/set-up-windows-10), 请参阅 Microsoft 教育 > windows 文档。</span><span class="sxs-lookup"><span data-stu-id="a3c57-126">Find out more [about setting up Windows devices in schools](https://docs.microsoft.com/education/windows/set-up-windows-10) from the Microsoft Education > Windows documentation.</span></span>

