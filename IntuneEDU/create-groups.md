---
title: 在 Intune for Education 中创建组
titleSuffix: Intune for Education
description: 了解如何管理使用 Intune for Education 的设备组。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: doueby
ms.date: 07/23/2018
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.openlocfilehash: 1008314a0c9737736ce6e7768f704cd316c252fe
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62146717"
---
# <a name="create-groups-in-intune"></a><span data-ttu-id="6660d-103">在 Intune 中创建组</span><span class="sxs-lookup"><span data-stu-id="6660d-103">Create groups in Intune</span></span>

<span data-ttu-id="6660d-104">在 Intune 中的组功能允许您管理用户、 应用和设备管理要求基本相似。</span><span class="sxs-lookup"><span data-stu-id="6660d-104">The group feature in Intune lets you manage users, apps, and devices that have similar management needs.</span></span> <span data-ttu-id="6660d-105">使用组，可以减少单独管理和故障排除的设备所花费的时间。</span><span class="sxs-lookup"><span data-stu-id="6660d-105">With groups, you can reduce the time you spend individually managing and troubleshooting devices.</span></span> 

## <a name="default-groups"></a><span data-ttu-id="6660d-106">默认组</span><span class="sxs-lookup"><span data-stu-id="6660d-106">Default groups</span></span>  
<span data-ttu-id="6660d-107">-现成可用，Intune for Education 附带使你能够管理的默认组：</span><span class="sxs-lookup"><span data-stu-id="6660d-107">Out-of-the-box, Intune for Education comes with default groups that enable you to manage:</span></span>  
* <span data-ttu-id="6660d-108">“所有设备”</span><span class="sxs-lookup"><span data-stu-id="6660d-108">All devices</span></span>
* <span data-ttu-id="6660d-109">所有用户</span><span class="sxs-lookup"><span data-stu-id="6660d-109">All users</span></span>

<span data-ttu-id="6660d-110">如果您使用学校数据同步将学校记录导入，将创建两个额外的默认组。</span><span class="sxs-lookup"><span data-stu-id="6660d-110">Two additional default groups are created if you used School Data Sync to import your school records.</span></span> <span data-ttu-id="6660d-111">它们使您能够管理：</span><span class="sxs-lookup"><span data-stu-id="6660d-111">They enable you to manage:</span></span>  
* <span data-ttu-id="6660d-112">所有教师</span><span class="sxs-lookup"><span data-stu-id="6660d-112">All teachers</span></span>
* <span data-ttu-id="6660d-113">所有学生</span><span class="sxs-lookup"><span data-stu-id="6660d-113">All students</span></span>

<span data-ttu-id="6660d-114">这些默认组表示最广泛类别的用户和设备在您的学校和不能更改或删除。</span><span class="sxs-lookup"><span data-stu-id="6660d-114">These default groups represent the broadest categories of users and devices in your school and can't be changed or removed.</span></span>

## <a name="custom-groups"></a><span data-ttu-id="6660d-115">自定义组</span><span class="sxs-lookup"><span data-stu-id="6660d-115">Custom groups</span></span>  

<span data-ttu-id="6660d-116">将特定的或基于方案的配置应用于自定义创建的组。</span><span class="sxs-lookup"><span data-stu-id="6660d-116">Apply specific or scenario-based configurations to custom-created groups.</span></span> <span data-ttu-id="6660d-117">如果您的学校中必须使用 Windows 10 和 iOS 设备，创建组，如所有 Ipad 和所有 Windows 10 电脑。</span><span class="sxs-lookup"><span data-stu-id="6660d-117">If you have both Windows 10 and iOS devices in your school, create groups, such as all iPads and all Windows 10 PCs.</span></span> <span data-ttu-id="6660d-118">这样一来，你将能够更轻松地识别组和分发的设置。</span><span class="sxs-lookup"><span data-stu-id="6660d-118">This way, you'll be able to more easily recognize groups and distribute settings.</span></span> 

