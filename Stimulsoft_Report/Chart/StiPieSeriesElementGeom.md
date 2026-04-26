---
title: "StiPieSeriesElementGeom Class"
---

## StiPieSeriesElementGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesElementGeom  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BorderColor** | Color |  |
| **Count** | int |  |
| **EndAngle** | float |  |
| **Path** | List<[StiSegmentGeom](../Stimulsoft/Base/Context/StiSegmentGeom.md)> |  |
| **PathLight** | List<[StiSegmentGeom](../Stimulsoft/Base/Context/StiSegmentGeom.md)> |  |
| **Radius** | float |  |
| **StartAngle** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |
| **GetToolTipPoint** | [StiInteractionToolTipPointOptions](StiInteractionToolTipPointOptions.md) |  |

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

#### GetToolTipPoint

**GetToolTipPoint**(): [StiInteractionToolTipPointOptions](StiInteractionToolTipPointOptions.md)

**Returns** [StiInteractionToolTipPointOptions](StiInteractionToolTipPointOptions.md)

