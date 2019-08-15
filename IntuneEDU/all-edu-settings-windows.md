---
title: 所有 Windows 10 的设备设置
titleSuffix: Intune for Education
description: 请参阅 Intune for Education 中的所有 Windows 10 设备设置的列表
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/10/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: 63705b1370379efe03b70876b6313a906a57719e
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146799"
---
# <a name="windows-10-device-settings-in-intune-for-education"></a>Intune for Education 中的 Windows 10 设备设置

本文列出并描述 Intune for Education 中的所有 Windows 设备设置。 若要查看和编辑这些设置在门户中的，单击**组** > **设置** > **Windows 设备设置**。  


  ![所有设备，Intune for Education 中的组页面的屏幕截图。 突出显示设置选项卡，并显示 Windows 设备设置类别已展开，显示所有 10 个的子类别的设置。 每个设置处于折叠状态。](./media/edu-windows-device-settings-1812.png)   

## <a name="apply-settings"></a>应用设置  
将应用[组设置](what-are-groups.md)建立在您的学校的设备上的访问权限和安全边界。 可以在您的学校; 中的所有组中分配相同的设置或者，可以自定义课堂体验并将设置应用于单独的组。  

## <a name="configuration-options"></a>配置选项  
Intune for Education 中的许多设置配置为**块**或**允许**。 对于某些设置，**未配置**是一个选项。 切换到时**未配置**，设备将：  
* 使用默认设置。 
* 允许设备用户 （学生或教师） 自定义从自己的设备的设置。    

> [!NOTE]
> 用户、 应用和设备的设置不同于[租户设置](edu-tenant-general-settings.md)。 租户设置解决你的组织的订阅和管理设置。

## <a name="accounts-and-sign-in"></a>帐户和登录  
配置用户登录到学校设备的方式。

|设置|其作用|
|---|---|
|阻止添加和使用个人 Microsoft 帐户登录|阻止用户使用其 Microsoft 帐户登录。|
|阻止添加和使用非 Microsoft 帐户登录|阻止用户添加其 Microsoft 帐户以外的任何帐户。 如果你想要强制用户只能使用其 Microsoft 帐户电子邮件，请使用此设置。| 
|配置首选的 Azure Active Directory 租户域|使用户能够登录到 Windows 而无需键入的域名。 如果配置此设置，租户域名将预填充，但仍可编辑。|  

## <a name="apps"></a>应用  
配置设置，如用户如何安装和访问其设备上的应用。  

