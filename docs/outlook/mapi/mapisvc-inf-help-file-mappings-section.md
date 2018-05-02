---
title: "MapiSvc.inf [Help File Mappings] Section"
 
 
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
 
 
localization_priority: Normal
api_type:
- COM
ms.assetid: 62aee641-b73f-4f53-9e8d-adf010c9ea1a
description: "Last modified: July 23, 2011"
---

# MapiSvc.inf [Help File Mappings] Section

 **Last modified:** July 23, 2011 
  
 * **Applies to:** Outlook * 
  
The **[Help File Mappings]** section contains entries that each map one message service to the file that provides Help for errors generated by the service. Entries in this section use the following format: 
  
 **[Help File Mappings]** _message service name_ =  _Help file name_
  
The message service name is the name of the installed message service; the Help file name is the name of the file where the error information resides. The example following shows a typical **[Help File Mappings]** section that contains entries for three services: MAPI, the MsgService service, and the MS service. 
  
```
[Help File Mappings]
MAPI=MAPI.HLP
MsgService=MYHELP.HLP
MS=STORE.HLP

```

