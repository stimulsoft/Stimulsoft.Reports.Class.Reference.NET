---
title: "StiBaseLineSeriesGeom Class"
---

## StiBaseLineSeriesGeom Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiBaseLineSeriesGeom
```

### Inheritance

Inherits from: [StiSeriesGeom](StiSeriesGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBaseLineSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, [StiSeriesPointsInfo](StiSeriesPointsInfo.md) pointsInfo, IStiSeries series) |  |
| **StiBaseLineSeriesGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, PointF?pointsFrom , PointF?points , IStiSeries series) |  |

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
