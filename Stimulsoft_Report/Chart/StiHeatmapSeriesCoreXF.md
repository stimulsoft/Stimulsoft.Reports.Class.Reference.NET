---
title: "StiHeatmapSeriesCoreXF Class"
---

## StiHeatmapSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHeatmapSeriesCoreXF**(IStiSeries series) |  |

**StiHeatmapSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **GetAllValues** | List<float> |  |
| **GetHeatmapColors** | Color[] |  |
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

#### GetAllValues

**GetAllValues**(): List<float>

**Returns** List<float>


---

#### GetHeatmapColors

**GetHeatmapColors**(): Color[]

**Returns** Color[]


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

