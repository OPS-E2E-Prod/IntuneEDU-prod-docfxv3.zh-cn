---
title: 续订 Apple MDM 证书
titleSuffix: Intune for Education
description: 了解如何续订过期的证书或 Intune for Education 门户中的令牌。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: a5989a02466183e4c891851598ffc885588c78fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146562"
---
# <a name="renew-ios-certificate-and-tokens"></a>续订 iOS 证书和令牌
Apple MDM Push 证书、 MDM server 令牌和 VPP 令牌过期后创建它们的 365 天。 Intune for Education 将向您发出警报时证书或令牌是接近或已过期。 

请确保续订以维护你的 Intune for Education 帐户和 Apple 帐户之间的连接。  

## <a name="renew-apple-mdm--certificate"></a>续订 Apple MDM 证书  
> [!IMPORTANT]
> 如果 Apple MDM 证书过期或被删除，你将需要重置并重新注册设备的新证书。  

MDM push certificate 是与用来创建它的 Apple ID 相关联。 续订证书与此相同的 Apple id。

1. 从 Intune for Education 仪表板，单击**租户设置** > **iOS 设备管理**。
2. 单击**MDM Push Certificate**选项卡。
3. 单击**续订证书**。
4. 按照上的说明**MDM Push Certificate**页。 你将需要访问 Apple 推送证书门户以续订 MDM push Certificate。 请记住，登录到 Apple Push Certificates 门户中使用用来创建原始证书的 Apple ID。
5. 当您在 Apple Push Certificates 门户时，请单击要续订即将过期的证书的选项。 
6. 完成在 Apple 门户中的步骤。 当证书的状态中读取**Active**再次单击以下载并将其保存。
7. 返回到 Intune for Education 门户，并输入用于登录到 Apple Push Certificates 门户的 Apple ID。
8. 上载你下载的证书。
9. 单击“保存” 。

## <a name="renew-mdm-server-token"></a>续订 MDM server 令牌

续订 MDM server 令牌每年一次以确保 Intune for Education 始终具有 iOS 设备的更新的列表。

MDM server 令牌是与用来将服务器添加的 Apple ID 相关联。 续订令牌与此相同的 Apple id。 

1. 从 Intune for Education 仪表板，单击**租户设置** > **iOS 设备管理**。
2. 单击**MDM Server 令牌**选项卡。
3. 选择你想要续订的令牌。
4. 单击**续订令牌**。
5. 按照上的说明**MDM Server 令牌**页。 你将需要访问 Apple School Manager 生成新 MDM Server 令牌。 请记住，登录到 Apple School Manager 与用来获取原始令牌的 Apple ID。
6. 下载并保存新的令牌从 Apple School Manager 后，返回到 Intune for Education 门户。 键入用来创建原始令牌的 Apple ID。
7. 上传已下载的令牌。
8. 单击“保存” 。


## <a name="renew-vpp-token"></a>续订 VPP 令牌
续订你的 VPP 令牌每年一次以确保你 VPP 购买的应用可以查看和分配 Intune for Education。  

VPP 令牌是与用来创建它的 Apple ID 相关联。 续订令牌与此相同的 Apple id。  

1. 上**iOS 设备管理**页上，单击**VPP 令牌**选项卡。
2. 选择你想要续订的令牌。
3. 下**VPP 令牌：Microsoft Intune**，单击**续订令牌**。
4. 按照上的说明**VPP 令牌**页。 你将需要访问 Apple School Manager，以获取新令牌。 请记住，用于获取原始令牌的 Apple ID 登录。
5. 按照 Apple School Manager 创建和下载的令牌中的步骤。 然后将令牌保存到您的计算机。
6. 返回到 Intune for Education 门户。 输入用于登录到 Apple School Manager 中的 Apple ID。
7. 单击文件夹图标，浏览计算机的文件。 选择你下载和前面保存的令牌文件。
8. 选择您的学校的设备的位置。
9. 如果不想要启用自动应用更新，切换设置来禁用它们。 
10. 单击“保存” 。

## <a name="next-steps"></a>后续步骤
现在，续订证书和令牌，请确保[组设置](edit-groups-intune-for-edu.md)处于最新状态。 若要查看你在 Intune 中的组的当前状态，了解如何[查看报表](what-are-reports.md)。  

读取[什么是 Intune for Education 中新](whats-new-in-edu.md)要了解有关最新的更新和功能。