---
title: "StiLineSeriesCoreXF3D Class"
---

## StiLineSeriesCoreXF3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiSeriesCoreXF3D](StiSeriesCoreXF3D.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLineSeriesCoreXF3D**(IStiSeries series) |  |

**StiLineSeriesCoreXF3D**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **GetSeriesBorderColor** | object |  |
| **GetSeriesColor** | Color |  |
| **RenderSeries3D** | void |  |

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

#### GetSeriesColor

**GetSeriesColor**(**colorIndex**: int, **colorCount**: int, **color**: Color): Color

**Parameters**

- **colorIndex** (int)  
- **colorCount** (int)  
- **color** (Color)  

**Returns** Color


---

#### RenderSeries3D

**RenderSeries3D**(**render3D**: [StiRender3D](StiRender3D.md), **context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: [StiRectangle3D](StiRectangle3D.md), **geom**: [StiAreaGeom](StiAreaGeom.md), **seriesIndex**: int, ****: IStiSeriesseries): void

**Parameters**

- **render3D** ([StiRender3D](StiRender3D.md))  
- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** ([StiRectangle3D](StiRectangle3D.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **seriesIndex** (int)  
- **** (IStiSeriesseries)  

