---
title: "StiExportingEvent Class"
---

## StiExportingEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiExportingEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiExportingEvent**() | Creates a new object of the type StiExportingEvent. |
| **StiExportingEvent**(string script) | Creates a new object of the type StiExportingEvent with specified arguments. |
| **StiExportingEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