<span data-ttu-id="6660d-119">此外可以将应用和设置分配给特定组的学生。</span><span class="sxs-lookup"><span data-stu-id="6660d-119">You can also assign apps and settings to specific groups of students.</span></span> <span data-ttu-id="6660d-120">例如，第 8 个的等级课程可能需要不同的应用程序比第六级课程。</span><span class="sxs-lookup"><span data-stu-id="6660d-120">For example, an 8th grade curriculum may require different apps than a 6th grade curriculum.</span></span> <span data-ttu-id="6660d-121">您可以创建两个，特定于级的组和分配应用和设置适用于学生的每个集。</span><span class="sxs-lookup"><span data-stu-id="6660d-121">You can create two, grade-specific groups and assign apps and settings that are appropriate for each set of students.</span></span>  
## <a name="group-types"></a><span data-ttu-id="6660d-122">组类型</span><span class="sxs-lookup"><span data-stu-id="6660d-122">Group types</span></span>  

<span data-ttu-id="6660d-123">有两种类型的可用于组织用户和设备在 Intune for Education 的组： 分配的组和动态组。</span><span class="sxs-lookup"><span data-stu-id="6660d-123">There are two types of groups that you can use to organize users and devices in Intune for Education: assigned groups and dynamic groups.</span></span>

### <a name="assigned-groups"></a><span data-ttu-id="6660d-124">已分配的组</span><span class="sxs-lookup"><span data-stu-id="6660d-124">Assigned groups</span></span>  

<span data-ttu-id="6660d-125">当你想要手动将用户或设备添加到组时使用已分配的组。</span><span class="sxs-lookup"><span data-stu-id="6660d-125">Assigned groups are used when you want to manually add users or devices to a group.</span></span>  <span data-ttu-id="6660d-126">就像将档案系统放在一起： 将使用您自己的逻辑或分组方法的特定文件夹到文件特定的文章。</span><span class="sxs-lookup"><span data-stu-id="6660d-126">Think of it like putting a filing system together: you'll file specific papers into a specific folder using your own logic or method of grouping.</span></span> <span data-ttu-id="6660d-127">当您需要这些文章时，您就知道确切的文件夹，以转到。</span><span class="sxs-lookup"><span data-stu-id="6660d-127">When you need those papers, you'll know the exact folder to go to.</span></span> 

<span data-ttu-id="6660d-128">同样，您可以创建文件夹中的文件夹或*子组*，以便进一步组织到可管理的大小更大的组。</span><span class="sxs-lookup"><span data-stu-id="6660d-128">Similarly, you can create folders within folders, or *subgroups*, to further organize a larger group into a manageable size.</span></span>

<span data-ttu-id="6660d-129">若要了解如何手动分配或删除成员，请参阅[编辑组](edit-groups-intune-for-edu.md)。</span><span class="sxs-lookup"><span data-stu-id="6660d-129">To learn how to manually assign or remove members, see [Edit groups](edit-groups-intune-for-edu.md).</span></span>


### <a name="dynamic-groups"></a><span data-ttu-id="6660d-130">动态组</span><span class="sxs-lookup"><span data-stu-id="6660d-130">Dynamic groups</span></span>  
<span data-ttu-id="6660d-131">动态组引用创建将学生或设备分配到组的规则。</span><span class="sxs-lookup"><span data-stu-id="6660d-131">Dynamic groups reference rules that you create to assign students or devices to groups.</span></span> <span data-ttu-id="6660d-132">规则的条件在初始组创建过程中指定并创建组后，可以编辑。</span><span class="sxs-lookup"><span data-stu-id="6660d-132">The criteria for rules is specified during initial group creation, and can be edited after a group is created.</span></span>

<span data-ttu-id="6660d-133">例如，可以创建一组特定于 2019年学校年结束时从 Contoso 高毕业的学员。</span><span class="sxs-lookup"><span data-stu-id="6660d-133">For example, you can create a group specific to students graduating from Contoso High at the end of the 2019 school year.</span></span> <span data-ttu-id="6660d-134">而是不是通过和手动分配每个学生，Intune for Education 将到基于学校和毕业日期组筛选学生。</span><span class="sxs-lookup"><span data-stu-id="6660d-134">Rather than go through and assign each student manually, Intune for Education would filter the students into the group based on school and graduation date.</span></span>

