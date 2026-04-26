---
title: "StiStackedSplineAreaSeriesGeom Class"
---

## StiStackedSplineAreaSeriesGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiSeriesGeom](StiSeriesGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiStackedSplineAreaSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, [StiSeriesPointsInfo](StiSeriesPointsInfo.md) pointsInfo, IStiSeries series) |  |

**StiStackedSplineAreaSeriesGeom**(**areaGeom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md), **series**: IStiSeries)

**Parameters**

- **areaGeom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  
- **series** (IStiSeries)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EndPoints** | PointF?[] |  |
| **PointsIds** | string[] |  |
| **StartPoints** | PointF?[] |  |

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

