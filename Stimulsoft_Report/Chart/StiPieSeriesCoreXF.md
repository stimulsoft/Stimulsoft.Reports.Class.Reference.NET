---
title: "StiPieSeriesCoreXF Class"
---

## StiPieSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPieSeriesCoreXF**(IStiSeries series) |  |

**StiPieSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **CheckIntersectionLabels** | void |  |
| **CheckIntersectionOutLabels** | void |  |
| **GetArgumentText** | string |  |
| **GetColorCount** | int |  |
| **GetGradPerValue** | double |  |
| **GetPieDistance** *(+1 overloads)* | float |  |
| **GetPieSeriesLabels** | [IStiPieSeriesLabels](IStiPieSeriesLabels.md) |  |
| **GetPoint** | PointF |  |
| **GetPointCenter** | PointF |  |
| **GetRadius** | float |  |
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

#### CheckIntersectionLabels

**CheckIntersectionLabels**(**geom**: [StiAreaGeom](StiAreaGeom.md)): void

**Parameters**

- **geom** ([StiAreaGeom](StiAreaGeom.md))  


---

#### CheckIntersectionOutLabels

**CheckIntersectionOutLabels**(**geom**: [StiAreaGeom](StiAreaGeom.md)): void

**Parameters**

- **geom** ([StiAreaGeom](StiAreaGeom.md))  


---

#### GetArgumentText

**GetArgumentText**(**series**: IStiSeries, **index**: int): string

**Parameters**

- **series** (IStiSeries)  
- **index** (int)  

**Returns** string


---

#### GetColorCount

**GetColorCount**(****: IStiSeriesseriesArray, **isForValueFrom**: bool): int

**Parameters**

- **** (IStiSeriesseriesArray)  
- **isForValueFrom** (bool)  

**Returns** int


---

#### GetGradPerValue

**GetGradPerValue**(****: IStiSeriesseries, **isForValueFrom**: bool): double

**Parameters**

- **** (IStiSeriesseries)  
- **isForValueFrom** (bool)  

**Returns** double


---

#### GetPieDistance

**GetPieDistance**(**pieIndex**: int): float

**Parameters**

- **pieIndex** (int)  

**Returns** float

---

**GetPieDistance**(**series**: IStiPieSeries, **pieIndex**: int): float

**Parameters**

- **series** (IStiPieSeries)  
- **pieIndex** (int)  

**Returns** float


---

#### GetPieSeriesLabels

**GetPieSeriesLabels**(): [IStiPieSeriesLabels](IStiPieSeriesLabels.md)

**Returns** [IStiPieSeriesLabels](IStiPieSeriesLabels.md)


---

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

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseriesArray): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseriesArray)  