<span data-ttu-id="6660d-135">如果在组中的一名学生传输超出 Contoso 高和到另一个学校，您学区，将无法从动态组中手动删除。</span><span class="sxs-lookup"><span data-stu-id="6660d-135">If a student within the group transfers out of Contoso High and into another school in your district, you would not be able to manually remove them from a dynamic group.</span></span> <span data-ttu-id="6660d-136">相反，您需要更新，以便 Intune 知道，他们知道不再满足成员资格的组条件的学生的学校名称。</span><span class="sxs-lookup"><span data-stu-id="6660d-136">Instead, you would need to update the student's school name so that Intune knows that they know longer meet the group criteria for membership.</span></span>

<span data-ttu-id="6660d-137">由于动态组只能包含其规则定义，因此不能创建在其下的子组。</span><span class="sxs-lookup"><span data-stu-id="6660d-137">Since dynamic groups can only contain what their rules define, you cannot create subgroups under them.</span></span>

<span data-ttu-id="6660d-138">若要了解如何编辑组规则，请参阅[编辑组](edit-groups-intune-for-edu.md)。</span><span class="sxs-lookup"><span data-stu-id="6660d-138">To learn how to edit group rules, see [Edit groups](edit-groups-intune-for-edu.md).</span></span>

> [!TIP]
> <span data-ttu-id="6660d-139">使用动态规则来筛选通过相似的组或最近登记组的设备，如*DeviceType_School_Grade_0001*。</span><span class="sxs-lookup"><span data-stu-id="6660d-139">Use the dynamic rules to filter through groups of similarly-named or recently onboarded groups of devices, such as *DeviceType_School_Grade_0001*.</span></span> <span data-ttu-id="6660d-140">动态组是非常适用于管理大量设备或大型学区中的用户。</span><span class="sxs-lookup"><span data-stu-id="6660d-140">Dynamic groups are ideal for managing large groups of devices or users in large school districts.</span></span> <span data-ttu-id="6660d-141">它们减少时间和手动遍历学校的清单或员工所需的成本。</span><span class="sxs-lookup"><span data-stu-id="6660d-141">They reduce the time and costs required to manually go through a school's inventory or headcount.</span></span>  


## <a name="plan-your-groups"></a><span data-ttu-id="6660d-142">规划组</span><span class="sxs-lookup"><span data-stu-id="6660d-142">Plan your groups</span></span>
<span data-ttu-id="6660d-143">若要开始，计划的设置和应用程序所需的学区、 学生、 教师和设备。</span><span class="sxs-lookup"><span data-stu-id="6660d-143">To get started, plan out the settings and apps required for your school district, students, teachers, and devices.</span></span> <span data-ttu-id="6660d-144">设置分配给组，并且一些组需要的特定设置和应用程序。</span><span class="sxs-lookup"><span data-stu-id="6660d-144">Settings are assigned to groups, and some groups will require specific settings and apps.</span></span>   

<span data-ttu-id="6660d-145">例如：</span><span class="sxs-lookup"><span data-stu-id="6660d-145">For example:</span></span>  
* <span data-ttu-id="6660d-146">对于所有的设备，阻止应用使用位置服务。</span><span class="sxs-lookup"><span data-stu-id="6660d-146">For all devices, block apps from using location services.</span></span> 
* <span data-ttu-id="6660d-147">有关 AP 计算机科学中，分配学生应用来编辑代码。</span><span class="sxs-lookup"><span data-stu-id="6660d-147">For AP computer science, assign students apps to edit code.</span></span>
* <span data-ttu-id="6660d-148">对于第 12 年级历史记录学生，来启用 web 浏览以便他们可以访问学术文章。</span><span class="sxs-lookup"><span data-stu-id="6660d-148">For 12th grade history students, enable web browsing so they can access academic articles.</span></span>
* <span data-ttu-id="6660d-149">对于摄影学生来启用设备照相机。</span><span class="sxs-lookup"><span data-stu-id="6660d-149">For photography students, enable device camera.</span></span>


