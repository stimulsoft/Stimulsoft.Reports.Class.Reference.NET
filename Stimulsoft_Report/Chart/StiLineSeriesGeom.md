---
title: "StiLineSeriesGeom Class"
---

## StiLineSeriesGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiBaseLineSeriesGeom](StiBaseLineSeriesGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLineSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, [StiSeriesPointsInfo](StiSeriesPointsInfo.md) pointsInfo, IStiSeries series) |  |

**StiLineSeriesGeom**(**areaGeom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md), **series**: IStiSeries)

**Parameters**

- **areaGeom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  
- **series** (IStiSeries)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PointsNullConnect** | PointF?[] |  |
| **PointsZeroConnect** | PointF?[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |

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

