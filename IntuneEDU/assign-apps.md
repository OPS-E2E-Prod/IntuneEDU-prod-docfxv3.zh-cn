---
title: 如何安装应用？
titleSuffix: Intune for Education
description: 了解如何使用 Intune for Education 管理的应用。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 635a5cc7-7dd4-45f9-9b18-3eddb76d0c74
searchScope:
- IntuneEDU
ms.openlocfilehash: 260679748d8ddb891d042abd6e0d7d0f5f698b34
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146512"
---
# <a name="installing-apps-on-school-devices"></a>在学校设备上安装应用

若要在学校设备上安装的应用，必须首先将其分配给一个组。 本文介绍三种方法可以将应用分配到学生教师。  

分配应用后，应用程序发送到相应的设备。 在设备签入到 Intune for Education 时启动应用程序安装。 

## <a name="add-apps-to-intune-for-education-inventory"></a>将应用添加到 Intune 教育版清单
默认情况下，受欢迎的应用是 Intune for Education 中可用于直接分配。 如果想要分配的应用不在你的清单，了解如何将其添加到 Intune for Education 与以下文章之一：
* [Microsoft Store for Education 的应用](acquire-store-apps.md)
* [免费 iOS App Store 应用](add-apps-ios.md)
* [iOS VPP 应用](add-vpp-apps-ios.md)
* [Windows 10 桌面应用程序](add-desktop-apps-edu.md)
* [Web 应用](add-web-apps-edu.md)  

## <a name="assign-apps-with-express-configuration"></a>分配应用快速配置
转到[快速配置](Express-configuration-intune-edu.md)将多个应用分配给单个组。 

1. 从 Intune for Education 仪表板，单击**快速配置**。  
2. 选择你想要将应用添加到的组。 然后单击“下一步” 。
3. 选择要部署到你的组的一个或多个应用。 然后单击“下一步” 。 
4. 应用将自动分配给你的组。 继续完成快速配置。

##  <a name="assign-apps-to-a-single-group"></a>将应用分配到一个组
选择一个组和一个或多个应用安装到该组中的设备。

1. 从 Intune for Education 仪表板，单击**组**。
2. 选择你想要部署到应用的组。
3. 转到在顶部的任务栏，单击**应用**若要查看可用的应用列表。  
4. 选择要部署到你的组的一个或多个应用。 
5. 选择**保存**将所选的应用部署到该组。 设备检查入到 Intune for Education 的下一个时间，将自动开始安装。  

## <a name="asign-apps-to-multiple-groups"></a>Asign 应用到多个组
选择一个应用并将其分配给一个或多个组进行安装。

1. 从 Intune for Education 仪表板，单击**应用**。
2. 从左侧上的应用列表中，选择想要分配的应用。
3. 转到在顶部的任务栏，单击**组** > **更改组分配**。 
4. 选择你想要分配到应用的组。  
