---
title: "StiGetBarCodeEvent Class"
---

## StiGetBarCodeEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGetBarCodeEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetBarCodeEvent**() | Creates a new object of the type StiBarCodeEvent. |
| **StiGetBarCodeEvent**(string script) | Creates a new object of the type StiGetBarCodeEvent with specified arguments. |
| **StiGetBarCodeEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
