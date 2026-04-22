---
title: "StiProcessChartEvent Class"
---

## StiProcessChartEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiProcessChartEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiProcessChartEvent**() | Creates a new object of the type StiPostProcessChartEvent. |
| **StiProcessChartEvent**(string script) | Creates a new object of the type StiPostProcessChartEvent with specified arguments. |
| **StiProcessChartEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
