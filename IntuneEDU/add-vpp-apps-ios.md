---
title: 添加 VPP 购买的应用
titleSuffix: Intune for Education
description: 了解如何将购买的 VPP 应用添加到 Intune for Education。
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
ms.openlocfilehash: 69af75f14afb144bfed01919b1cba65d34a440f2
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146558"
---
# <a name="add-vpp-purchased-ios-apps-to-intune"></a>将 VPP 购买的 iOS 应用添加到 Intune

从 Intune for Education 门户添加 iOS Volume Purchase Program (VPP) 应用。 本文介绍如何管理已同步到 Microsoft Intune 的 VPP 购买的应用。

免费和付费应用是可用于通过 App Store 批量购买。 若要安装的免费 iOS 应用*而无需 VPP 令牌*，请参阅如何[在 Intune 中添加免费 iOS 应用](add-apps-ios.md)。  

## <a name="what-is-the-volume-purchase-program"></a>Volume Purchase Program 是什么？
Apple Volume Purchase Program 可让组织购买应用许可证中大容量，并通过其移动设备管理器 (MDM) 管理它们。 与 MDM，如 Intune for Education，可以管理许可证的大小，然后以无提示方式将其部署到学生设备无线。 在教室和多个设备需要同一应用程序的位置的组织中的 VPP/MDM 合作关系是理想选择。 

## <a name="before-you-begin"></a>在开始之前
若要查看和管理许可证从 Intune for Education 门户，你首先必须：  
* 配置[VPP 令牌](setup-ios-device-management.md)。
* 购买应用的 Apple VPP 供应商通过或通过 Apple School Manager > 应用商店应用和书籍。
* 现有的传输购买许可证分配给相应的 Intune VPP 令牌。 请参阅[Apple 教育支持站点](https://support.apple.com/education)若要了解如何传送许可证。 

## <a name="search-and-add-apps"></a>搜索并添加应用
完成以下步骤以搜索并添加付费的 iOS 应用从 Intune for Education 门户。 

免费的应用程序都可直接从门户购买。 但是，这些应用程序都可用，以便 VPP 帐户的情况下用户可以轻松地获取它们。 如果你打算将免费的应用程序以无提示方式和在卷部署到您的学校的设备，应通过 Apple VPP 或 Apple School Manager 网站进行购买。

1. 登录到 Intune for Education 门户。
2. 单击“应用”。
3. 从应用列表中下, **iOS 应用**，单击**新的应用程序**。
4. 从您打算在其中购买应用程序中选择国家/地区。
5. 键入应用程序的完整或部分名称。 Intune 从应用商店中返回相关结果的列表。 
6. 选择的应用。 
7. 一条消息出现，提示你完成购买通过 Apple School Manager。 单击链接以转到 Apple School Manager。
8. 按照完成购买的 Apple School Manager 中的步骤。 系统将提示您要将你的许可证分配到相应的位置。
9. 返回到 Intune for Education >**应用**。 您的应用程序将出现在**iOS 应用**列表。 如果没有立即看到它，等待几分钟并刷新页面。

### <a name="view-app-details"></a>查看应用详细信息
应用在应用程序列表中，在出现**iOS 应用**。 单击应用程序以查看其：

* **概述**：列出了应用程序名称、 发布者和日期添加到 Intune。 此外列出了可供分配的许可证数目。
* **组**：列出所有分配有该应用的组。 更改组分配给或转到特定组的详细信息页。
* **安装状态**:显示有关应用程序的安装，如已分配给设备的详细信息。 上次签入的时间和安装是否成功、 失败还是仍正在进行中，还列出了状态。

## <a name="reassign-vpp-purchased-licenses"></a>重新分配 VPP 购买的许可证
无法从 Intune for Education 删除 VPP 购买的应用。 但是，可以从已分配组中删除用户或从分配中删除整个组。  

