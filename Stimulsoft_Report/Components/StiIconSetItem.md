---
title: "StiIconSetItem Class"
---

## StiIconSetItem Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiIconSetItem
```

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIconSetItem**() | Creates a new object of the type StiIconSetItem. |
| **StiIconSetItem**([StiIcon](StiIcon.md) icon, [StiIconSetOperation](StiIconSetOperation.md) operation, [StiIconSetValueType](StiIconSetValueType.md) valueType, float value) | Creates a new object of the type StiIconSetItem. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Icon** | [StiIcon](StiIcon.md) |  |
| **Operation** | [StiIconSetOperation](StiIconSetOperation.md) |  |
| **Value** | float |  |
| **ValueType** | [StiIconSetValueType](StiIconSetValueType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
