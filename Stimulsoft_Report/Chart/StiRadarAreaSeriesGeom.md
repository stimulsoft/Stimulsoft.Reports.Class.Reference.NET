---
title: "StiRadarAreaSeriesGeom Class"
---

## StiRadarAreaSeriesGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRadarAreaSeriesGeom**(IStiSeries series, [StiSeriesPointsInfo](StiSeriesPointsInfo.md) pointsInfo) |  |

**StiRadarAreaSeriesGeom**(**series**: IStiSeries, **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md))

**Parameters**

- **series** (IStiSeries)  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Points** | PointF?[] |  |
| **PointsFrom** | PointF?[] |  |
| **PointsIds** | string[] |  |
| **Series** | IStiSeries |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |
| **InvokeMouseEnter** | void |  |
| **InvokeMouseLeave** | void |  |

---

### Method Details

#### Contains

**Contains**(**x**: float, **y**: float): bool

**Parameters**

- **x** (float)  
- **y** (float)  

**Returns** bool


---

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws area geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### InvokeMouseEnter

**InvokeMouseEnter**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  


---

#### InvokeMouseLeave

**InvokeMouseLeave**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  

