---
title: "StiClusteredColumnSeriesCoreXF Class"
---

## StiClusteredColumnSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiClusteredColumnSeriesCoreXF**(IStiSeries series) |  |

**StiClusteredColumnSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **CorrectPoint** | PointF |  |
| **GetColumnRect** | RectangleF |  |
| **GetPointEnd** | PointF |  |
| **GetSeriesBorderColor** | object |  |
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

#### CorrectPoint

**CorrectPoint**(**point**: PointF, **rect**: RectangleF): PointF

**Parameters**

- **point** (PointF)  
- **rect** (RectangleF)  

**Returns** PointF


---

#### GetColumnRect

**GetColumnRect**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **currentSeries**: IStiClusteredColumnSeries, **value**: double?, **seriesLeftPos**: float, **seriesWidth**: float): RectangleF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **currentSeries** (IStiClusteredColumnSeries)  
- **value** (double?)  
- **seriesLeftPos** (float)  
- **seriesWidth** (float)  

**Returns** RectangleF


---

#### GetPointEnd

**GetPointEnd**(**currentSeries**: IStiClusteredColumnSeries, **value**: double?, **seriesLeftPos**: float, **seriesWidth**: float): PointF

**Parameters**

- **currentSeries** (IStiClusteredColumnSeries)  
- **value** (double?)  
- **seriesLeftPos** (float)  
- **seriesWidth** (float)  

**Returns** PointF


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

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseries): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseries)  

