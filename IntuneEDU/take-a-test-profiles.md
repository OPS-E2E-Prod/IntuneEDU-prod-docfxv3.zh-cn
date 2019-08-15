---
title: 需要 a Test 配置文件
titleSuffix: Intune for Education
description: 了解如何使用执行的测试配置文件来管理和捕获学生测试结果。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 3ad65b15-015a-402e-9dd5-0748dee79459
searchScope:
- IntuneEDU
ms.openlocfilehash: 18c4e4db1bfe3a5759058d5e4b3cc90945097146
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147513"
---
# <a name="add-a-take-a-test-profile-in-intune-for-education"></a><span data-ttu-id="24569-103">Intune for Education 中添加 Take a Test 配置文件</span><span class="sxs-lookup"><span data-stu-id="24569-103">Add a Take a Test profile in Intune for Education</span></span>

<span data-ttu-id="24569-104">Take a Test 应用可以安全地管理在线课堂的 Windows 10 设备上测试。</span><span class="sxs-lookup"><span data-stu-id="24569-104">The Take a Test app lets you securely administer online tests on your classroom's Windows 10 devices.</span></span>  <span data-ttu-id="24569-105">学生使用他们在登录到测试配置文件提供的凭据。</span><span class="sxs-lookup"><span data-stu-id="24569-105">Students use the credentials you provide for them to sign in to the test profile.</span></span> <span data-ttu-id="24569-106">然后单击要启动测试的评估 URL。</span><span class="sxs-lookup"><span data-stu-id="24569-106">Then they click the assessment URL to launch the test.</span></span> 
 
<span data-ttu-id="24569-107">本文介绍如何：</span><span class="sxs-lookup"><span data-stu-id="24569-107">This article describes how to:</span></span>
* <span data-ttu-id="24569-108">创建 Take a Test 配置文件。</span><span class="sxs-lookup"><span data-stu-id="24569-108">Create a Take a Test profile.</span></span>
* <span data-ttu-id="24569-109">将该配置文件分配给在您的学校的学生。</span><span class="sxs-lookup"><span data-stu-id="24569-109">Assign the profile to students in your school.</span></span>  

> [!NOTE]
> <span data-ttu-id="24569-110">为需要测试目的创建独占的用户。</span><span class="sxs-lookup"><span data-stu-id="24569-110">Create an exclusive user for Take a Test purposes.</span></span> <span data-ttu-id="24569-111">将 Take a Test 配置文件为此用户分配，以便不会影响学生或教师设备。</span><span class="sxs-lookup"><span data-stu-id="24569-111">Assign your Take a Test profile to this user so that you don't impact student or teacher devices.</span></span> <span data-ttu-id="24569-112">了解如何在 Windows 10 教育版，用户分配[Take 测试上设置多台 Pc](https://technet.microsoft.com/edu/windows/take-a-test-multiple-pcs)一文。</span><span class="sxs-lookup"><span data-stu-id="24569-112">Learn how to assign a user in the Windows 10 for Education, [Set up Take a Test on multiple PCs](https://technet.microsoft.com/edu/windows/take-a-test-multiple-pcs) article.</span></span>

## <a name="take-a-test-features"></a><span data-ttu-id="24569-113">测试功能</span><span class="sxs-lookup"><span data-stu-id="24569-113">Take a Test features</span></span>
<span data-ttu-id="24569-114">当一名学生启动测试时，他们的桌面锁定。</span><span class="sxs-lookup"><span data-stu-id="24569-114">When a student launches a test, their desktop locks.</span></span> <span data-ttu-id="24569-115">Take a Test 应用将打开新窗口中。</span><span class="sxs-lookup"><span data-stu-id="24569-115">The Take a Test app opens in a new window.</span></span> <span data-ttu-id="24569-116">采用测试清除系统剪贴板，以便学生不能复制并粘贴的内容。</span><span class="sxs-lookup"><span data-stu-id="24569-116">Take a Test clears the system's clipboard so that students can't copy and paste content.</span></span>

<span data-ttu-id="24569-117">虽然测试处于活动状态，但是不能测试对象：</span><span class="sxs-lookup"><span data-stu-id="24569-117">While a test is active, test takers cannot:</span></span>

* <span data-ttu-id="24569-118">请访问其他网站。</span><span class="sxs-lookup"><span data-stu-id="24569-118">Visit other websites.</span></span>
* <span data-ttu-id="24569-119">打开或访问其他应用。</span><span class="sxs-lookup"><span data-stu-id="24569-119">Open or access other apps.</span></span>
* <span data-ttu-id="24569-120">更改设置。</span><span class="sxs-lookup"><span data-stu-id="24569-120">Change settings.</span></span>
* <span data-ttu-id="24569-121">扩展显示。</span><span class="sxs-lookup"><span data-stu-id="24569-121">Extend the display.</span></span>  
* <span data-ttu-id="24569-122">请参阅通知。</span><span class="sxs-lookup"><span data-stu-id="24569-122">See notifications.</span></span>
* <span data-ttu-id="24569-123">接收应用程序和操作系统更新。</span><span class="sxs-lookup"><span data-stu-id="24569-123">Receive app and OS updates.</span></span>
* <span data-ttu-id="24569-124">收到文本建议。</span><span class="sxs-lookup"><span data-stu-id="24569-124">Receive text suggestions.</span></span>
* <span data-ttu-id="24569-125">使用 Cortana。</span><span class="sxs-lookup"><span data-stu-id="24569-125">Use Cortana.</span></span>
* <span data-ttu-id="24569-126">共享、 打印或记录设备屏幕上，除非学校或 IT 管理员允许的。</span><span class="sxs-lookup"><span data-stu-id="24569-126">Share, print, or record device screens, unless allowed by school or IT administrator.</span></span>

