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
# <a name="add-a-take-a-test-profile-in-intune-for-education"></a>Intune for Education 中添加 Take a Test 配置文件

Take a Test 应用可以安全地管理在线课堂的 Windows 10 设备上测试。  学生使用他们在登录到测试配置文件提供的凭据。 然后单击要启动测试的评估 URL。 
 
本文介绍如何：
* 创建 Take a Test 配置文件。
* 将该配置文件分配给在您的学校的学生。  

> [!NOTE]
> 为需要测试目的创建独占的用户。 将 Take a Test 配置文件为此用户分配，以便不会影响学生或教师设备。 了解如何在 Windows 10 教育版，用户分配[Take 测试上设置多台 Pc](https://technet.microsoft.com/edu/windows/take-a-test-multiple-pcs)一文。

## <a name="take-a-test-features"></a>测试功能
当一名学生启动测试时，他们的桌面锁定。 Take a Test 应用将打开新窗口中。 采用测试清除系统剪贴板，以便学生不能复制并粘贴的内容。

虽然测试处于活动状态，但是不能测试对象：

* 请访问其他网站。
* 打开或访问其他应用。
* 更改设置。
* 扩展显示。  
* 请参阅通知。
* 接收应用程序和操作系统更新。
* 收到文本建议。
* 使用 Cortana。
* 共享、 打印或记录设备屏幕上，除非学校或 IT 管理员允许的。

### <a name="how-is-assistive-technology-affected"></a>辅助技术如何影响？
某些设备功能-例如讲述人-和其他辅助技术仍然是完全正常运行时执行测试。 有关应用功能的列表，请参阅[需要测试应用程序技术参考](https://docs.microsoft.com/education/windows/take-a-test-app-technical)。


## <a name="take-a-test-profile-setup"></a>需要测试配置文件安装程序
设置 Intune for Education 中的配置文件。 在开始之前，我们建议您创建专用的用户帐户仅用于评估。 用户将登录到此帐户来访问测试。 

1. 从 Intune for Education 仪表板，单击**Take 测试配置文件**。    
![侧栏中的选项的列表](./media/dashboard-002-left-sidebar-list.png)  
2.  单击添加 Take a Test 配置文件。  
 ![在左上方选择添加需要测试配置文件按钮](./media/takeatest-001-new-profile.png)  
3. 输入测试的描述性名称。  
4 输入评估 URL。  
 ![需要测试配置文件窗口](./media/takeatest-002-new-profile-edit-window.png)  
5. 配置测试设置的其余部分：    
    a. 允许屏幕捕获  
    b. 需要安装一个打印机的 Pc  
    c. 允许文本建议   
6. 从现有用户的列表中选择一个帐户。 学生将使用该帐户的用户名和密码登录到相应的评估。  

若要查看的任何配置文件的详细信息，请从左侧和右侧的页上选择它。 然后单击**帐户**选项卡。  

## <a name="assign-or-change-groups"></a>分配或更改组
将需要访问测试的配置文件的学生组分配。 请按照这些步骤太组分配对进行编辑。
1. 从**Take 测试配置文件**页上，单击**组**选项卡。 
2. 单击**更改组分配**。 
3. 选择一个或多个组从**的所有组**菜单。 然后单击**添加组**。 
4. 若要从分配中删除一个组，请选择从组**分配的组**菜单。 然后单击**删除组**。
5. 单击**确定**提交所做的更改。

## <a name="delete-take-a-test-profile"></a>删除 Take a Test 配置文件  
删除 Take a Test 配置文件时，它将成为一个典型的用户帐户。 学生仍可以登录到帐户使用其现有的凭据，但从帐户中删除 URL 评估链接。 登录到的帐户将不再锁定的学生设备。

1. 从**Take 测试配置文件**页上，选择你想要删除的配置文件。
2. 单击**删除需要 a Test 配置文件**。
3. 单击**删除**来确认你的操作。

若要详细了解 Take 在你的设备上的测试，请参阅[Windows 10 中进行测试](https://technet.microsoft.com/edu/windows/take-tests-in-windows-10)。
