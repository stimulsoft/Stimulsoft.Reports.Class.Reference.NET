---
title: "StiMinStrFunctionService Class"
---

## StiMinStrFunctionService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the class for work with MinStr aggregate function. To calculate the type string is used.

```csharp
public class StiMinStrFunctionService
```

### Inheritance

Inherits from: StiAggregateFunctionService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMinStrFunctionService**() |  |
| **StiMinStrFunctionService**(bool runningTotal) |  |

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
