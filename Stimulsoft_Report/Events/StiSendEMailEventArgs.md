---
title: "StiSendEMailEventArgs Class"
---

## StiSendEMailEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`

Describes an argument for the event StiSendEMailEvent.

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSendEMailEventArgs**([StiReport](../root/StiReport.md) report, string recipient, string subject, string body, string filePath) |  |

**StiSendEMailEventArgs**(**report**: [StiReport](../root/StiReport.md), **recipient**: string, **subject**: string, **body**: string, **filePath**: string)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **recipient** (string)  
- **subject** (string)  
- **body** (string)  
- **filePath** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Body** | string | Gets or sets a body of sending EMail. |
| **CallStandardHandler** | bool | Gets or sets a value indicating whether it is necessary to call standard handler. |
| **FilePath** | string | Gets or sets a file path of sending EMail. |
| **Recipient** | string | Gets or sets a recipient of sending EMail. |
| **Report** | [StiReport](../root/StiReport.md) | Gets or sets a report of sending EMail. |
| **Subject** | string | Gets or sets a subject of sending EMail. |
