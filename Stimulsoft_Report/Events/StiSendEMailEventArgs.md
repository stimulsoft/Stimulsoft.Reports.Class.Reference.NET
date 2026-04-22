---
title: "StiSendEMailEventArgs Class"
---

## StiSendEMailEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

Describes an argument for the event StiSendEMailEvent.

```csharp
public class StiSendEMailEventArgs
```

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSendEMailEventArgs**([StiReport](../StiReport.md) report, string recipient, string subject, string body, string filePath) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Body** | string | Gets or sets a body of sending EMail. |
| **CallStandardHandler** | bool | Gets or sets a value indicating whether it is necessary to call standard handler. |
| **FilePath** | string | Gets or sets a file path of sending EMail. |
| **Recipient** | string | Gets or sets a recipient of sending EMail. |
| **Report** | [StiReport](../StiReport.md) | Gets or sets a report of sending EMail. |
| **Subject** | string | Gets or sets a subject of sending EMail. |
