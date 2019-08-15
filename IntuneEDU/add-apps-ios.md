---
title: 从 iOS 应用商店添加免费的应用程序
titleSuffix: Intune for Education
description: 了解如何从 iOS 应用商店的免费应用程序添加到 Intune for Education。
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
ms.openlocfilehash: 4d17b0d12758dc781fa89f522f07ace5247cdc2e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62145894"
---
# <a name="add-free-ios-apps-to-intune-for-education"></a>向 Intune for Education 添加免费 iOS 应用  
搜索并将从 iOS 应用商店的免费应用添加到你的应用程序清单。 本文介绍如何购买免费 iOS 应用，以便可以查看并将其分配 Intune for Education 门户中。
 
说明仅适用于应用被列为**免费**应用商店中。 若要添加的付费应用，请参阅本文中，[添加 VPP 购买的 iOS 应用到 Intune](add-vpp-apps-ios.md)。

## <a name="recommendation-set-up-vpp-token"></a>建议：设置 VPP 令牌

不需要 VPP 令牌，以安装免费的应用程序，但我们建议使用它。 VPP 令牌允许您购买的所有应用-免费和付费-通过 VPP 应用商店。 Intune 以无提示方式安装 VPP 购买的应用在设备上，并且不需要 Apple ID 进行身份验证。  

如果您选择不使用 VPP 令牌购买您的应用程序，将只能够管理 Intune for Education 中的免费应用程序。 设备用户还需要使用安装分配应用到 Apple ID 登录。

## <a name="add-new-ios-app"></a>添加新的 iOS 应用
完成以下步骤以将 iOS 应用添加到 Intune for Education。
1. 登录到 Intune for Education 门户。
2. 单击“应用”。
3. 在左窗格中下, **IOS 应用**，单击**新的应用程序**。
5. 在搜索框中，键入应用的完整或部分名称。
6. 选择应用程序，然后单击**保存**将应用添加到 Intune 清单。

## <a name="view-app-details-in-intune-for-education"></a>Intune for Education 中查看应用详细信息
添加应用程序在应用程序列表中，在出现**iOS 应用商店**。 单击应用程序以查看其：

* **概述**：列出了应用程序名称、 发布者和日期添加到 Intune。 单击要查看在 iTunes 中的应用的应用名称。
* **组**：列出所有分配有该应用的组。 更改组分配给或转到特定组的详细信息页。
* **安装状态**:显示有关应用程序的安装，如已分配给设备的详细信息。 上次签入的时间和安装是否成功、 失败还是仍正在进行中，还列出了状态。  
