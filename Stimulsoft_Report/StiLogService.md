---
title: "StiLogService Class"
---

## StiLogService Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

The service that is responsible for keeping the log in the report system.

```csharp
public class StiLogService
```

### Inheritance

Inherits from: [StiService](../Stimulsoft_Base/Services/StiService.md)  
Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClearLogOnStart** | bool |  |
| **TraceEnabled** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **Write** `static` *(+3 overloads)* | void | Writes an message into the log. |
| **WriteLogString** | void | Writes an message into the log. |
