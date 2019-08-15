---
title: 快速配置
titleSuffix: Intune for Education
description: 使用 Express 配置来设置你 Intune for Education 中的组。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.openlocfilehash: eb3b697973d37d5b4697559b3ba87b64ba9afdb3
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147276"
---
# <a name="express-configuration-in-intune-for-education"></a>快速配置 Intune for Education 中

  ![快速配置磁贴，这表示"启动快速配置，单击此处选择的应用和组的设置。"](./media/express-config-001-launch-tile.png)

快速配置，可将设置和应用分配给用户和设备。 在首页上找到有关分步演练的启动磁贴[Intune for Education 门户](https://intuneeducation.portal.azure.com)。 

当您单击通过每个步骤，您将看到已配置的大多数 Windows 或 iOS 设置。 这些配置是默认值，并根据建议设置。 推荐的特定于操作系统的应用还预先选定状态。 根据需要为你的学校，请更改默认选择。 

每当用户想要对组的设置或应用程序进行更改，则返回到快速配置。 

## <a name="launch-express-configuration"></a>启动快速配置
本部分介绍如何完成快速配置中的步骤。 若要充分利用快速配置，请确保已同步学校数据，或在 Azure AD 中创建组。 

1. 登录到 Intune for Education 门户。
2. 在仪表板中，单击**启动快速配置**。  

如果当你启动快速配置已禁用 iOS 配置：  
1. 从仪表板中，选择**查看所有** > **iOS 设备管理**。
2. 上传 Apple MDM Push certificate。
3. 注册[Apple MDM Server 令牌](setup-ios-device-management.md)。

## <a name="choose-a-group-to-configure"></a>选择要配置的组

创建和使用你的 Intune for Education 订阅包含一些组。 Intune for Education 填充学校记录中的详细信息组。 这些组是：  

 * 所有设备  
 * 所有用户  
 
如果使用学校数据同步 (SDS) 将您的学校记录导入，还可以看到：  

 * 所有教师  
 * 所有学生  

Intune for Education 建议您开始**所有用户**组。 将所有用户必须都具有这些设置。 例如，密码要求和弹出限制可能都是相同的所有用户。

  ![选择组屏幕，要求用户选择一个组。](./media/express-config-004-choose-group.png)

单击展开/折叠箭头以查看或隐藏所有组。 请记住，当你配置的顶级组及其子组继承其所有设置。

## <a name="choose-apps"></a>选择应用

可以将以下应用类型添加到设备：
* [Web 应用](add-web-apps-edu.md)
* Windows 10 应用
    * [Microsoft Office](install-office.md)
    * [Microsoft Store for Education 的应用](acquire-store-apps.md)
    * [桌面应用](add-desktop-apps-edu.md)
* iOS 应用
    * [免费 iOS App Store 应用](add-apps-ios.md)
    * [批量购买计划 (VPP) 应用](add-vpp-apps-ios.md)

选择要分配的一个或多个应用。 应用程序将立即分配给你的组在单击后**下一步**。

  ![应用程序分配屏幕中。 应用程序被按分配不同的类型，包括 web 应用和 Microsoft Store for Education 的应用。](./media/express-config-005-choose-apps.png)

此外显示 Intune for Education[常用应用程序从 Microsoft Store for Education](add-popular-apps-edu.md)从跨所有 Intune 教育版用户。


## <a name="choose-settings"></a>选择设置
快速配置显示在 Intune 中设备和用户的常见设置。 设置可分为特定于操作系统的类别：Windows 设置和 iOS 设置。

使用建议的值是预设的默认设置。 如果你想要坚持使用建议，并不进行任何更改，请单击**下一步**。 设置将立即应用于组中。 

  ![选择设置屏幕中。 设置已组织成的折叠列表，包括部门等设备共享、 基本的设备设置、 应用设置、 浏览器设置的详细信息。](./media/express-config-006-choose-settings.png)


更改快速配置选项在任何时间以适合您的学校不断变化的策略。 有关更多自定义 Intune for Education 中，查看的完整列表[Windows 10](all-edu-settings-windows.md)并[iOS](all-edu-settings-ios.md)设备设置。

## <a name="review-settings"></a>查看设置

在保存前，查看你的应用和设置选项。 单击**回**进行更改。 评审完成后，单击**保存**。

 ![查看你选择的屏幕。 它显示应用程序以及在快速配置过程中选择的设置。](./media/express-config-007-save-changes.png)  

  ![在完成屏幕中。 它显示的"配置更多的组"按钮和已完成的选项。 已完成的所有选项提供都了简单介绍什么是过程，包括添加到 Intune for Education 的设备，通过将其联接到 Azure Active Directory 中的下一步。](./media/express-config-008-all-done.png)

## <a name="next-steps"></a>后续步骤
[分配组管理员](group-admin-delegate.md)可帮助您管理刚刚创建的组。 通过再探快速配置来随时编辑你的组。 若要查看更多设置，[访问的组选项卡](create-groups.md)。

