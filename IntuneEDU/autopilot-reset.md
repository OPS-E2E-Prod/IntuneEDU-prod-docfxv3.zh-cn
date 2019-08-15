---
title: 使用 Autopilot Reset 重新配置设备与 Intune for Education
titleSuffix: Intune for Education
description: 了解如何在 Intune for Education 中 Autopilot 重置。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/17/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: ''
searchScope:
- IntuneEDU
ms.openlocfilehash: 23430e2902eeb5673f1915b1a9e547bdde1e17dd
ms.sourcegitcommit: 05576d32cac5cc3998ea579404ce84a2813c9083
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/09/2019
ms.locfileid: "68866721"
---
# <a name="autopilot-reset"></a>Autopilot 重置
你可以使用 Autopilot Reset 从设备中删除个人文件、应用和设置。 设备在 Intune 中保持注册状态, 并返回到完全配置或已知 IT 批准状态。
可以通过 Intune for Education 门户 Autopilot 本地或远程重置设备。  

使用 Intune for Education 门户, 无需 IT 人员访问每台设备即可启动该过程。 从门户中, 你可以重置单个设备, 或对组中的所有设备执行批量重置。 通过重置组中的所有设备, 你可以快速擦除和重新配置学生设备, 以便为新的学年做好准备。  

重置后, 原始设置会应用到设备, 然后与 Intune 同步以获取最新的策略。 如果设备使用 Autopilot 重置，设备的主要用户将会遭删除。 在重置后登录的下一个用户将被设置为主要用户。   

## <a name="requirements"></a>要求
使用 Autopilot Reset 仅适用于运行 Windows 10 1709 版或更高版本的设备。
仅适用于运行 Windows 10 版本17672或更高版本的设备进行远程使用 Autopilot 重置。

## <a name="use-autopilot-reset-locally"></a>在本地使用 Autopilot 重置
如果需要擦除单个设备, 可以直接在设备上执行此操作。 在设备上, 按 CTRL + WIN + R。 按 Ctrl + WIN + R 后, 你必须使用管理员凭据进行身份验证, 以便触发重置。

## <a name="use-autopilot-reset-remotely-for-a-single-device"></a>对单个设备使用远程重置 Autopilot
1. 在 Intune for Education 中, 选择 "**组**" > 选择设备组。
2. 选择 > Autopilot "**重置**的设备。 若要确认重置, 请再次选择 " **Autopilot 重置**"。
2.  启动重置时, 将显示一条消息。 设备会在下次连接到 Internet 时重置。  

## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a>大容量地使用设备的 Autopilot 远程重置  
1.  在 Intune for Education 中, 选择 "**组**" > 选择组。
2. 选择**Autopilot "重置所有设备**"。
2. 在 " **Autopilot 重置组**" 框中, 键入当前组的名称。 然后选择 " **Autopilot Reset** " 进行确认。
3.  每个设备将在下一次连接到 Internet 时进行重置。 如果任何设备不支持远程 Autopilot 重置, 你将看到名为 "**设备无法重置**" 的表。 该表列出了每个设备以及无法重置的原因。  

## <a name="next-steps"></a>后续步骤
[通过远程操作管理设备](edu-device-remote-actions.md)



