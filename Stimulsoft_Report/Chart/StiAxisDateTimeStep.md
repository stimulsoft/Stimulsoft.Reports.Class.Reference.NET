---
title: "StiAxisDateTimeStep Class"
---

## StiAxisDateTimeStep Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAxisDateTimeStep
```

### Inheritance

Implements: IStiAxisDateTimeStep  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxisDateTimeStep**() |  |
| **StiAxisDateTimeStep**([StiTimeDateStep](StiTimeDateStep.md) step, int numberOfValues) |  |
| **StiAxisDateTimeStep**([StiTimeDateStep](StiTimeDateStep.md) step, int numberOfValues, bool interpolation) |  |
| **StiAxisDateTimeStep**([StiTimeDateStep](StiTimeDateStep.md) step, int numberOfValues, bool interpolation, [StiDateTimeStepAggregation](StiDateTimeStepAggregation.md) aggregation) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Aggregation** | [StiDateTimeStepAggregation](StiDateTimeStepAggregation.md) |  |
| **Interpolation** | bool |  |
| **NumberOfValues** | int |  |
| **Step** | [StiTimeDateStep](StiTimeDateStep.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
