---
title: "StiSteppedLineSeriesGeom Class"
---

## StiSteppedLineSeriesGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiBaseLineSeriesGeom](StiBaseLineSeriesGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSteppedLineSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, [StiSeriesPointsInfo](StiSeriesPointsInfo.md) pointsInfo, IStiSeries series) |  |

**StiSteppedLineSeriesGeom**(**areaGeom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md), **series**: IStiSeries)

**Parameters**

- **areaGeom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  
- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |
| **GetSteppedPoints** | PointF?[] |  |
| **GetSteppedPointsIds** | string[] |  |

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

#### GetSteppedPoints

**GetSteppedPoints**(****: PointF?points): PointF?[]

**Parameters**

- **** (PointF?points)  

**Returns** PointF?[]


---

#### GetSteppedPointsIds

**GetSteppedPointsIds**(****: stringids): string[]

**Parameters**

- **** (stringids)  

**Returns** string[]

