---
title: "StiSunburstSeriesCoreXF Class"
---

## StiSunburstSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSunburstSeriesCoreXF**(IStiSeries series) |  |

**StiSunburstSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetPoint** | PointF |  |
| **GetPointCenter** | PointF |  |
| **GetRadius** | float |  |
| **RenderSeries** | void |  |

---

### Method Details

#### GetPoint

**GetPoint**(**centerPie**: PointF, **radius**: float, **angle**: float): PointF

**Parameters**

- **centerPie** (PointF)  
- **radius** (float)  
- **angle** (float)  

**Returns** PointF


---

#### GetPointCenter

**GetPointCenter**(**rect**: RectangleF): PointF

**Parameters**

- **rect** (RectangleF)  

**Returns** PointF


---

#### GetRadius

**GetRadius**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): float

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** float


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseriesCollection): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseriesCollection)  

