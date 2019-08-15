---
title: 将桌面应用添加到 Intune for Education
titleSuffix: Intune for Education
description: 了解如何上传并将新的桌面应用程序文件添加到 Intune for Education。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.openlocfilehash: 91c7a3bd20bcc51000ce16a1f77109c2093bb21b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146034"
---
# <a name="add-desktop-apps-in-intune-for-education"></a><span data-ttu-id="c5f1a-103">Intune for Education 中添加桌面应用程序</span><span class="sxs-lookup"><span data-stu-id="c5f1a-103">Add desktop apps in Intune for Education</span></span>

<span data-ttu-id="c5f1a-104">上传并将桌面应用程序添加到你的 Intune for Education 清单。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-104">Upload and add desktop apps to your Intune for Education inventory.</span></span> <span data-ttu-id="c5f1a-105">添加应用后，你可以[将其分配给组](install-apps.md)和 Windows 10 设备上安装它们。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-105">After you've added the apps, you can [assign them to groups](install-apps.md) and install them on your Windows 10 devices.</span></span>  

<span data-ttu-id="c5f1a-106">若要完成这些步骤，将你想要添加的应用需要的安装文件。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-106">To complete these steps, you will need the installation file for the app that you want to add.</span></span>  

1. <span data-ttu-id="c5f1a-107">登录到 Intune for Education 门户。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-107">Sign in to the Intune for Education portal.</span></span>
2. <span data-ttu-id="c5f1a-108">单击“应用”。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-108">Click **Apps**.</span></span>
3. <span data-ttu-id="c5f1a-109">在左窗格中下,**桌面应用**，单击**新的应用程序**。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-109">In the left pane, under **DESKTOP APPS**, click **New app**.</span></span>
4. <span data-ttu-id="c5f1a-110">在中**新的桌面应用程序**部分中，输入以下详细信息：</span><span class="sxs-lookup"><span data-stu-id="c5f1a-110">In the **New desktop app** section, enter the following details:</span></span>
   * <span data-ttu-id="c5f1a-111">**应用文件**-上传应用程序的 MSI 安装程序。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-111">**App file** — Upload an MSI installer for the app.</span></span>
   * <span data-ttu-id="c5f1a-112">**应用名称**-应用在设备上显示的名称。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-112">**App name** — The name of the app to appear on devices.</span></span>
   * <span data-ttu-id="c5f1a-113">**说明**— 说明的应用程序可以帮助您快速识别它。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-113">**Description** — A description of the app that will help you quickly identify it.</span></span>
   * <span data-ttu-id="c5f1a-114">**发布服务器**— 名称应用发布者，可帮助你快速标识应用程序开发人员。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-114">**Publisher** — The name of the app publisher, to help you quickly identify the app developer.</span></span>
   * <span data-ttu-id="c5f1a-115">**图标**-上载 PNG 或 JPG 文件，以用作应用程序的图标。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-115">**Icon** — Upload a PNG or JPG file to use as the app's icon.</span></span>
5. <span data-ttu-id="c5f1a-116">单击文件夹图标并选择应用安装文件从您的计算机。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-116">Click the folder icon and select the app installation file from your computer.</span></span> 
6. <span data-ttu-id="c5f1a-117">单击“保存” 。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-117">Click **Save**.</span></span> <span data-ttu-id="c5f1a-118">然后，应用将上载到 Intune for Education。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-118">The app will then upload to Intune for Education.</span></span> <span data-ttu-id="c5f1a-119">上传完成后，你可以[将应用分配给设备](install-apps.md)。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-119">Once the upload is complete, you can [assign the app to devices](install-apps.md).</span></span> 

   ![添加新的桌面应用程序屏幕，示例应用程序，evernote 填写所有字段。](./media/apps-004-filled-out-desktop-app.png)  

> [!NOTE]
> <span data-ttu-id="c5f1a-121">如果遇到错误，"应用程序没有安装文件"或"任何应用程序安装文件已添加"，该文件未正确上传。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-121">If you run into the error, "The app doesn't have an install file" or "No app install file was added," the file didn't upload properly.</span></span> <span data-ttu-id="c5f1a-122">若要解决此问题，请尝试上传和重新保存该文件。</span><span class="sxs-lookup"><span data-stu-id="c5f1a-122">To fix this, try to upload and save the file again.</span></span>
