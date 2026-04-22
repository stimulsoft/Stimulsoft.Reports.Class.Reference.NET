---
title: "StiCardsVisual Class"
---

## StiCardsVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Cards`  
**Assembly:** `Stimulsoft.Dashboard`

```csharp
public class StiCardsVisual
```

### Inheritance

Inherits from: [StiVisual](../StiVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCardsVisual(StiCardsElement element, [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DataTable** | [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Element** | StiCardsElement |  |
| **Style** | StiCardsElementStyle |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws a visual object on specified context and at specified location. |
| **DrawEmptyData** | void |  |
| **GetColor** | Color |  |
| **GetStyleColor** | Color |  |
| **MeasureBubbleCell** | SizeF |  |
| **MeasureDataBarsCell** | SizeF |  |
| **MeasureIndicatorCell** `static` | SizeF |  |
| **MeasureSparklinesCell** `static` | SizeF |  |
| **ProcessColumnsWithTopN** | List<object[]> |  |
| **UnionRectangles** `static` | [RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **ZoomAndMoveUp** `static` | List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)> |  |
