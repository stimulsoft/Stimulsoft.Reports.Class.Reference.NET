---
title: "StiSunburstSeriesElementGeom Class"
---

## StiSunburstSeriesElementGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesElementGeom  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BeginTime** | TimeSpan |  |
| **BorderColor** | Color |  |
| **Brush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ClientRectangleDt** | RectangleF |  |
| **EndAngle** | float |  |
| **Path** | List<[StiSegmentGeom](../Stimulsoft/Base/Context/StiSegmentGeom.md)> |  |
| **RadiusFrom** | float |  |
| **RadiusTo** | float |  |
| **StartAngle** | float |  |

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

