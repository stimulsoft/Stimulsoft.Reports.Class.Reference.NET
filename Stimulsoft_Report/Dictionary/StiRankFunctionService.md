---
title: "StiRankFunctionService Class"
---

## StiRankFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the class for work with Rank aggregate function. To calculate the type Int is used.

```csharp
public class StiRankFunctionService
```

### Inheritance

Inherits from: StiAggregateFunctionService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiRankFunctionService()` |  |
| `StiRankFunctionService(bool runningTotal)` |  |
| `StiRankFunctionService(bool runningTotal, bool dense, [StiRankOrder](../StiRankOrder.md) sortOrder)` |  |

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
