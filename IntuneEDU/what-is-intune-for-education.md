---
title: 什么是 Intune for Education？
titleSuffix: Intune for Education
description: 了解关于 Intune for Education 和如何如何管理 iOS 和 Windows 设备在教育环境中。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 01/03/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: c66e1700-aac0-44c0-af89-d5d9d4fac9ae
searchScope:
- IntuneEDU
ms.openlocfilehash: 6e85a1c80c3a74735b716dbaa553baa06bbe7f3f
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146833"
---
# <a name="what-is-intune-for-education"></a>什么是 Intune for Education？

Microsoft Intune for Education 是面向学校的基于云的移动设备管理 (MDM) 服务。 它可帮助教师和学生保持课堂设备上高效工作，并可学校数据的安全。 

使用 Intune for Education 可以：
* 管理桌面和移动设备的学生用于访问课堂数据。
* 配置和分配的应用的学生在课堂中使用。
* 控制学生和教师如何访问和共享课堂信息。
* 应用于设备和应用学校安全要求。

Intune for Education 门户设计为包括仅设置和管理 iOS 和 Windows 所需的工作流学校的设备。 在门户中，可以查看和采取措施对你的设备、 用户和应用清单。 Intune for Education 还支持 Take a Test 应用，它允许教师评估直接从课堂设备的学生进度。  

## <a name="sign-up-for-intune-for-education"></a>注册 Intune 教育版
如果你尚不存在已使用 Intune for Education 帐户注册，了解[入门](https://docs.microsoft.com/intune/account-sign-up)。 本文适用于准备好注册 Intune 订阅其学校的系统管理员。 

## <a name="manually-add-users-to-you-intune-subscription"></a>手动将用户添加到你的 Intune 订阅
如果您不使用 Microsoft 学校数据同步 (SDS) 服务导入学生和教师的记录，则必须[手动将用户添加到你的 Intune 订阅](https://docs.microsoft.com/intune/users-add)。 通过 Azure 门户或 Office 365 门户，可以添加学生和教师。 用户设置时，您还需要授予管理员权限。 

## <a name="supported-os-and-browsers"></a>支持的 OS 和浏览器
完整的 Intune 管理服务支持多个设备操作系统。 对于学校设置，同样的问题，我们建议使用 Intune for Education。 它的门户设置到专门支持 Windows 10 和 iOS 学校的设备。  

若要查看受 Intune 支持 web 浏览器和操作系统的完整列表，请参阅[支持的操作系统和浏览器](https://docs.microsoft.com/intune/supported-devices-browsers)Microsoft Intune 文档中。  

## <a name="configuring-your-intune-for-education-tenant"></a>配置你的 Intune for Education 租户
*租户*指的是 Intune for Education 的组织的实例。 租户级别上的设置会影响您组织的 Intune 订阅。 同时具有 Intune for Education**常规**设置和**iOS 设备管理**租户设置。 

### <a name="general-settings"></a>常规设置
**常规**租户设置页面要求您的学校提供 IT 联系信息和资源信息。 此信息大多数是可选的但可用于为学生和教职员工提供 IT 点联系。  有关编辑常规设置的详细信息，请参阅[编辑常规设置](edu-tenant-general-settings.md)。 

### <a name="ios-device-management-settings"></a>iOS 设备管理设置  
**iOS 设备管理**设置寻求有关 Apple 帐户的信息。 这些设置是必需的组织想要管理其在 Intune 中的 iOS 设备。 配置适用于 iOS 的设备管理之前, 无法查看或管理 iOS 相关 Intune for Education 门户中的设置。

有关设置你的设备的 iOS 设备管理设置的详细信息，请参阅[设置 iOS 设备管理](setup-ios-device-management.md)。

仅[委派管理员](group-admin-delegate.md)Intune for Education 中允许查看和更改租户设置。

## <a name="does-intune-for-education-work-on-shared-devices"></a>共享设备可以处理 Intune for Education？  
Intune for Education 使用共享设备，并在一台设备上支持多个用户的管理。 共享设备的学生可能有不同的应用和针对它们的设置。 当学生登录到设备时，他们将看到的应用和专门为其分配的设置。  

## <a name="compatible-resources-and-tools"></a>兼容的资源和工具

将有权访问其他 Microsoft 管理工具，例如：
* 在 Azure 门户中，Microsoft Intune[完整的设备、 应用和用户管理体验](https://docs.microsoft.com/intune/understand-explore/introduction-to-microsoft-intune)
* Microsoft Azure Active Directory (Azure AD)、[标识和访问管理系统](https://docs.microsoft.com/azure/active-directory/active-directory-administer)
* [Microsoft 学校数据同步](https://sds.microsoft.com)
* [Office 365 教育版](https://support.office.com/article/Get-started-with-Office-365-Education-AB02ABE5-A1EE-458C-B749-5B44416CCF14)

使用 Intune for Education 与[Microsoft 教育](https://docs.microsoft.com/education/#pivot=itpro)这样的工具：

- [Office 365 教育版](https://support.office.com/article/Set-up-Office-365-for-business-6a3a29a0-e616-4713-99d1-15eda62d04fa)
- [Windows 10 教育版](https://docs.microsoft.com/education/windows)
- [Microsoft Store for Education](https://docs.microsoft.com/microsoft-store/index?toc=/microsoft-store/education/toc.json)
- [Minecraft:教育版](https://docs.microsoft.com/education/windows/school-get-minecraft)

> [!VIDEO https://www.youtube.com/embed/ukrnCwcLvV8]

## <a name="get-started-with-intune-for-education"></a>开始使用 Intune for Education
使用 Microsoft 学校数据同步的学生记录导入。使用学校电脑应用设置配置学校的 Windows 设备或登录到[Intune for Education](https://intuneeducation.portal.azure.com)设置适用于 iOS 设备的 Apple 管理。

从[仪表板](how-do-i-customize-my-dashboard.md)，启动[快速配置](Express-configuration-intune-edu.md)。 选择用户或设备组 (如学生、 教师，或_第二层的计算机实验室_) 和开始分配应用和设置。

![一次登录到 Intune for Education 的登陆页面的屏幕截图。](./media/dashboard-001-landing-page.png)
