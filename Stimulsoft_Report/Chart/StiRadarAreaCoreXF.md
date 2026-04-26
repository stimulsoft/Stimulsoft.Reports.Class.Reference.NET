---
title: "StiRadarAreaCoreXF Class"
---

## StiRadarAreaCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAreaCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRadarAreaCoreXF**(IStiArea area) |  |

**StiRadarAreaCoreXF**(**area**: IStiArea)

**Parameters**

- **area** (IStiArea)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void | Applying specified style to this area. |
| **CheckIntersectionLabels** | void |  |
| **CreateStripLinesAxis** | void |  |
| **MeasureLabels** | RectangleF |  |
| **PrepareInfo** | void |  |
| **Render** | StiCellGeom |  |
| **RenderArguments** | void |  |
| **RenderSeries** | void |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle): void

Applying specified style to this area.

**Parameters**

- **style** (IStiChartStyle)  


---

#### CheckIntersectionLabels

**CheckIntersectionLabels**(**geom**: [StiAreaGeom](StiAreaGeom.md)): void

**Parameters**

- **geom** ([StiAreaGeom](StiAreaGeom.md))  


---

#### CreateStripLinesAxis

**CreateStripLinesAxis**(**axis**: [IStiYRadarAxis](IStiYRadarAxis.md), **minimum**: float, **maximum**: float): void

**Parameters**

- **axis** ([IStiYRadarAxis](IStiYRadarAxis.md))  
- **minimum** (float)  
- **maximum** (float)  


---

#### MeasureLabels

**MeasureLabels**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): RectangleF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** RectangleF


---

#### PrepareInfo

**PrepareInfo**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### Render

**Render**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **areaRect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **areaRect** (RectangleF)  

**Returns** StiCellGeom


---

#### RenderArguments

**RenderArguments**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **geom**: [StiRadarAreaGeom](StiRadarAreaGeom.md), **series**: IStiSeries): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **geom** ([StiRadarAreaGeom](StiRadarAreaGeom.md))  
- **series** (IStiSeries)  


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), **seriesCollection**: List<IStiSeries>): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **seriesCollection** (List<IStiSeries>)  

