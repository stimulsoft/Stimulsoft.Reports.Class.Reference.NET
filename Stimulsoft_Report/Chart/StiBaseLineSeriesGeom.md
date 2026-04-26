---
title: "StiBaseLineSeriesGeom Class"
---

## StiBaseLineSeriesGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiSeriesGeom](StiSeriesGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBaseLineSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, [StiSeriesPointsInfo](StiSeriesPointsInfo.md) pointsInfo, IStiSeries series) |  |
| **StiBaseLineSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, PointF?pointsFrom , PointF?points , IStiSeries series) |  |

**StiBaseLineSeriesGeom**(**areaGeom**: [StiAreaGeom](StiAreaGeom.md), **pointsInfo**: [StiSeriesPointsInfo](StiSeriesPointsInfo.md), **series**: IStiSeries)

**Parameters**

- **areaGeom** ([StiAreaGeom](StiAreaGeom.md))  
- **pointsInfo** ([StiSeriesPointsInfo](StiSeriesPointsInfo.md))  
- **series** (IStiSeries)  

---

**StiBaseLineSeriesGeom**(**areaGeom**: [StiAreaGeom](StiAreaGeom.md), ****: PointF?pointsFrom, ****: PointF?points, **series**: IStiSeries)

**Parameters**

- **areaGeom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (PointF?pointsFrom)  
- **** (PointF?points)  
- **series** (IStiSeries)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Points** | PointF?[] |  |
| **PointsFrom** | PointF?[] |  |
| **PointsIds** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws area geom object on spefied context. |
| **GetAnimation** *(+2 overloads)* | [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md) |  |
| **GetAnimationConnect** | [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md) |  |
| **InvokeMouseEnter** | void |  |
| **InvokeMouseLeave** | void |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws area geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### GetAnimation

**GetAnimation**(): [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)

**Returns** [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)

---

**GetAnimation**(****: PointF?points): [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)

**Parameters**

- **** (PointF?points)  

**Returns** [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)

---

**GetAnimation**(****: PointF?pointsFrom, ****: PointF?points, ****: stringpointsIds): [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)

**Parameters**

- **** (PointF?pointsFrom)  
- **** (PointF?points)  
- **** (stringpointsIds)  

**Returns** [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)


---

#### GetAnimationConnect

**GetAnimationConnect**(****: PointF?points): [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)

**Parameters**

- **** (PointF?points)  

**Returns** [StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)


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

