---
title: "StiGetArgumentEvent Class"
---

## StiGetArgumentEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGetArgumentEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetArgumentEvent**() | Creates a new object of the type StiGetArgumentEvent. |
| **StiGetArgumentEvent**(string script) | Creates a new object of the type StiGetArgumentEvent with specified arguments. |
| **StiGetArgumentEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
