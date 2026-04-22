---
title: "StiSumDistinctDecimalFunctionService Class"
---

## StiSumDistinctDecimalFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the class for work with SumDistinct aggregate function. To calculate the type Decimal is used.

```csharp
public class StiSumDistinctDecimalFunctionService
```

### Inheritance

Inherits from: [StiTwoArgumentAggregateFunctionService](StiTwoArgumentAggregateFunctionService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSumDistinctDecimalFunctionService()` |  |
| `StiSumDistinctDecimalFunctionService(bool runningTotal)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalcItem** *(+1 overloads)* | void | A value calculation. |
| **GetResultType** | Type | Returns the type of the result. |
| **GetValue** | object | Returns the calculation result. |
| **Init** | void | First initialization. |
| **RestoreState** | void | Restores the earlier saved object state. |
| **SaveState** | void | Saves the current state of an object. |
| **SetValue** | void | Sets the calculation result. |
