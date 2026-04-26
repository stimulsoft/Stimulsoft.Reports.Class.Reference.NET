---
title: "StiChartElementInteractionHelper Class"
---

## StiChartElementInteractionHelper Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetInteraction** `static` | [IStiGeomInteraction](../../Stimulsoft_Report/Chart/IStiGeomInteraction.md) | Returns IStiGeomInteraction object for specified chart at specified x and y location. |
| **GetInteractionTooltipAbsolutePoint** `static` | [StiInteractionToolTipPointOptions](../../Stimulsoft_Report/Chart/StiInteractionToolTipPointOptions.md) |  |
| **GetInteractions** `static` | List<[IStiGeomInteraction](../../Stimulsoft_Report/Chart/IStiGeomInteraction.md)> |  |
| **GetSeriesElementGeomsIsSelected** `static` | List<[IStiSeriesElement](../../Stimulsoft_Report/Chart/IStiSeriesElement.md)> |  |
| **ResetChartGeomCache** `static` | void | Resets all chart geom cache settings. |
| **ResetSeriesElementGeomsSelection** `static` | void |  |

---

### Method Details

#### GetInteraction `static`

**GetInteraction**(**chart**: [StiChart](../../Stimulsoft_Report/Chart/StiChart.md), **chartElement**: StiChartElement, **chartRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **x**: float, **y**: float, **chartGeom**: StiCellGeom, **zoom**: float, **typeNotUse**: Type): [IStiGeomInteraction](../../Stimulsoft_Report/Chart/IStiGeomInteraction.md)

Returns IStiGeomInteraction object for specified chart at specified x and y location.

**Parameters**

- **chart** ([StiChart](../../Stimulsoft_Report/Chart/StiChart.md))  
- **chartElement** (StiChartElement)  
- **chartRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **x** (float)  
- **y** (float)  
- **chartGeom** (StiCellGeom)  
- **zoom** (float)  
- **typeNotUse** (Type)  

**Returns** [IStiGeomInteraction](../../Stimulsoft_Report/Chart/IStiGeomInteraction.md)


---

#### GetInteractionTooltipAbsolutePoint `static`

**GetInteractionTooltipAbsolutePoint**(**cellGeom**: StiCellGeom, **chart**: [StiChart](../../Stimulsoft_Report/Chart/StiChart.md), **chartElement**: StiChartElement, **chartRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **zoom**: float): [StiInteractionToolTipPointOptions](../../Stimulsoft_Report/Chart/StiInteractionToolTipPointOptions.md)

**Parameters**

- **cellGeom** (StiCellGeom)  
- **chart** ([StiChart](../../Stimulsoft_Report/Chart/StiChart.md))  
- **chartElement** (StiChartElement)  
- **chartRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **zoom** (float)  

**Returns** [StiInteractionToolTipPointOptions](../../Stimulsoft_Report/Chart/StiInteractionToolTipPointOptions.md)


---

#### GetInteractions `static`

**GetInteractions**(**chart**: [StiChart](../../Stimulsoft_Report/Chart/StiChart.md), **chartElement**: StiChartElement, **chartRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **x**: float, **y**: float, **chartGeom**: StiCellGeom, **zoom**: float, **typeNotUse**: Type): List<[IStiGeomInteraction](../../Stimulsoft_Report/Chart/IStiGeomInteraction.md)>

**Parameters**

- **chart** ([StiChart](../../Stimulsoft_Report/Chart/StiChart.md))  
- **chartElement** (StiChartElement)  
- **chartRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **x** (float)  
- **y** (float)  
- **chartGeom** (StiCellGeom)  
- **zoom** (float)  
- **typeNotUse** (Type)  

**Returns** List<[IStiGeomInteraction](../../Stimulsoft_Report/Chart/IStiGeomInteraction.md)>


---

#### GetSeriesElementGeomsIsSelected `static`

**GetSeriesElementGeomsIsSelected**(**chart**: [StiChart](../../Stimulsoft_Report/Chart/StiChart.md), **chartElement**: StiChartElement, **chartRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **zoom**: float): List<[IStiSeriesElement](../../Stimulsoft_Report/Chart/IStiSeriesElement.md)>

**Parameters**

- **chart** ([StiChart](../../Stimulsoft_Report/Chart/StiChart.md))  
- **chartElement** (StiChartElement)  
- **chartRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **zoom** (float)  

**Returns** List<[IStiSeriesElement](../../Stimulsoft_Report/Chart/IStiSeriesElement.md)>


---

#### ResetChartGeomCache `static`

**ResetChartGeomCache**(): void

Resets all chart geom cache settings.


---

#### ResetSeriesElementGeomsSelection `static`

**ResetSeriesElementGeomsSelection**(**chart**: [StiChart](../../Stimulsoft_Report/Chart/StiChart.md), **chartElement**: StiChartElement, **chartRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **zoom**: float): void

**Parameters**

- **chart** ([StiChart](../../Stimulsoft_Report/Chart/StiChart.md))  
- **chartElement** (StiChartElement)  
- **chartRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **zoom** (float)  

