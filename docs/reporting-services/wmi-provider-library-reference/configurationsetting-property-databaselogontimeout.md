---
title: "DatabaseLogonTimeout Property (WMI MSReportServer_ConfigurationSetting) | Microsoft Docs"
ms.custom: ""
ms.date: "03/01/2017"
ms.prod: reporting-services
ms.prod_service: "reporting-services-sharepoint, reporting-services-native"
ms.service: ""
ms.component: "wmi-provider-library-reference"
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 


ms.tgt_pltfrm: ""
ms.topic: "article"
apiname: 
  - "DatabaseLogonTimeout Property"
apilocation: 
  - "reportingservices.mof"
apitype: "MOFDef"
helpviewer_keywords: 
  - "DatabaseLogonTimeout property"
ms.assetid: 4a65162c-33de-485e-8fd3-2bd6bff8bf8d
caps.latest.revision: 38
author: "markingmyname"
ms.author: "maghan"
manager: "kfile"
ms.workload: "Inactive"
---
# ConfigurationSetting Property - DatabaseLogonTimeout
  Specifies the number of seconds to wait before an attempt to log on to the report server database fails. A value of **0** indicates an infinite wait time. Read only.  
  
## Syntax  
  
```vb  
Public Dim DatabaseLogonTimeout As Int32  
```  
  
```csharp  
public Int32 DatabaseLogonTimeout;  
```  
  
## Property Values  
 A 32-bit signed integer object that represents the number of seconds.  
  
## Example Code  
 [MSReportServer_ConfigurationSetting Class](../../reporting-services/wmi-provider-library-reference/msreportserver-configurationsetting-class.md)  
  
## Requirements  
 **Namespace:** [!INCLUDE[ssRSWMInmspcA](../../includes/ssrswminmspca-md.md)]  
  
## See Also  
 [MSReportServer_ConfigurationSetting Members](../../reporting-services/wmi-provider-library-reference/msreportserver-configurationsetting-members.md)  
  
  
