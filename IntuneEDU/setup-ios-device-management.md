---
title: 设置 iOS 设备管理
titleSuffix: Intune for Education
description: 启用 iOS 设备管理同步并从 Intune for Education 门户管理 iOS 设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/09/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 7f581e8dcfc870c8b5b9994dab3b2f7a9a9428dc
ms.sourcegitcommit: fe8359eaaf216ca4938332fa7ef91d200ea72f7c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/08/2019
ms.locfileid: "67622844"
---
# <a name="setup-ios-device-management"></a>设置 iOS 设备管理 

可以管理或分配给学生和教师的 iOS 设备之前，必须设置 Intune for Education 中的 iOS 设备管理。 此安装程序需要在添加 MDM Push Certificate 和配置至少一个 MDM Server 令牌 （也称为一个 DEP 令牌）。  

  ![租户设置、 iOS 设备管理页面，显示令牌，MDM Push Certificate，MDM 服务器上的绿色圆圈，白色复选标记和 VPP 令牌卡的屏幕截图。 圆圈表示配置了所有。 用户可以单击显示"管理"可以编辑或更新配置的蓝色矩形按钮。](./media/set-up-ios-management-landing-1807.png)   

安装过程中，您将使用你的 Apple School Manager 帐户连接你的 Intune for Education 帐户。 连接可确保 Intune for Education 始终提供有关已购买的 iOS 设备的最新详细信息。

本文介绍如何：

* 添加 Apple MDM Push certificate。
* 配置和同步 Apple MDM Server 令牌。
* 配置一个 Apple VPP 令牌。

## <a name="what-happens-after-i-set-up-device-management"></a>我设置了设备管理后，会发生什么情况？
已设置了 iOS 设备管理后，你可以使用 Intune for Education 管理的应用和 iOS 设备上的设置。 此外将有权的报告和操作，因此可以解决冲突任意位置。  

学生和教师在您的学校中将能够安全地访问学校网站和电子邮件。  

## <a name="requirements"></a>要求
在开始之前，请确保你有：  
* Internet 连接。
* Apple School Manager 帐户凭据。
* Intune for Education 设备许可证。 详细了解中的设备许可证[Intune 许可证 docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)。  

