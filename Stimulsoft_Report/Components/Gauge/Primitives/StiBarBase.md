---
title: "StiBarBase Class"
---

## StiBarBase Class

**Namespace:** `Stimulsoft.Report.Components.Gauge.Primitives`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiBarBase
```

### Inheritance

Inherits from: StiIndicatorBase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiBarBase()` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BarType** | [StiBarRangeListType](../../../Gauge/StiBarRangeListType.md) |  |
| **EmptyBorderBrush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **EmptyBorderWidth** | float |  |
| **EmptyBrush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **EndWidth** | float |  |
| **Offset** | float |  |
| **RangeList** | StiBarRangeListCollection |  |
| **StartWidth** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckActualBrushForTopGeometry** | void |  |
| **Clone** | object |  |
| **LoadFromJsonObject** | void |  |
| **OnRangeColorChanged** | void |  |
| **OnValueChanged** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
