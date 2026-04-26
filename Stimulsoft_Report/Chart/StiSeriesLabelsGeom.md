---
title: "StiSeriesLabelsGeom Class"
---

## StiSeriesLabelsGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSeriesLabelsGeom**(IStiSeriesLabels seriesLabels, IStiSeries series, int index, double value, RectangleF clientRectangle) |  |

**StiSeriesLabelsGeom**(**seriesLabels**: IStiSeriesLabels, **series**: IStiSeries, **index**: int, **value**: double, **clientRectangle**: RectangleF)

**Parameters**

- **seriesLabels** (IStiSeriesLabels)  
- **series** (IStiSeries)  
- **index** (int)  
- **value** (double)  
- **clientRectangle** (RectangleF)  


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


---

#### InvokeMouseEnter

**InvokeMouseEnter**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  


---

#### InvokeMouseLeave

**InvokeMouseLeave**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  

