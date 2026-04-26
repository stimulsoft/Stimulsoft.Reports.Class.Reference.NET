---
title: "StiBubbleSeriesCoreXF Class"
---

## StiBubbleSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiScatterSeriesCoreXF](StiScatterSeriesCoreXF.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBubbleSeriesCoreXF**(IStiSeries series) |  |

**StiBubbleSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **RenderBubbles** | void |  |
| **RenderLines** | void |  |
| **RenderSeries** | void |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle, **color**: Color): void

**Parameters**

- **style** (IStiChartStyle)  
- **color** (Color)  


---

#### RenderBubbles

**RenderBubbles**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **geom**: [StiAreaGeom](StiAreaGeom.md), **series**: IStiBubbleSeries, ****: PointF?points, **weights**: double): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **series** (IStiBubbleSeries)  
- **** (PointF?points)  
- **weights** (double)  


---

#### RenderLines

**RenderLines**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **geom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseriesArray): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseriesArray)  

