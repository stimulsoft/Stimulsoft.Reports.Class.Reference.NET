---
title: "StiExportedEvent Class"
---

## StiExportedEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiExportedEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiExportedEvent()` | Creates a new object of the type StiExportedEvent. |
| `StiExportedEvent(string script)` | Creates a new object of the type StiExportedEvent with specified arguments. |
| `StiExportedEvent(StiComponent parent)` | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
