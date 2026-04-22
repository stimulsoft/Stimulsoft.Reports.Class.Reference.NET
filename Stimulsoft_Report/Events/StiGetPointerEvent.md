---
title: "StiGetPointerEvent Class"
---

## StiGetPointerEvent Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGetPointerEvent
```

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetPointerEvent**() | Creates a new object of the type StiGetBookmarkEvent. |
| **StiGetPointerEvent**(string script) | Creates a new object of the type StiGetBookmarkEvent with specified arguments. |
| **StiGetPointerEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |
