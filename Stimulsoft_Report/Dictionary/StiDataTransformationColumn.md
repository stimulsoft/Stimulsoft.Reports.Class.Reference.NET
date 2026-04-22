---
title: "StiDataTransformationColumn Class"
---

## StiDataTransformationColumn Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes a data transformation column.

```csharp
public class StiDataTransformationColumn
```

### Inheritance

Inherits from: StiDataColumn  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataTransformationColumn**() | Creates a new object of the type StiCalcDataColumn. |
| **StiDataTransformationColumn**(string name, string alias, Type type, string expression) |  |
| **StiDataTransformationColumn**(string name, string alias, Type type, string expression, string key, [StiDataTransformationMode](StiDataTransformationMode.md) mode) | Creates a new object of the type StiCalcDataColumn. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Expression** | string |  |
| **Mode** | [StiDataTransformationMode](StiDataTransformationMode.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDictionaryColumn** | StiDataColumn |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
