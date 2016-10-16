---
title: "How to: Create a Workflow Console Application"
ms.custom: na
ms.date: 10/02/2016
ms.prod: .net-framework-4.6
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
ms.assetid: 51a2eea7-921c-49f1-b358-68afc27f1ee9
caps.latest.revision: 16
manager: erikre
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - pl-pl
  - pt-br
  - ru-ru
  - tr-tr
  - zh-cn
  - zh-tw
---
# How to: Create a Workflow Console Application
Windows Workflow Foundation (WF) allows you to create workflows for executing system or human processes. The Windows Workflow Designer provides the design surface for creating these workflows. The Workflow Designer can be used to create workflows from within Visual Studio or it can be integrated into other applications that rehost the designer.  
  
 This topic describes how to use the Workflow Designer in Visual Studio 2010 to create a workflow in a console application.  
  
### To create a workflow console application  
  
1.  Start Visual Studio 2010.  
  
2.  On the **File** menu, point to **New**, and then select **Project…**.  
  
     The **New Project** dialog box opens.  
  
3.  In the **Installed Templates** pane, select **Workflow** from either the **Visual C#** or **Visual Basic** groupings, depending on your language of preference.  
  
4.  In the middle pane, select **Workflow Console Application**.  
  
5.  In the **Name** box, enter a descriptive name for your project to make it easy to identify.  
  
6.  In the **Location** box, enter the directory in which you want to save your project, or click **Browse** to navigate to it.  
  
7.  In the **Solution** box, enter the name for the new solution. Click **OK** to create the application.  
  
    > [!NOTE]
    >  If you want to add a workflow console application to an existing solution, open that solution in Visual Studio 2010, right click the solution in **Solution Explorer**, and select **Add**, then **New Project…** to open the **New Project** dialog box. Proceed as described above in this procedure.  
  
8.  The project template creates a workflow definition in XAML and the console application definition is in source code. The Workflow Designer opens and displays the canvas for the workflow you created.  
  
9. To compose a workflow, drag activities or other workflow items from the **Toolbox** to the design surface in your workflow.  
  
## See Also  
 [Creating a Workflow Project](../WF_Design/Creating-a-Workflow-Project.md)