### <a name="how-is-assistive-technology-affected"></a><span data-ttu-id="24569-127">辅助技术如何影响？</span><span class="sxs-lookup"><span data-stu-id="24569-127">How is assistive technology affected?</span></span>
<span data-ttu-id="24569-128">某些设备功能-例如讲述人-和其他辅助技术仍然是完全正常运行时执行测试。</span><span class="sxs-lookup"><span data-stu-id="24569-128">Some device features--such as narrator--and other assistive technology are still fully functional while taking a test.</span></span> <span data-ttu-id="24569-129">有关应用功能的列表，请参阅[需要测试应用程序技术参考](https://docs.microsoft.com/education/windows/take-a-test-app-technical)。</span><span class="sxs-lookup"><span data-stu-id="24569-129">For a list of the apps features, see [Take a Test app technical reference](https://docs.microsoft.com/education/windows/take-a-test-app-technical).</span></span>


## <a name="take-a-test-profile-setup"></a><span data-ttu-id="24569-130">需要测试配置文件安装程序</span><span class="sxs-lookup"><span data-stu-id="24569-130">Take a Test profile setup</span></span>
<span data-ttu-id="24569-131">设置 Intune for Education 中的配置文件。</span><span class="sxs-lookup"><span data-stu-id="24569-131">Set up a profile in Intune for Education.</span></span> <span data-ttu-id="24569-132">在开始之前，我们建议您创建专用的用户帐户仅用于评估。</span><span class="sxs-lookup"><span data-stu-id="24569-132">Before you begin, we recommend that you create a dedicated user account used solely for assessments.</span></span> <span data-ttu-id="24569-133">用户将登录到此帐户来访问测试。</span><span class="sxs-lookup"><span data-stu-id="24569-133">Users will sign in to this account to access tests.</span></span> 

1. <span data-ttu-id="24569-134">从 Intune for Education 仪表板，单击**Take 测试配置文件**。</span><span class="sxs-lookup"><span data-stu-id="24569-134">From Intune for Education dashboard, click **Take a Test profiles**.</span></span>    
<span data-ttu-id="24569-135">![侧栏中的选项的列表](./media/dashboard-002-left-sidebar-list.png)</span><span class="sxs-lookup"><span data-stu-id="24569-135">![List of options in the sidebar](./media/dashboard-002-left-sidebar-list.png)</span></span>  
2.  <span data-ttu-id="24569-136">单击添加 Take a Test 配置文件。</span><span class="sxs-lookup"><span data-stu-id="24569-136">Click Add Take a Test profile.</span></span>  
 ![在左上方选择添加需要测试配置文件按钮](./media/takeatest-001-new-profile.png)  
3. <span data-ttu-id="24569-138">输入测试的描述性名称。</span><span class="sxs-lookup"><span data-stu-id="24569-138">Enter a descriptive name for the test.</span></span>  
<span data-ttu-id="24569-139">4 输入评估 URL。</span><span class="sxs-lookup"><span data-stu-id="24569-139">4 Enter the Assessment URL.</span></span>  
 ![需要测试配置文件窗口](./media/takeatest-002-new-profile-edit-window.png)  
5. <span data-ttu-id="24569-141">配置测试设置的其余部分：</span><span class="sxs-lookup"><span data-stu-id="24569-141">Configure the rest of the test settings:</span></span>    
    <span data-ttu-id="24569-142">a.</span><span class="sxs-lookup"><span data-stu-id="24569-142">a.</span></span> <span data-ttu-id="24569-143">允许屏幕捕获</span><span class="sxs-lookup"><span data-stu-id="24569-143">Allow screen capture</span></span>  
    <span data-ttu-id="24569-144">b.</span><span class="sxs-lookup"><span data-stu-id="24569-144">b.</span></span> <span data-ttu-id="24569-145">需要安装一个打印机的 Pc</span><span class="sxs-lookup"><span data-stu-id="24569-145">Require PCs to have a printer installed</span></span>  
    <span data-ttu-id="24569-146">c.</span><span class="sxs-lookup"><span data-stu-id="24569-146">c.</span></span> <span data-ttu-id="24569-147">允许文本建议</span><span class="sxs-lookup"><span data-stu-id="24569-147">Allow text suggestions</span></span>   
6. <span data-ttu-id="24569-148">从现有用户的列表中选择一个帐户。</span><span class="sxs-lookup"><span data-stu-id="24569-148">Select an account from your list of existing users.</span></span> <span data-ttu-id="24569-149">学生将使用该帐户的用户名和密码登录到相应的评估。</span><span class="sxs-lookup"><span data-stu-id="24569-149">Students will use the account's username and password to sign in to the appropriate assessment.</span></span>  

<span data-ttu-id="24569-150">若要查看的任何配置文件的详细信息，请从左侧和右侧的页上选择它。</span><span class="sxs-lookup"><span data-stu-id="24569-150">To view the details of any profile, select it from the left side of the page.</span></span> <span data-ttu-id="24569-151">然后单击**帐户**选项卡。</span><span class="sxs-lookup"><span data-stu-id="24569-151">Then click the **Account** tab.</span></span>  

## <a name="assign-or-change-groups"></a><span data-ttu-id="24569-152">分配或更改组</span><span class="sxs-lookup"><span data-stu-id="24569-152">Assign or change groups</span></span>
<span data-ttu-id="24569-153">将需要访问测试的配置文件的学生组分配。</span><span class="sxs-lookup"><span data-stu-id="24569-153">Assign groups of students that require access to the test profile.</span></span> <span data-ttu-id="24569-154">请按照这些步骤太组分配对进行编辑。</span><span class="sxs-lookup"><span data-stu-id="24569-154">Follow these steps to make edits to group assignments too.</span></span>
1. <span data-ttu-id="24569-155">从**Take 测试配置文件**页上，单击**组**选项卡。</span><span class="sxs-lookup"><span data-stu-id="24569-155">From the **Take a Test profiles** page, click the **Groups** tab.</span></span> 
2. <span data-ttu-id="24569-156">单击**更改组分配**。</span><span class="sxs-lookup"><span data-stu-id="24569-156">Click **Change group assignments**.</span></span> 
3. <span data-ttu-id="24569-157">选择一个或多个组从**的所有组**菜单。</span><span class="sxs-lookup"><span data-stu-id="24569-157">Select one or more groups from the **All Groups** menu.</span></span> <span data-ttu-id="24569-158">然后单击**添加组**。</span><span class="sxs-lookup"><span data-stu-id="24569-158">Then click **Add Groups**.</span></span> 
4. <span data-ttu-id="24569-159">若要从分配中删除一个组，请选择从组**分配的组**菜单。</span><span class="sxs-lookup"><span data-stu-id="24569-159">To remove a group from the assignment, select the group from the **Groups assigned** menu.</span></span> <span data-ttu-id="24569-160">然后单击**删除组**。</span><span class="sxs-lookup"><span data-stu-id="24569-160">Then click **Remove Groups**.</span></span>
5. <span data-ttu-id="24569-161">单击**确定**提交所做的更改。</span><span class="sxs-lookup"><span data-stu-id="24569-161">Click **Ok** to submit your changes.</span></span>

## <a name="delete-take-a-test-profile"></a><span data-ttu-id="24569-162">删除 Take a Test 配置文件</span><span class="sxs-lookup"><span data-stu-id="24569-162">Delete Take a Test profile</span></span>  
<span data-ttu-id="24569-163">删除 Take a Test 配置文件时，它将成为一个典型的用户帐户。</span><span class="sxs-lookup"><span data-stu-id="24569-163">When you delete a Take a Test profile, it becomes a typical user account.</span></span> <span data-ttu-id="24569-164">学生仍可以登录到帐户使用其现有的凭据，但从帐户中删除 URL 评估链接。</span><span class="sxs-lookup"><span data-stu-id="24569-164">Students are still able to sign in to the account with its existing credentials, but the URL assessment link is removed from the account.</span></span> <span data-ttu-id="24569-165">登录到的帐户将不再锁定的学生设备。</span><span class="sxs-lookup"><span data-stu-id="24569-165">Signing into the account will also no longer lock student devices.</span></span>

1. <span data-ttu-id="24569-166">从**Take 测试配置文件**页上，选择你想要删除的配置文件。</span><span class="sxs-lookup"><span data-stu-id="24569-166">From the **Take a Test profiles** page, choose the profile you want to delete.</span></span>
2. <span data-ttu-id="24569-167">单击**删除需要 a Test 配置文件**。</span><span class="sxs-lookup"><span data-stu-id="24569-167">Click **Delete Take a Test profile**.</span></span>
3. <span data-ttu-id="24569-168">单击**删除**来确认你的操作。</span><span class="sxs-lookup"><span data-stu-id="24569-168">Click **Delete** to confirm your action.</span></span>

<span data-ttu-id="24569-169">若要详细了解 Take 在你的设备上的测试，请参阅[Windows 10 中进行测试](https://technet.microsoft.com/edu/windows/take-tests-in-windows-10)。</span><span class="sxs-lookup"><span data-stu-id="24569-169">To find out more about Take a Test on your devices, see [Take a Test in Windows 10](https://technet.microsoft.com/edu/windows/take-tests-in-windows-10).</span></span>
