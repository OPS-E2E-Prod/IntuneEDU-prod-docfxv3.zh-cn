---
title: 注册 Windows 10 设备
titleSuffix: Intune for Education
description: 了解如何适用于教育的 Intune 设置 Windows 10 设备。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.openlocfilehash: 29d4b238fb906eac01f3ffe36dd252f8b657d046
ms.sourcegitcommit: 9c43411a2c210cf1d755c3120015c89611e33613
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/18/2019
ms.locfileid: "67213394"
---
# <a name="enroll-windows-10-devices"></a>注册 Windows 10 设备

设置 Intune 教育版设置为与你的信息后，如学生记录、 应用和设备的设置，将设备连接到 Intune for Education。 对于新的 Windows 10 设备，在初始设备安装过程中建立的连接。   

## <a name="when-to-use-set-up-school-pcs-vs-windows-autopilot"></a>何时使用设置学校 Pc 与 Windows Autopilot  
下表介绍何时使用学校电脑、 Windows Autopilot 和 / 或用于初始设备安装程序的设置。 使用**考虑的要点**列要考虑您自己的学校环境和安装程序需求。  

|考虑的要点| 设置学校电脑 |Windows Autopilot  |
|---------|---------|---------|  
|IT 人员 | IT 人员执行设备取消装箱，第一个开机，和设备配置的由 IT 人员执行。|针对从 IT 人员的有限 engagement 优化。 学生和教师可以执行设备取消装箱，第一个开机，和初始配置。|
|设备用户|  最适用于共享设备和面向年轻的学生。|最适用于 1 对 1 设备和面向较旧的学生。|
|应用     | 最适合部署在较慢的网络上同时大型应用程序。|适用于所有规模的应用。| 
|网络 | 必选项; 可靠 internet 连接最适合低带宽网络。| 必选项; 可靠 internet 连接基于的并发设备设置数量和大小所需应用的网络带宽消耗。 学生可以设置其家庭网络上的设备。|
|类的第一天|设备准备好进行登录，并立即使用。| 学生需要取消装箱并连接到网络;安装程序会自动完成。|
|部署时间|只需 1-2 分钟;时间基于数量的并发设备设置、 网络带宽和需要应用程序的大小增加。|只需 1-2 分钟;时间基于数量的并发设备设置、 网络带宽和需要应用程序的大小增加。|
|Oem/合作伙伴|不适用。  |需要 Windows Autopilot 服务由合作伙伴 (CSP) 或 OEM 提供程序注册的设备 Id。 |
|现有内部部署配置| 支持使用 Windows 配置设计器。 | 支持混合 AD 加入;设备必须在 Active Directory 域控制器所在的同一网络上。|  
### <a name="setting-up-devices-with-windows-autopilot"></a>设置与 Windows Autopilot 设备
 若要设置你的设备与[Autopilot](https://docs.microsoft.com/windows/deployment/windows-autopilot/windows-autopilot-requirements)，请转到[Intune](https://devicemanagement.microsoft.com) > **设备注册** > **Windows 注册**  > **设备**。   

### <a name="setting-up-devices-with-set-up-school-pcs-app"></a>设置设备使用 Set 学校电脑应用
将 Windows 设备添加到 Intune 通过学校电脑应用设置。 应用程序将指导完成如何配置并保存单个设备配置文件，可以将分发到多台计算机。 USB 驱动器用于保存并在设备安装过程配置文件下载到每个设备。 

有关应用程序的详细信息，请参阅[什么设置学校电脑？](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)一文。 

## <a name="setup-windows-devices"></a>设置 Windows 设备  
完成以下步骤以将 Windows 10 设备添加到 Intune for Education。 在安装期间，设备必须具有 Internet 访问权限。 

1. 在新的 Windows 10 设备上的电源。 
2. 在新的或重置设备上，读取第一个安装程序屏幕，**让启动与区域。这是吧？** 选择您的 Pc 的位置的区域。 然后选择**是**。  

   ![示例中的 Windows 10 OOBE 开始设置屏幕的屏幕截图。 美国突出显示为所选区域](./media/RS5_Choose_Region.png)  

3. 选择键盘布局。 此步骤配置屏幕上的键盘，以匹配您键盘上的物理布局。 它还可以配置语言和键盘字符。 选择**是**以继续。  

      ![示例屏幕截图的键盘布局屏幕中，使用美国突出显示为所选的布局。](./media/RS5_Choose_Keyboard.png)  

4. 如果你想要添加其他键盘布局，选择**添加布局**。 否则，请选择**跳过**。   

     ![示例的第二个键盘布局屏幕，通过添加布局并跳到右下角中的选项的屏幕截图。](./media/RS5_Second_keyboard.png)  

5. 选择**设置为工作或学校帐户**。 然后选择**下一步**。  

     ![示例屏幕截图中的 * * 你希望如何设置？ * * 屏幕上，突出到集的选项会显示为工作或学校帐户。](./media/RS5_Choose_Setup_Type.png)  

6. 键入电子邮件地址与您的学校管理员或注册管理器帐户相关联。 然后选择**下一步**。  

     ![示例屏幕截图中的 * * 登录 Microsoft * * 屏幕上，使用 Microsoft 徽标和电子邮件字段为空。](./media/RS5_Sign_In.png)  

7. 输入帐户的密码。 然后选择**下一步**。  

     ![示例屏幕截图中的 * * 输入密码 * * 屏幕，使用组织的徽标和空密码字段。](./media/RS5_Enter_Password.png)  



8. 选择设备的隐私设置。 配置这些设置，根据您的学校的策略。 某些设置，如**语音识别**并**位置**默认开启。  

     ![默认情况下打开示例屏幕截图中列出的隐私设置选项，与某些设置。](./media/RS5_Choose_Settings.png)  


9. 选择**接受**以完成设备设置。 可能需要几分钟才能完成安装，请尽情以开始另一台设备上的安装程序。  

## <a name="next-steps"></a>后续步骤
现在，设备学校用于设置并准备就绪后，了解如何更新、 监视和解决这些问题。   
* 将分配[组管理员](group-admin-delegate.md)可帮助您管理您的学校内或跨地区的教室设置
* 查看所有[Windows 设置](all-edu-settings-windows.md)，可以调整
* 了解如何[设置继承](settings-inheritance.md)影响新组
* 审阅[报表](what-are-reports.md)地找出并对错误进行故障排除  

 
