---
title: "StiSeriesLabelsGeom Class"
---

## StiSeriesLabelsGeom Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiSeriesLabelsGeom
```

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSeriesLabelsGeom(IStiSeriesLabels seriesLabels, IStiSeries series, int index, double value, RectangleF clientRectangle)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BeginTime** | TimeSpan |  |
| **Duration** | TimeSpan |  |
| **Index** | int |  |
| **Series** | IStiSeries |  |
| **SeriesLabels** | IStiSeriesLabels |  |
| **Value** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws area geom object on spefied context. |
| **DrawMarker** | void |  |
| **InvokeMouseEnter** | void |  |
| **InvokeMouseLeave** | void |  |
