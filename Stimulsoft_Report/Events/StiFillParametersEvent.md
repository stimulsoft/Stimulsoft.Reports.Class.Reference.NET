---
title: "StiFillParametersEvent Class"
---

## StiFillParametersEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFillParametersEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiFillParametersEvent()` | Creates a new object of the type StiFillParametersEvent. |
| `StiFillParametersEvent(string script)` | Creates a new object of the type StiFillParametersEvent with specified arguments. |
| `StiFillParametersEvent(StiComponent parent)` | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
