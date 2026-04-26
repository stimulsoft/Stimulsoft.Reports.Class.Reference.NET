---
title: "StiStackedBaseLineSeriesCoreXF Class"
---

## StiStackedBaseLineSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiStackedBaseLineSeriesCoreXF**(IStiSeries series) |  |

**StiStackedBaseLineSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **GetSeriesBorderColor** | object |  |
| **GetSeriesBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **RenderAreas** | void |  |
| **RenderLines** | void |  |
| **RenderMarkers** | void |  |
| **RenderSeries** | void |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle, **color**: Color): void

**Parameters**

- **style** (IStiChartStyle)  
- **color** (Color)  


---

#### GetSeriesBorderColor

**GetSeriesBorderColor**(**colorIndex**: int, **colorCount**: int): object

**Parameters**

- **colorIndex** (int)  
- **colorCount** (int)  

**Returns** object


---

#### GetSeriesBrush

**GetSeriesBrush**(**colorIndex**: int, **colorCount**: int): [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **colorIndex** (int)  
- **colorCount** (int)  

**Returns** [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### RenderAreas

**RenderAreas**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **geom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  


---

#### RenderLines

**RenderLines**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **geom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  


---

#### RenderMarkers

**RenderMarkers**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **geom**: [StiAreaGeom](StiAreaGeom.md), ****: PointF?points): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (PointF?points)  


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseries): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseries)  