> [!IMPORTANT]
> Intune 教育版只支持 iOS 设备注册的设备购买通过 Apple dep。 Apple School Manager 有关的详细信息，请参阅[Apple 教育支持站点](https://support.apple.com/education)。  

## <a name="add-an-mdm-push-certificate"></a>添加 MDM Push certificate
Apple MDM Push certificate 设置了你的 Intune 和 Apple School Manager 帐户之间建立安全连接。 连接后，Intune 可以不断同步和管理你的 Apple 设备和应用。 

1. 登录到 Intune for Education 门户。
2. 转到侧栏，然后单击**租户设置** > **iOS 设备管理**。
3. 单击**MDM Push Certificate**选项卡。
4. 按照上的说明**MDM Push Certificate**页。 你将需要访问 Apple 推送证书门户来创建 MDM push certificate。 登录到您的学校的 Apple ID，一个不在个人的 Apple Push Certificates 门户。
5. 完成在 Apple 门户中的步骤。 创建证书后，单击要下载并保存它。
6. 返回到 Intune for Education 门户，并输入用于登录到 Apple Push Certificates 门户的 Apple ID。
7. 上载你下载的证书。
8. 单击“保存”  。  

推送证书到期每个 365 天。 Intune for Education 连接到 Apple School Manager 帐户，因此所需的证书[都需要每年续订](renew-ios-certificate-token.md)。  


## <a name="configure-mdm-server-token"></a>配置 MDM server 令牌  
有时称为 DEP 令牌，MDM server 令牌，可以从 Apple School Manager 的 Intune 同步设备详细信息。 这些详细信息告知它需要管理的设备的 Intune，并填充 Intune for Education 门户中的应用清单。  

### <a name="shared-ipad-configuration"></a>共享的 iPad 配置  
可以配置你的 iOS 设备注册为共享 iPad 设备。 使用共享 iPad 的学生和教师登录到您的学校设备其唯一的托管 Apple id。 随着对象移动设备的应用和数据随之一起移动。 一名学生可以使用一台设备开始编写一篇，并登录到不同设备更高版本来完成本文。 若要详细了解*共享 iPad*并*托管 Apple Id*，请访问[Apple 教育网站](https://www.apple.com/education/it/)并[文档](https://go.microsoft.com/fwlink/?linkid=2060097&clcid=0x409)。  

课堂设备仍在之间，即使没有共享 iPad 的学生共享。 但是，用户数据不会移动设备之间。 配置你的服务器令牌之前，将选择你想要启用共享 iPad。 

### <a name="server-token-setup"></a>Server 令牌安装程序  

以下步骤介绍如何配置你的 MDM Server 令牌。 

1. 转到**租户设置** > **iOS 设备管理**，然后选择**MDM Server 令牌**选项卡。
2. 选择**设置令牌**。
3. 选择你想要注册的设备与新的服务器令牌相关联。  
    * 若要配置共享 iPad 此令牌，请选择**用户将登录到其托管 Apple Id 的设备**。 所有设备分配给此令牌都将会设置，以便用户必须登录到其托管 Apple id。  
        > [!IMPORTANT]
        > 在创建服务器令牌后，不能更改所选。 该时间点，如果你想要更改设备的注册方式后，你将需要创建新的服务器令牌。  

        > [!NOTE]
        > 如果设置了与共享 iPad 设备时，将获取所有附带共享 iPad，除外的课堂和美术应用的功能。 这些应用程序不受 Intune for Education。 设置 MDM server 令牌后，所有其他共享 iPad 功能将可供您。  

    * 如果您的学校未使用托管 Apple Id，请选择**任何人都可以取消锁定这些设备...** 设备仍可共享的学生&ndash;他们将只需直接访问，而无需登录。 如果你设置一个，它们可能需要设备密码。  

4. 选择**下载**用于下载所需的 Intune 公钥。 你将需要上载此文件中 Apple School Manager 创建 MDM server 令牌。 将文件保存到您的计算机。
5. 选择**转到我在 Apple School Manager 中的 MDM 服务器**。 如果系统提示，请登录到 Apple School Manager 与您的学校的 Apple ID，不是你个人的一个。
6. 在屏幕创建 MDM 服务器中执行的步骤。 然后保存所做的更改。 如果没有要完成此步骤的信息，请与您的学校的 Intune 管理员联系。
7. 下载并保存 MDM 服务器的令牌。
8. 保留在 Apple School Manager 中并转到**设备分配**。 对于每个设备，整个设备购买或以 CSV 文件中的设备的列表的顺序号输入的序列号。  

  ![Apple School Manager 网站，设备分配页的屏幕截图。 显示步骤 1 中，使用单选按钮选择的"选择设备"和用户输入他们想要手动输入购买的设备的空字段框。 显示步骤 2，"选择操作"下拉列表菜单与其中用户应选择"将分配到服务器"。](./media/Apple-School-Manager-MDM-Server-token-1807.png)   

9. 从下拉列表菜单中选择**将分配给服务器**。 然后选择刚才创建的 MDM 服务器。
10. 返回到 Intune for Education 门户，并输入用于登录到 Apple School Manager 中的 Apple ID。
11. 上传已下载的 MDM server 令牌。
12. 单击“保存”  。

MDM server 令牌会过期每个 365 天。 若要查看和管理为教育版门户中 Intune 的设备，需要使用令牌。 你将需要[每年续订](renew-ios-certificate-token.md)。

### <a name="device-enrollment-profile"></a>设备注册配置文件
Intune for Education 创建并配置每个 MDM server 令牌应用 iOS 注册配置文件。

所有 iOS 设备添加到 Intune 教育版都设置为受监督模式。 作为管理员，受监督的模式允许您更好地控制您的学校的设备。 例如，您可以将推送新的应用或应用更新以无提示方式到设备。 仅限监督的设备设置的完整列表，请参阅文章[配置需要监督](/intune/device-restrictions-ios#settings-that-require-supervised-mode)。

Intune for Education 适用于通过 MDM server 令牌注册的设备命名方案。 名称将有助于您确定和组的单独设备。 默认情况下，设备是名为其设备序列号。 设置你的 MDM server 令牌时，还可以添加自定义设备名称。  

有关注册配置文件的详细信息，查看[配置设置的列表](add-devices-ios-edu.md#preconfigured-settings)在注册过程。  

### <a name="sync-managed-devices"></a>同步托管设备
现在，Intune for Education 有权管理的 iOS 设备，以查看你管理的设备列表同步。  
1. 登录到 Intune for Education。
2. 单击**租户设置** > **iOS 设备管理** > **DEP 令牌**。
3. 单击任何列出的令牌。
4. 单击**同步设备列表**。 

显示在列表中的设备已经可供注册。 启动它们以开始注册过程。

## <a name="configure-vpp-tokens"></a>配置 VPP 令牌

 VPP 令牌链接到你的 Apple VPP 或 Apple School Manager 帐户的你的 Intune for Education 帐户。 可以创建单个的 VPP 令牌，以在整个组织; 管理应用也可以创建多个 VPP 令牌以分散到不同的位置或管理员管理。  

VPP 令牌所需的 Intune 添加到：  
* Intune for Education 门户中同步应用详细信息。
* 将 VPP 购买的应用分配到组。
* 以无提示方式安装 VPP 购买的应用，学校在设备上，而无需设备用户的 Apple id。

而无需 VPP 令牌，仍可以搜索并获取[免费 iOS 应用通过 App Store](add-apps-ios.md)。 但是，若要在设备上安装应用，设备用户必须使用登录 Apple id。 

1. 上**iOS 设备管理**页上，单击**VPP 令牌**选项卡。
2. 单击**打开 Apple School Manager**并使用您的学校的 Apple ID，一个不在个人登录。
3. 按照 Apple School 管理来创建和下载的令牌中的步骤。 将令牌保存到本地驱动器。
4. 返回到 Intune for Education 门户。 输入用于登录到 Apple School Manager 中的 Apple ID。
5. 单击文件夹图标，浏览计算机的文件。 选择你下载和前面保存的令牌文件。
6. 选择您的学校的设备的位置。
7. 如果不想要启用自动应用更新，切换设置来禁用它们。 
8. 单击“保存”  。

令牌过期每个 365 天。 管理 VPP 购买的应用，因此所需的令牌[都需要每年续订](renew-ios-certificate-token.md)。

### <a name="whats-a-managed-device"></a>什么是托管的设备？
为了帮助您了解托管和非托管设备之间的区别，我们看一下下面的方案。

教师为学校带来了个人的 iOS 设备。 在学校时间，教师使用设备，若要安排父会议和跟踪的类分配。  

 设备不被购买通过 Apple DEP 计划学校。 未在 Intune for Education 租户下注册。 因此，没有 Intune 与教师的设备进行通信的方法。 设备被视为不托管-IT 管理员已在教师如何使用设备在学校时间内无法控制。 

同样，因为它不是已知的托管设备，教师将无法访问受保护的学校资源，例如电子邮件。  

## <a name="next-steps"></a>后续步骤

采购[免费从应用商店应用](add-apps-ios.md)，或[添加 VPP 购买应用](add-vpp-apps-ios.md)到 Intune for Education 门户。  

