---
title: "StiPictorialSeriesCoreXF Class"
---

## StiPictorialSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPictorialSeriesCoreXF**(IStiSeries series) |  |

**StiPictorialSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Index** | int |  |
| **Series** | StiPictorialSeries |  |
| **Value** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **GetSeriesBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **RenderSeries** | void |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle, **color**: Color): void

**Parameters**

- **style** (IStiChartStyle)  
- **color** (Color)  


---

#### GetSeriesBrush

**GetSeriesBrush**(**colorIndex**: int, **colorCount**: int): [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **colorIndex** (int)  
- **colorCount** (int)  

**Returns** [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseriesArray): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseriesArray)  