## <a name="create-a-group"></a><span data-ttu-id="6660d-150">创建组</span><span class="sxs-lookup"><span data-stu-id="6660d-150">Create a group</span></span>  
<span data-ttu-id="6660d-151">组只能创建一个时间。</span><span class="sxs-lookup"><span data-stu-id="6660d-151">Groups must be created one a time.</span></span> <span data-ttu-id="6660d-152">安装过程中，你将选择要创建为任一用户或设备组。</span><span class="sxs-lookup"><span data-stu-id="6660d-152">During setup, you'll select to create a group for either users or for devices.</span></span>

1. <span data-ttu-id="6660d-153">从 Intune for Education 仪表板，单击**组** > **创建组**。</span><span class="sxs-lookup"><span data-stu-id="6660d-153">From the Intune for Education dashboard, click **Groups** > **Create group**.</span></span>
2. <span data-ttu-id="6660d-154">输入描述性的组名称。</span><span class="sxs-lookup"><span data-stu-id="6660d-154">Enter a descriptive group name.</span></span>
3. <span data-ttu-id="6660d-155">选择组类型。</span><span class="sxs-lookup"><span data-stu-id="6660d-155">Select a group type.</span></span> <span data-ttu-id="6660d-156">有关更多有关分配和动态组的详细信息，请参阅[类型分组](## Group types) </span><span class="sxs-lookup"><span data-stu-id="6660d-156">For more details about assigned and dynamic groups see [Group types](## Group types) </span></span>  
    <span data-ttu-id="6660d-157">a.</span><span class="sxs-lookup"><span data-stu-id="6660d-157">a.</span></span> <span data-ttu-id="6660d-158">分配：手动添加和删除这些组中的用户和设备。</span><span class="sxs-lookup"><span data-stu-id="6660d-158">Assigned: Manually add and remove users and device in these groups.</span></span> <span data-ttu-id="6660d-159">如果选择此选项，请转到步骤 5。</span><span class="sxs-lookup"><span data-stu-id="6660d-159">If you select this option, go to step 5.</span></span>
   <span data-ttu-id="6660d-160">b.</span><span class="sxs-lookup"><span data-stu-id="6660d-160">b.</span></span> <span data-ttu-id="6660d-161">动态：实现规则自动添加和删除用户和设备。</span><span class="sxs-lookup"><span data-stu-id="6660d-161">Dynamic: Rules are implemented to automatically add and remove users and devices.</span></span> <span data-ttu-id="6660d-162">如果选择此选项，请转到步骤 4。</span><span class="sxs-lookup"><span data-stu-id="6660d-162">If you select this option, go to step 4.</span></span>
4. <span data-ttu-id="6660d-163">选择以管理设备或学生。</span><span class="sxs-lookup"><span data-stu-id="6660d-163">Select to manage devices or students.</span></span>
    <span data-ttu-id="6660d-164">a.</span><span class="sxs-lookup"><span data-stu-id="6660d-164">a.</span></span> <span data-ttu-id="6660d-165">设备：如果选择此选项，则会显示命名规则。</span><span class="sxs-lookup"><span data-stu-id="6660d-165">Devices: If you select this, a naming rule appears.</span></span> <span data-ttu-id="6660d-166">创建一个规则，以将启动或包含您输入的文本的设备自动分配。</span><span class="sxs-lookup"><span data-stu-id="6660d-166">Create a rule to automatically assign devices that start or contain the text you input.</span></span> <span data-ttu-id="6660d-167">键入时，将在页面底部填充成员的预览。</span><span class="sxs-lookup"><span data-stu-id="6660d-167">As you type, a preview of members will populate at the bottom of the page.</span></span>
    <span data-ttu-id="6660d-168">b.</span><span class="sxs-lookup"><span data-stu-id="6660d-168">b.</span></span> <span data-ttu-id="6660d-169">学生：如果选择学生，将出现的位置和标识规则。</span><span class="sxs-lookup"><span data-stu-id="6660d-169">Students: If you select Students, a location and identification rule appears.</span></span> <span data-ttu-id="6660d-170">创建一个规则以自动分配转到你的租户中特定学校的学生。</span><span class="sxs-lookup"><span data-stu-id="6660d-170">Create a rule to automatically assign students that go to a specific school in your tenant.</span></span> <span data-ttu-id="6660d-171">然后选择此选项将学生组合在按等级或毕业年份。</span><span class="sxs-lookup"><span data-stu-id="6660d-171">Then select to group students by grade or graduation year.</span></span> <span data-ttu-id="6660d-172">输入所有字段后，将在页面底部填充成员的预览。</span><span class="sxs-lookup"><span data-stu-id="6660d-172">After you input all fields, a preview of members will populate at the bottom of the page.</span></span>
5. <span data-ttu-id="6660d-173">在页面底部，单击**创建组**。</span><span class="sxs-lookup"><span data-stu-id="6660d-173">At the bottom of the page, click **Create group**.</span></span>

## <a name="create-a-subgroup"></a><span data-ttu-id="6660d-174">创建子组</span><span class="sxs-lookup"><span data-stu-id="6660d-174">Create a subgroup</span></span>  
<span data-ttu-id="6660d-175">设置组在 Intune 中为层次结构。</span><span class="sxs-lookup"><span data-stu-id="6660d-175">Groups are set up in Intune as hierarchies.</span></span> <span data-ttu-id="6660d-176">父组是在层次结构的顶部和[应用到此组的任何设置由其下的组继承](settings-inheritance.md)。</span><span class="sxs-lookup"><span data-stu-id="6660d-176">The parent group is the top of the hierarchy, and [any settings applied to this group are inherited by the groups under it](settings-inheritance.md).</span></span> <span data-ttu-id="6660d-177">此概念称为*设置继承*。</span><span class="sxs-lookup"><span data-stu-id="6660d-177">This concept is known as *settings inheritance*.</span></span>  <span data-ttu-id="6660d-178">设置继承，可以更轻松地将设置应用于一支庞大的用户和设备。</span><span class="sxs-lookup"><span data-stu-id="6660d-178">Setting inheritance makes it easier to apply settings to a large group of users and devices.</span></span> 

<span data-ttu-id="6660d-179">只能在创建子组*下*为其分配组。</span><span class="sxs-lookup"><span data-stu-id="6660d-179">Subgroups can only be created *under* assigned groups.</span></span> 

 ![创建子组页面上的，具有子组创建两个位置，在组名称和侧栏的顶部 — 圈定的红色](./media/groups-007-create-subgroup.png)

1. <span data-ttu-id="6660d-181">转到**组**，然后选择一个组。</span><span class="sxs-lookup"><span data-stu-id="6660d-181">Go to **Groups** and choose a group.</span></span> <span data-ttu-id="6660d-182">此组将你的子组的父级。</span><span class="sxs-lookup"><span data-stu-id="6660d-182">This group will be the parent to your subgroup.</span></span>
2. <span data-ttu-id="6660d-183">单击**创建子组**。</span><span class="sxs-lookup"><span data-stu-id="6660d-183">Click **Create sub group**.</span></span>
3. <span data-ttu-id="6660d-184">输入**组名称**。</span><span class="sxs-lookup"><span data-stu-id="6660d-184">Enter the **Group name**.</span></span> 
4. <span data-ttu-id="6660d-185">选择组类型。</span><span class="sxs-lookup"><span data-stu-id="6660d-185">Select your group type.</span></span> <span data-ttu-id="6660d-186">有关组类型的更多详细信息，请参阅的步骤[创建一个组](#create-a-group)上面。</span><span class="sxs-lookup"><span data-stu-id="6660d-186">For more details about group types, see the steps for [Create a group](#create-a-group) above.</span></span>
5. <span data-ttu-id="6660d-187">单击**创建组**。</span><span class="sxs-lookup"><span data-stu-id="6660d-187">Click **Create group**.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="6660d-188">后续步骤</span><span class="sxs-lookup"><span data-stu-id="6660d-188">Next steps</span></span> 
<span data-ttu-id="6660d-189">[委派的权限](group-admin-delegate.md)以允许管理员组来管理父级别的组和子组。</span><span class="sxs-lookup"><span data-stu-id="6660d-189">[Delegate permission](group-admin-delegate.md) to allow admin groups to manage parent level groups and subgroups.</span></span>  

<span data-ttu-id="6660d-190">[了解完整](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)组在 Intune 中的管理体验。</span><span class="sxs-lookup"><span data-stu-id="6660d-190">[Learn about the full](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)groups management experience in Intune.</span></span>
