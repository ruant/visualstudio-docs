---
title: "&#39;&lt;method1&gt;&#39; and &#39;&lt;method2&gt;&#39; cannot overload each other because they differ only by parameters declared &#39;ByRef&#39; or &#39;ByVal&#39;"
ms.custom: na
ms.date: 10/01/2016
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-csharp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 82af13b1-2641-4881-b25a-c782974bded1
caps.latest.revision: 8
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
# &#39;&lt;method1&gt;&#39; and &#39;&lt;method2&gt;&#39; cannot overload each other because they differ only by parameters declared &#39;ByRef&#39; or &#39;ByVal&#39;
You have attempted to overload a method with another method that differs from the first only by a parameter declared as `ByRef` or `ByVal`.  
  
 **Error ID:** BC30345  
  
### To correct this error  
  
-   Ensure that the methods are differentiated by more than the name of the `ByRef` or `ByVal` parameter.  
  
## See Also  
 [Procedure Overloading](../Topic/Procedure%20Overloading%20\(Visual%20Basic\).md)   
 [Considerations in Overloading Procedures](../Topic/Considerations%20in%20Overloading%20Procedures%20\(Visual%20Basic\).md)