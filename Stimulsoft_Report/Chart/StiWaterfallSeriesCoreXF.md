---
title: "StiWaterfallSeriesCoreXF Class"
---

## StiWaterfallSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiClusteredColumnSeriesCoreXF](StiClusteredColumnSeriesCoreXF.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWaterfallSeriesCoreXF**(IStiSeries series) |  |

**StiWaterfallSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColumnRect** | RectangleF |  |
| **GetPointEnd** | PointF |  |
| **RenderSeries** | void |  |

---

### Method Details

#### GetColumnRect

**GetColumnRect**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **currentSeries**: IStiClusteredColumnSeries, **value**: double?, **seriesLeftPos**: float, **seriesWidth**: float, **posY**: float): RectangleF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **currentSeries** (IStiClusteredColumnSeries)  
- **value** (double?)  
- **seriesLeftPos** (float)  
- **seriesWidth** (float)  
- **posY** (float)  

**Returns** RectangleF


---

#### GetPointEnd

**GetPointEnd**(**currentSeries**: IStiClusteredColumnSeries, **value**: double?, **seriesLeftPos**: float, **seriesWidth**: float, **posY**: float): PointF

**Parameters**

- **currentSeries** (IStiClusteredColumnSeries)  
- **value** (double?)  
- **seriesLeftPos** (float)  
- **seriesWidth** (float)  
- **posY** (float)  

**Returns** PointF


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseries): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseries)  

