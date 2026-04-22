---
title: "StiLastFunctionService Class"
---

## StiLastFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the class for work with Last aggregate function. To calculate the type Object is used.

```csharp
public class StiLastFunctionService
```

### Inheritance

Inherits from: StiAggregateFunctionService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiLastFunctionService()` |  |
| `StiLastFunctionService(bool runningTotal)` |  |

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
