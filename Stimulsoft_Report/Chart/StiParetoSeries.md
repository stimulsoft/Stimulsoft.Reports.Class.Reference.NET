---
title: "StiParetoSeries Class"
---

## StiParetoSeries Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiParetoSeries
```

### Inheritance

Inherits from: StiSeries  
Implements: IStiParetoSeries  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiParetoSeries**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowApplyBrushNegative** | bool |  |
| **AllowApplyColorNegative** | bool |  |
| **AllowApplyLineColor** | bool |  |
| **BorderColor** | Color |  |
| **BorderThickness** | int |  |
| **Brush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BrushNegative** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CornerRadius** | StiCornerRadius |  |
| **Icon** | StiFontIcons? |  |
| **LabelsOffset** | int |  |
| **LineColorNegative** | Color |  |
| **ShowNulls** | bool |  |
| **ShowNullsAs** | [StiShowEmptyCellsAs](StiShowEmptyCellsAs.md) |  |
| **ShowZeros** | bool |  |
| **ShowZerosAs** | [StiShowEmptyCellsAs](StiShowEmptyCellsAs.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **CreateNew** | StiSeries |  |
| **GetDefaultAreaType** | Type |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
