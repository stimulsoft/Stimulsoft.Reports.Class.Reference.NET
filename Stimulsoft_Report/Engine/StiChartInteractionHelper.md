---
title: "StiChartInteractionHelper Class"
---

## StiChartInteractionHelper Class

**Namespace:** `Stimulsoft.Report.Engine`

Class helps work with chart interactions.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetInteraction** `static` | [IStiGeomInteraction](../Chart/IStiGeomInteraction.md) | Returns IStiGeomInteraction object for specified chart at specified x and y location. |
| **ProcessChart** `static` | void |  |
| **ResetChartGeomCache** `static` | void | Resets all chart geom cache settings. |

---

### Method Details

#### GetInteraction `static`

**GetInteraction**(**chart**: [StiChart](../Chart/StiChart.md), **chartRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **x**: float, **y**: float, **chartGeom**: StiCellGeom, **zoom**: float, **typeNotUse**: Type): [IStiGeomInteraction](../Chart/IStiGeomInteraction.md)

Returns IStiGeomInteraction object for specified chart at specified x and y location.

**Parameters**

- **chart** ([StiChart](../Chart/StiChart.md))  
- **chartRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **x** (float)  
- **y** (float)  
- **chartGeom** (StiCellGeom)  
- **zoom** (float)  
- **typeNotUse** (Type)  

**Returns** [IStiGeomInteraction](../Chart/IStiGeomInteraction.md)


---

#### ProcessChart `static`

**ProcessChart**(**masterChart**: [StiChart](../Chart/StiChart.md), **childChart**: [StiChart](../Chart/StiChart.md)): void

**Parameters**

- **masterChart** ([StiChart](../Chart/StiChart.md))  
- **childChart** ([StiChart](../Chart/StiChart.md))  


---

#### ResetChartGeomCache `static`

**ResetChartGeomCache**(): void

Resets all chart geom cache settings.

