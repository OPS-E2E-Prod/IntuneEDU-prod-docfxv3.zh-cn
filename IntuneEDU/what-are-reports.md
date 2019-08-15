---
title: 查看和下载 Intune for Education 中的报表
titleSuffix: Intune for Education
description: 获取报表，以帮助您了解设备、 设置和 Intune for Education 中的应用程序活动。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: a5922c35-261c-43db-9c7b-c5c93af9cbec
searchScope:
- IntuneEDU
ms.reviewer: travisj
ms.openlocfilehash: 8bc3fe827d3ca1b37a1b0f8ab226d4d15a30db05
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147207"
---
# <a name="view-and-download-reports"></a><span data-ttu-id="5f3ff-103">查看和下载报表</span><span class="sxs-lookup"><span data-stu-id="5f3ff-103">View and download reports</span></span>  

<span data-ttu-id="5f3ff-104">Intune for Education 中查看当前的设备，应用程序、 设置和运行状况清单。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-104">View your current device, application, setting, and health inventory in Intune for Education.</span></span> <span data-ttu-id="5f3ff-105">下载报表来查看或共享脱机。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-105">Download reports to review or share offline.</span></span>

<span data-ttu-id="5f3ff-106">本文介绍了可用的报告以及如何在 Intune for Education 中看到它们。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-106">This article describes the reports available and how to see them in Intune for Education.</span></span>

## <a name="device-inventory"></a><span data-ttu-id="5f3ff-107">设备清单</span><span class="sxs-lookup"><span data-stu-id="5f3ff-107">Device inventory</span></span>
<span data-ttu-id="5f3ff-108">查看所有您学校的受管理的设备和设备详细信息。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-108">View all of your school's managed devices and device details.</span></span> <span data-ttu-id="5f3ff-109">如果设备运行不正常或未收到应用或设置，您可以参考此报表以了解何时它上次签入的使用 Intune。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-109">If a device is malfunctioning or hasn't received an app or setting, you can refer to this report to find out when it last checked-in with Intune.</span></span>   

   ![设备清单报表屏幕，其中显示在 Intune 教育版管理的设备的列表。](./media/reports-001-device-inventory.png)

## <a name="application-inventory"></a><span data-ttu-id="5f3ff-111">应用程序清单</span><span class="sxs-lookup"><span data-stu-id="5f3ff-111">Application inventory</span></span>
<span data-ttu-id="5f3ff-112">查看安装在您的学校中的托管设备上的所有应用。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-112">View all apps installed on the managed devices in your school.</span></span> <span data-ttu-id="5f3ff-113">此报表提供详细信息，可帮助您解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-113">This report provides details that will help you troubleshoot deployment problems.</span></span> <span data-ttu-id="5f3ff-114">请参阅重要详细信息，例如多个应用所属的设备和当前安装的版本。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-114">See important details such as the number of devices the app belongs to and the current version installed.</span></span>  
 
 ![应用程序清单报表屏幕，其中显示在 Intune 教育版管理的应用的列表。](./media/reports-002-app-inventory.png)  

## <a name="settings-errors"></a><span data-ttu-id="5f3ff-116">设置错误</span><span class="sxs-lookup"><span data-stu-id="5f3ff-116">Settings errors</span></span>
<span data-ttu-id="5f3ff-117">查看当前设置错误和受影响的组的列表。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-117">View a list of current setting errors and the groups affected.</span></span> <span data-ttu-id="5f3ff-118">此报表列出的设备和用户有冲突，无法解析的设置。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-118">This report lists both the devices and users that have conflicting, unresolved settings.</span></span>   

   ![设置错误报告屏幕，其中显示的设置冲突列表。](./media/reports-003-settings-error.png)

## <a name="windows-defender"></a><span data-ttu-id="5f3ff-120">Windows Defender</span><span class="sxs-lookup"><span data-stu-id="5f3ff-120">Windows Defender</span></span>
<span data-ttu-id="5f3ff-121">在您的学校中查看每个托管设备的 Windows Defender 设备运行状况状态。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-121">View the Windows Defender device health status for every managed device in your school.</span></span> <span data-ttu-id="5f3ff-122">此报表列出了设备运行状况状态，提醒用户不是完全安全的设备。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-122">This report lists a device health status to alert you to devices that are not fully secure.</span></span> 

## <a name="access-your-reports"></a><span data-ttu-id="5f3ff-123">访问你的报表</span><span class="sxs-lookup"><span data-stu-id="5f3ff-123">Access your reports</span></span>

1. <span data-ttu-id="5f3ff-124">从[Intune for Education 仪表板](https://intuneeducation.portal.azure.com)，单击**报表**。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-124">From the [Intune for Education dashboard](https://intuneeducation.portal.azure.com), click **Reports**.</span></span>  
2. <span data-ttu-id="5f3ff-125">选择你想要查看的报表。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-125">Select the report you want to view.</span></span> 
3. <span data-ttu-id="5f3ff-126">使用搜索框查找特定设备、 应用和设置。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-126">Use the search boxes to find specific devices, applications, and settings.</span></span>
4. <span data-ttu-id="5f3ff-127">若要下载的报表，请单击**下载报告**。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-127">To download a report, click **Download report**.</span></span> <span data-ttu-id="5f3ff-128">Intune for Education 可为以逗号分隔值 (.csv) 文件将下载到计算机，报表。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-128">Intune for Education will download a report to your computer, as a comma-separated value (.csv) file.</span></span> <span data-ttu-id="5f3ff-129">视图和 modiy 文件在电子表格应用程序，如[Microsoft Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba)。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-129">View and modiy the file in a spreadsheet app, such as [Microsoft Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba).</span></span>  

## <a name="next-steps"></a><span data-ttu-id="5f3ff-130">后续步骤</span><span class="sxs-lookup"><span data-stu-id="5f3ff-130">Next steps</span></span>  
<span data-ttu-id="5f3ff-131">详细了解如何[完整报告在 Intune 中的体验](https://docs.microsoft.com/intune/deploy-use/understand-microsoft-intune-operations-by-using-reports)或有关报表[使用 Microsoft Graph](https://developer.microsoft.com/graph/docs/overview/overview)。</span><span class="sxs-lookup"><span data-stu-id="5f3ff-131">Find out more about the [full reporting experience in Intune](https://docs.microsoft.com/intune/deploy-use/understand-microsoft-intune-operations-by-using-reports) or about reporting [using Microsoft Graph](https://developer.microsoft.com/graph/docs/overview/overview).</span></span>
