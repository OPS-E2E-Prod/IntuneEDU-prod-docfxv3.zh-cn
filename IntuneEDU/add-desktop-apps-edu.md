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
# <a name="add-desktop-apps-in-intune-for-education"></a>Intune for Education 中添加桌面应用程序

上传并将桌面应用程序添加到你的 Intune for Education 清单。 添加应用后，你可以[将其分配给组](install-apps.md)和 Windows 10 设备上安装它们。  

若要完成这些步骤，将你想要添加的应用需要的安装文件。  

1. 登录到 Intune for Education 门户。
2. 单击“应用”。
3. 在左窗格中下,**桌面应用**，单击**新的应用程序**。
4. 在中**新的桌面应用程序**部分中，输入以下详细信息：
   * **应用文件**-上传应用程序的 MSI 安装程序。
   * **应用名称**-应用在设备上显示的名称。
   * **说明**— 说明的应用程序可以帮助您快速识别它。
   * **发布服务器**— 名称应用发布者，可帮助你快速标识应用程序开发人员。
   * **图标**-上载 PNG 或 JPG 文件，以用作应用程序的图标。
5. 单击文件夹图标并选择应用安装文件从您的计算机。 
6. 单击“保存” 。 然后，应用将上载到 Intune for Education。 上传完成后，你可以[将应用分配给设备](install-apps.md)。 

   ![添加新的桌面应用程序屏幕，示例应用程序，evernote 填写所有字段。](./media/apps-004-filled-out-desktop-app.png)  

> [!NOTE]
> 如果遇到错误，"应用程序没有安装文件"或"任何应用程序安装文件已添加"，该文件未正确上传。 若要解决此问题，请尝试上传和重新保存该文件。
