---
title: "StiMaxStrFunctionService Class"
---

## StiMaxStrFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the class for work with MaxStr aggregate function. To calculate the type string is used.

```csharp
public class StiMaxStrFunctionService
```

### Inheritance

Inherits from: StiAggregateFunctionService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMaxStrFunctionService**() |  |
| **StiMaxStrFunctionService**(bool runningTotal) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AscComparison** | Comparison<string> |  |
