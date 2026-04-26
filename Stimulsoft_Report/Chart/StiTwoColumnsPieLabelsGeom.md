---
title: "StiTwoColumnsPieLabelsGeom Class"
---

## StiTwoColumnsPieLabelsGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiSeriesLabelsGeom](StiSeriesLabelsGeom.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md) |  |
| **ArcPoint** | PointF |  |
| **BorderColor** | Color |  |
| **CenterPie** | PointF |  |
| **EndPoint** | PointF |  |
| **LabelBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **LabelRect** | RectangleF |  |
| **LineColor** | Color |  |
| **SeriesBorderColor** | Color |  |
| **SeriesBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **SeriesLabelsBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **StartPoint** | PointF |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws area geom object on spefied context. |
| **DrawMarker** | void |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws area geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### DrawMarker

**DrawMarker**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **itemRect**: Rectangle, **markerColor**: object, **markerBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **itemRect** (Rectangle)  
- **markerColor** (object)  
- **markerBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  

