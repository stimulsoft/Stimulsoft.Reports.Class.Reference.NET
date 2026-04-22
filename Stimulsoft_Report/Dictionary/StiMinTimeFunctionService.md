---
title: "StiMinTimeFunctionService Class"
---

## StiMinTimeFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the class for work with MinTime aggregate function. To calculate the type TimeSpan is used.

```csharp
public class StiMinTimeFunctionService
```

### Inheritance

Inherits from: StiAggregateFunctionService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMinTimeFunctionService()` |  |
| `StiMinTimeFunctionService(bool runningTotal)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalcItem** | void | A value calculation. |
| **GetResultType** | Type | Returns the type of the result. |
| **GetValue** | object | Returns the calculation result. |
| **Init** | void | First initialization. |
| **RestoreState** | void | Restores the earlier saved object state. |
| **SaveState** | void | Saves the current state of an object. |
| **SetValue** | void | Sets the calculation result. |
