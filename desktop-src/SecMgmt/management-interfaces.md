---
Description: 'Lists the interfaces provided by the attachment engine.'
ms.assetid: '451587bd-a7ab-446b-b647-be98de251915'
title: Security Management Interfaces
---

# Security Management Interfaces

This section contains reference pages for the following groups of interfaces:

-   [Attachment Engine Interfaces](#attachment-engine-interfaces)

## Attachment Engine Interfaces



| Interface                                                            | Description                                                                                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**ISceSvcAttachmentData**](iscesvcattachmentdata.md)               | Retrieves configuration and analysis data about a specified security service from the Security Configuration snap-ins. The Security Configuration snap-ins expose this interface, which attachment snap-in extensions call to query configuration or analysis information.                                                 |
| [**ISceSvcAttachmentPersistInfo**](iscesvcattachmentpersistinfo.md) | Retrieves modified configuration or analysis information from an attachment snap-in. The Security Configuration snap-ins calls this interface to retrieve any modified information from the attachment snap-in extension. The Security Configuration snap-in then stores this data appropriately in the security database. |



 

For more information about the COM interfaces that must be implemented by snap-in extensions, see the [Microsoft Management Console](https://msdn.microsoft.com/library/aa814987) documentation.

 

 


