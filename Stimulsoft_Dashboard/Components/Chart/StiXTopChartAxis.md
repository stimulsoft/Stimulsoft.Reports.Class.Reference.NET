---
title: "StiXTopChartAxis Class"
---

## StiXTopChartAxis Class

**Namespace:** `Stimulsoft.Dashboard.Components.Chart`  
**Assembly:** `Stimulsoft.Dashboard`

```csharp
public class StiXTopChartAxis
```

### Inheritance

Inherits from: StiXChartAxis  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiXTopChartAxis()` |  |
| `StiXTopChartAxis(StiChartAxisLabels labels, [StiXChartAxisTitle](StiXChartAxisTitle.md) title, bool visible)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Range** | StiChartAxisRange |  |
| **StartFromZero** | [StiAutoBool](../../../Stimulsoft_Base/StiAutoBool.md) |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShouldSerializeRange** | bool |  |
| **ShouldSerializeStartFromZero** | bool |  |
| **ShouldSerializeVisible** | bool |  |
