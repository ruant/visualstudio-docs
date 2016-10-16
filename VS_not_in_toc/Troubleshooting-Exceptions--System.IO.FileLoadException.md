---
title: "Troubleshooting Exceptions: System.IO.FileLoadException"
ms.custom: na
ms.date: 10/01/2016
ms.devlang: 
  - JScript
  - VB
  - CSharp
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 6b4519e3-4d29-4031-8aec-c2735b4ee16d
caps.latest.revision: 11
manager: douge
translation.priority.ht: 
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - ru-ru
  - zh-cn
  - zh-tw
translation.priority.mt: 
  - cs-cz
  - pl-pl
  - pt-br
  - tr-tr
---
# Troubleshooting Exceptions: System.IO.FileLoadException
A <xref:System.IO.FileLoadException?qualifyHint=False> exception is thrown when a managed assembly is found but cannot be loaded.  
  
## Associated Tips  
 **Make sure that the file is a valid .NET Framework assembly.**  
 This exception is thrown if the file is not a valid .NET Framework assembly. For more information, see <xref:System.Reflection.Assembly?qualifyHint=False>.  
  
 **Check to make sure an assembly or module was not loaded twice with two different evidences.**  
 Evidence is the set of information that constitutes input to security policy decisions, such as what permissions can be granted to code. For more information, see <xref:System.EnterpriseServices.Internal.Publish.GacRemove?qualifyHint=False> and <xref:System.Reflection.Assembly.Evidence?qualifyHint=False>  
  
 **If using the RegisterAssembly or UnregisterAssembly methods, check to make sure the assembly name is not longer than MAX_PATH characters.**  
 The assembly name's length cannot exceed MAX_PATH. For more information, see <xref:System.EnterpriseServices.Internal.IComSoapPublisher.RegisterAssembly?qualifyHint=False> and <xref:System.EnterpriseServices.Internal.IComSoapPublisher.UnRegisterAssembly?qualifyHint=False>.  
  
 **If loading a satellite assembly, make sure the specified CultureInfo matches the file's CultureInfo.**  
 Satellite assemblies contain localized resources which contain non-localizable executable code and resources for a single culture that serve as the default or neutral culture. For more information, see <xref:System.Reflection.Assembly.GetSatelliteAssembly?qualifyHint=False>.  
  
## See Also  
 <xref:System.IO.FileLoadException?qualifyHint=False>   
 [Use the Exception Assistant](../Topic/How%20to:%20Use%20the%20Exception%20Assistant.md)