|设置|其作用|
|---|---|
|删除内置的 Windows 10 应用|卸载某些内置 Windows 应用程序。 了解这些应用是什么[如下](all-edu-settings-windows.md#remove-built-in-apps)。| 
|阻止访问管理应用|打开需要管理权限的应用程序块学生。|
|从 Microsoft Store for Education 安装应用程序块|阻止用户从未经授权的位置安装应用。|
|需要 Microsoft Store for Education 的应用从专用应用商店安装|只允许用户安装来自你的组织已设置的教育版 Microsoft Store 应用。|
|受信任的应用|允许或阻止用户安装受信任的应用来自 Microsoft 的证书进行签名。|
|不受信任的应用程序|允许或阻止用户安装应用程序且未签名，或由源不受信任由 Microsoft 签名的证书。|
|教育版 Microsoft Store 以外位置安装应用程序块|阻止用户从其他源和应用商店安装应用。
|块的 Microsoft Store for Education 的应用的自动更新|阻止 Microsoft Store for Education 的应用中自动更新。|
|使共享的设备上的学生可以共享应用程序数据|使学生在同一设备上使用相同的应用共享数据。|  


## <a name="enrollment-controls"></a>注册控件  
配置为教育设备注册到 Intune 相关的设置。

|设置|其作用|
|---|---|
|阻止手动取消注册|阻止用户手动取消注册设备管理。|
|启用 Autopilot 重置| 使用户具有管理权限以触发重置 Autopilot 设备锁定屏幕上按 CTRL + Win + R。 Autopilot 重置将移除所有用户数据&ndash;包括用户已安装的应用和个人设置&ndash;并保持在 Intune 中注册设备。 因此，设备保持最新的最新的应用、 策略和设置所有。|
|阻止添加预配包|阻止用户添加新的预配有设备设置的包。|
|阻止删除预配包|阻止用户删除具有设备设置的预配包。|  


## <a name="microsoft-edge"></a>Microsoft Edge  
配置影响 Microsoft Edge 浏览器体验和用户数据的设置。

### <a name="browser-experience"></a>浏览器体验  
|设置|其作用|
|---|---|
|配置主页|选择每次有人开始一个新的 Microsoft Edge 浏览器会话，此时会打开哪些页。|
|配置新选项卡页|选择每次有人在 Microsoft Edge 中打开新选项卡，此时会打开哪些页。|
|配置主页按钮行为|选择当用户单击 Microsoft Edge 中的主页按钮时，会显示哪些页。 此外可以隐藏的主页按钮。|
|阻止编辑收藏夹|阻止用户添加、 导入、 排序或编辑收藏夹列表。|
|阻止地址栏建议|从建议可能阻止 Microsoft Edge 的搜索词或以前访问过网站，如键入 URL 或搜索词。|
|阻止搜索建议|阻止 Microsoft Edge 中键入 URL 或搜索词建议可能的网站。|
|阻止 InPrivate 浏览|阻止用户从使用 InPrivate 浏览阻止 Microsoft Edge 保存数据，如浏览历史记录和 cookie。| 
|阻止浏览器扩展|阻止用户使用扩展来使用 Microsoft 和其他资源的附加功能进行自定义 Microsoft Edge。|
|阻止不受信任的浏览器扩展|阻止用户旁加载扩展到其 Microsoft Edge 浏览器。 这些扩展安装来自不可信源&ndash;不 Microsoft Store&ndash;和可能是恶意软件。|
|阻止 Microsoft Edge 中的打印|阻止用户打印浏览器的内容。|
|块首次运行页面|阻止用户看到首次运行页面。 当用户打开 Microsoft Edge 进行第一次并在浏览器更新后，将显示 Microsoft Edge 首次运行页。|
|阻止的弹出窗口|阻止打开新窗口的网站。|
|阻止重写安全警告|阻止用户在显示 SSL/TLS 证书错误的站点上单击"转到网页"。|
|阻止密码管理器|阻止用户使用密码管理器来保存密码。|
|阻止自动填充表单条目|保存在窗体字段中输入的数据块。|
|阻止访问 about: flags 页面|阻止访问关于： 标志页，其中包含的实验性设置和功能。|
|需要在 Internet Explorer 中查看 intranet 站点|如果设置为**块**，内部流量发送到 Microsoft 边缘，而不是 Internet Explorer。|
|阻止预启动|Microsoft Edge 预启动将打开 Microsoft Edge 作为后台进程在 Windows 启动过程。 此操作可帮助 Microsoft Edge 的性能并最小化启动它所需的时间量。 但是，作为后台进程可能会使设备显示为运行 Microsoft Edge*不符合*安全评估中。| 
|默认搜索引擎|选择必应、 Yahoo 或 Google 适用于 Microsoft Edge 为默认搜索引擎。|  

### <a name="user-data"></a>用户数据  
|设置|其作用|
|---|---|
|阻止开发人员工具|阻止用户访问开发人员工具。 Microsoft Edge 开发人员工具使用户能够生成和调试网页|
|同步 Microsoft Edge 的收藏夹与 Internet 资源管理器|同步从 Microsoft Edge 到 Internet Explorer 的所有收藏。| 
|在退出时清除浏览数据|关闭 Microsoft Edge 后自动清除历史记录、 cookie 和缓存的文件。|
|使用 Cookie|Cookie 可以存储网站设置，或跟踪用户的浏览行为。|


## <a name="network-and-connectivity"></a>网络和连接   
配置网络和连接设置：    
* Bluetooth  
* Internet 连接限制  
* Proxy (代理)  
* Wi-Fi 配置文件  

### <a name="bluetooth"></a>Bluetooth  
|设置|其作用|
|---|---|
|阻止蓝牙|阻止设备使用蓝牙。|
|阻止蓝牙可发现性|阻止设备被设置为可发现使用蓝牙。|
|通过蓝牙接收广告的块|阻止设备通过蓝牙接收营销消息和播发。|  
|阻止蓝牙 Swift 对通知|阻止用户获取有关蓝牙设备配对的通知。 Swift 对可以让用户知道蓝牙设备时附近，并且能够连接到 Windows 10。|  

### <a name="internet-connectivity-restrictions"></a>Internet 连接限制  
|设置|其作用|
|---|---|
|阻止 Internet 连接共享|阻止用户使用 Internet 连接共享，以便与其他设备共享设备的 Internet 连接。|
|阻止使用 Wi-fi 感知自动连接到开放热点|选择你想要阻止设备自动连接到 Wi-fi 热点。|
|阻止漫游时的移动电话网络数据|设备漫游时阻止使用手机网络数据。|  

### <a name="proxy"></a>Proxy (代理)  
|设置|其作用|
|---|---|
|块自动检测代理设置|如果设置了代理服务器来处理设备的网络流量，可以选择是否设备自动检测代理设置连接时。|
|使用代理脚本|启用适用于你设备的代理脚本使用。 如果您**允许**此设置，你需要提供**设置脚本地址**。|
|使用手动代理服务器配置|如果设置了手动代理，可以定义此处为其设置。 如果您**允许**此设置，你需要提供**代理服务器地址**，**端口**，**代理异常**，以及是否**使用代理服务器进行本地 (intranet) 连接**。|  

### <a name="wi-fi-profiles"></a>Wi-Fi 配置文件  

|设置|其作用|
|---|---|
|选择要将其分配给此组的 Windows Wi-fi 配置文件。|已创建的 Wi-fi 配置文件的列表出现在本部分中，并准备好分配。 可见的详细信息，包括**配置文件名称**，**网络名称 (SSID)**，**安全类型**，以及**说明**。 

> [!NOTE]
> 配置 WPA 2 企业 Wi-fi 网络使用[完整的 Intune 中的 Wi-fi 配置文件管理体验](https://docs.microsoft.com//intune/wi-fi-settings-import-windows-8-1)。 此外可以使用 Intune 设置[SCEP](https://docs.microsoft.com/intune/certificates-scep-configure)并[PKI](https://docs.microsoft.com/intune/certficates-pfx-configure)集成。   

## <a name="printer"></a>打印机   
配置设置，以允许打印机学校的设备访问。    

|设置|其作用|
|---|---|
|打印机列表|创建你想要提供给学生设备的打印机的列表。 输入打印机主机名。 带格式的主机名的一个示例是*printer1.contososd.edu*。| 
|指定默认打印机|使打印机可用作设备上的默认打印机选项。 输入打印机的主机名显示在你**打印机列表**。|  
|阻止添加新的打印机|阻止从新的打印机连接到他们的设备组。|  


## <a name="security"></a>安全性  
配置 Windows Defender 和 Windows SmartScreen 的安全设置。  

### <a name="windows-defender"></a>Windows Defender  
> [!NOTE]
> 仅在提供了某些 Windows Defender 设置[租户](edu-tenant-general-settings.md)级别并不会显示在门户中。  

|设置|其作用|
|---|---|
|阻止用户访问 Windows Defender 设置|阻止用户修改设备上的 Windows Defender 设置。|
|启用实时监视|启用始终运行的扫描恶意软件、 间谍软件和其他威胁的侵害。|
|启用行为监视|启用 Windows Defender 检查存在某些已知模式的可疑活动。|
|提示用户提交给 Microsoft 的可疑文件|选择自动向 Microsoft 发送文件，以做进一步分析。|
|若要执行的系统扫描的类型|如果 Windows Defender 将一次快速扫描、 完全扫描或没有扫描设备的选择。|
|每日快速扫描时间|选择 Windows Defender 运行每日快速扫描的日期的哪些小时。|
|扫描所有下载的文件|自动扫描所有下载的文件的恶意软件。|
|扫描 Microsoft web 浏览器中运行的脚本|扫描网站尝试在 Microsoft Edge 和 Internet Explorer 中运行的所有脚本。|
|完全扫描期间扫描可移动驱动器|在完全扫描期间包括可移动驱动器，如 USB 记忆棒。|
|扫描通过网络打开的文件|扫描所有文件使用网络时打开的网站中的用户。|
|完全扫描期间扫描远程文件夹|在完全扫描期间扫描远程位置上的任何文件夹。|
|扫描存档文件|扫描存档文件，如.zip 或.rar。|
|扫描传入的电子邮件|扫描通过网络接收的所有电子邮件。|
|打开文件或程序时，恶意软件扫描|当某个文件或程序打开，并会提醒用户有关可疑活动，扫描恶意软件。|
|删除已隔离恶意软件前一天| 设置受影响的文件的保存天数。 此天数后，删除该文件。 例如，如果设置为 0，该文件会被立即删除。|
|设置反恶意软件更新频率|选择 Windows Defender 应该检查并下载反恶意软件的更新频率。|
|可能不需要的应用程序保护|Windows Defender 提醒用户，并阻止可能不需要的软件试图安装自身在设备上。|
|阻止可疑文件|如果配置此设置，Windows Defender 防病毒软件将更主动地找出要阻止和扫描可疑文件。 如果未配置，它将阻止和扫描频率较低。 可以选择**未配置**，**高**，**超高**，以及**零容差**。 **高**主动阻止未知的文件，同时对设备性能的影响降到最低。 **超高**主动阻止未知的文件，但可能会对设备性能产生负面影响。 **零容差**阻止所有未知的文件运行。|
|启用云提供的保护|当 Windows Defender 将信息向 Microsoft 发送有关潜在安全威胁时可以获得实时保护。 此功能最适用于**提示用户提交给 Microsoft 的可疑文件**设置为自动发送文件。|
|检测到恶意软件威胁的操作|Windows Defender 将自动隔离检测到恶意软件。|
|启用网络检查服务|帮助保护设备免受基于网络的攻击。 使用来自 Microsoft Endpoint Protection 中心的已知漏洞签名来帮助检测和阻止恶意流量。|
|从扫描和实时保护中排除具有这些扩展名的文件|定义用户可以打开而无需扫描的安全威胁的文件的类型。
|从扫描和实时保护中排除进程|定义用户可以运行而无需扫描的安全威胁的进程类型。
|从扫描和实时保护中排除目录|定义用户可以访问而无需扫描的安全威胁的文件位置。|   

### <a name="windows-smartscreen"></a>Windows SmartScreen  

|设置|其作用|
|---|---|
|阻止用户重写有关网站的 SmartScreen 警告|阻止用户忽略并访问由 SmartScreen 筛选器阻止的网站。|
|阻止用户重写从 web 下载有关 SmartScreen 警告|阻止学生忽略和下载未经验证的文件的 SmartScreen 筛选器警告。|
|启用 SmartScreen 检查无法识别的应用程序和文件|启用 SmartScreen，通过检查无法识别的应用程序保护设备。|
|阻止用户重写有关应用程序和文件的 SmartScreen 警告|消除 SmartScreen 警告有关潜在恶意文件和应用程序块学生。|


## <a name="shared-devices"></a>共享的设备  
配置控制如何教师和学生共享的设备的设置。

|设置|其作用|
|---|---|
|优化设备进行共享|配置共享设备，例如电源和更新管理的推荐的设置。 允许多个学生或教师，登录到同一设备。|
|阻止来宾用户| 启用时，此选项才可用**优化设备进行共享**。 阻止来宾用户在登录到的共享设备。 阻止时，只有域用户可以登录。|  
|阻止访问本地存储| 启用时，此选项才可用**优化设备进行共享**。 阻止用户将文件保存到设备。 阻止时，用户可以仅保存到云。 | 
|阻止快速用户切换|允许用户从开始菜单的用户帐户之间快速切换。|  


### <a name="remove-built-in-apps"></a>删除内置应用  

当您选择以优化设备进行共享时，将从教师和学生删除这些应用程序的计算机：

* 混合的现实查看器  
* 天气
* 桌面应用程序安装工具
* 提示
* 我的办公室
* 纸牌集合
* 移动计划
* Windows 反馈中心
* Xbox
* Groove 音乐
* Mail
* Calendar
* Skype  

## <a name="updates-and-upgrade"></a>更新和升级
配置设备如何接收更新和升级。    

### <a name="updates"></a>Updates  

|设置|其作用|
|---|---|
|分支就绪级别|选择设备是否在 Current Branch 或 Current Branch 的业务的 Windows 更新。|
|配置如何以及何时安装更新|设置更新和维护期间更新的安装。|
|天数延迟功能更新后，将它们分别提供 (0-365)|设置等待要应用一项功能的多少天更新变得可用之后。 例如，如果设置为 0 天，只需变为可用的功能更新将立即应用于你的设备。|
|延迟质量更新后，将它们分别提供 (0-30) 天内|设置多少天，等待要应用的质量更新变得可用之后。 例如，如果设置为 0 天，只需变为可用的质量更新将立即应用于你的设备。|
|在删除前的天数卸载文件 (2-60)|安装功能更新后，则 Windows 将保留卸载新内部版本和还原到前一个所需文件。 设置等待卸载这些文件的天数。|
|阻止正在暂停 Windows 更新|暂停更新功能阻止用户访问。|
|允许学生，若要查看 Windows 10 的预发行功能|选择学生见设置的预发行功能，用于设置和试验，预发行功能或预发布功能。|
|传递优化模式|选择你想要将更新传递到设备。|  

### <a name="upgrade"></a>升级
|设置|其作用|
|---|---|
|要升级到的 Windows 版本| 此组中的将设备升级到另一版本的 Windows 10。 选择**要升级到版本**并输入**产品密钥**。|
|切出 S 模式|以前称为 Windows 10 S，S 模式是一个更安全的 Windows 10 版本。 此设置允许用户切换出 S 模式其设备。 **将保留在 S 模式**防止将其切换。 在 S 模式下，教师和学生使用 Microsoft Edge 和从 Microsoft Store 下载应用只能浏览。|

## <a name="user-experience"></a>用户体验   
配置的用户体验设置：   

  * 设备限制  
  * 锁定屏幕和桌面  
  * 设置应用程序  
  * “开始”菜单  

### <a name="device-restrictions"></a>设备限制  

|设置|其作用|
|---|---|
|阻止使用相机|阻止使用设备相机。|
|阻止 OneDrive 文件同步|阻止设备同步到 OneDrive 的文件。|
|阻止可移动存储|阻止使用可移动存储，如 U 盘、 SD 卡和外部硬盘的容量。|
|阻止 Cortana|阻止 Cortana，数字助理内置于 Windows 10 可以回答的问题和执行任务。|
|阻止定位服务|阻止应用使用位置服务来访问设备的位置。|  
|块结束任务在任务管理器|阻止用户使用任务管理器强制执行程序、 进程或关闭的任务。|
|阻止更改日期和时间设置|阻止用户更改设备日期和时间设置。|
|阻止更改语言设置|阻止用户更改设备的语言。|
|阻止更改设备区域设置|阻止用户更改区域设置，例如国家/地区和语言。|
|阻止更改电源和睡眠设置|阻止用户更改电源和睡眠设置。|
|发送诊断数据|定义是否收集并发送给 Microsoft 以帮助改进 Windows 的匿名使用情况数据。|  

### <a name="lock-screen-and-desktop"></a>锁定屏幕和桌面  

|设置|其作用|
|---|---|
|设置自定义锁屏图像|在登录屏幕上配置自定义背景图像。 您可以选择.jpg 或.png 小于的 20 MB 的大小。|
|设置自定义桌面图像|在桌面上配置自定义背景图像。 您可以选择.jpg 或.png 小于的 20 MB 的大小。|
|阻止 Windows 聚焦|阻止这些设备上的所有 Windows 聚焦功能。|
|阻止在锁屏界面上的通知|阻止从显示在屏幕锁定的设备上的通知。|
|锁定屏幕上的块 Cortana|防止用户在锁定屏幕中访问 Cortana。|

### <a name="settings-app"></a>设置应用程序  

|设置|其作用|
|---|---|
|阻止访问设置应用|阻止用户对整个设置应用程序访问权限。 若要阻止应用部分，选择从本部分中的其他设置。
|系统设置|阻止显示、 通知、 应用、 电源设置。|
|设备|阻止蓝牙、 打印机和的详细信息。|
|网络和 Internet|阻止 Wi-fi、 飞行模式和 VPN。|
|个性化设置|块的背景、 锁屏界面和颜色修改。|
|帐户|阻止用户帐户、 电子邮件、 同步、 工作和其他人。|
|时间和语言|块大小、 区域和日期。|
|轻松访问|阻止讲述人、 放大镜和高对比度。|
|隐私|块的位置和照相机。|
|更新和安全|阻止 Windows 更新、 恢复和备份。|  
|应用|阻止卸载，默认值和可选功能。|
|游戏|阻止游戏栏、 DVR、 广播和游戏模式。|  

### <a name="start-menu"></a>“开始”菜单  

|设置|其作用|
|---|---|
|强制开始菜单大小|定义是否强制开始菜单以显示全屏显示。|
|块跳转列表中显示最近从开始菜单打开程序|阻止跳转列表使其不显示在开始菜单上，禁用设置应用中的相应切换。|
|阻止在开始菜单中显示最近添加的应用|块最近添加从开始菜单中显示的应用程序。|
|阻止在开始菜单中显示最常用的应用|阻止从开始菜单中显示最常用的应用。|
|在开始菜单中的块应用列表|阻止从开始菜单中显示设备上的所有应用的列表。|
|在开始菜单中的块电源菜单|阻止 power 菜单上 （例如，重新启动，请关闭向下） 从开始菜单中显示。|
|在开始菜单中的块用户磁贴|阻止从开始菜单中正在显示当前用户的信息。|
|阻止选项出现在开始菜单中的用户磁贴上|你可以选择**更改帐户设置**，**锁**，并**注销**。|
|在开始菜单中选择的显示文件夹|你可以选择**文件资源管理器**，**设置**，**文档**，**下载**，**音乐**， **图片**，**视频**，**家庭组**，**网络**，并且**个人文件夹**。|
|应用自定义开始菜单布局|应用自定义开始菜单布局使用 XML 文件。 你可以上载小于 2 MB 的.xml 文件的大小。|
|将网站固定为开始菜单中的磁贴|固定网站作为磁贴开始菜单使用 XML 文件。 你可以上载小于 2 MB 的.xml 文件的大小。|  



## <a name="next-steps"></a>后续步骤  
配置 Intune for Education 门户中的组、 应用和设备设置。 如果尚未做它，请转到[快速配置](edu-express-config-settings-windows.md)并设置您的学校用 Microsoft 建议的设置。  

需要帮助管理设备？ [分配组管理员](group-admin-delegate.md)中您的学校来帮助你管理设备设置。  此外可以[详细了解完整的 Windows 10 设置管理体验](https://docs.microsoft.com/intune/deploy-use/windows-10-policy-settings-in-microsoft-intune)在 Intune 中可用。  
