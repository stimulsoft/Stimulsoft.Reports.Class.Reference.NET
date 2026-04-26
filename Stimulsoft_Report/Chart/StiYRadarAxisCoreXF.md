---
title: "StiYRadarAxisCoreXF Class"
---

## StiYRadarAxisCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiRadarAxisCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiYRadarAxisCoreXF**(IStiRadarAxis axis) |  |

**StiYRadarAxisCoreXF**(**axis**: IStiRadarAxis)

**Parameters**

- **axis** (IStiRadarAxis)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **GetAxisRect** | RectangleF |  |
| **Render** | StiCellGeom |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle): void

**Parameters**

- **style** (IStiChartStyle)  


---

#### GetAxisRect

**GetAxisRect**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **includeAxisArrow**: bool, **includeLabelsHeight**: bool, **isDrawing**: bool): RectangleF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **includeAxisArrow** (bool)  
- **includeLabelsHeight** (bool)  
- **isDrawing** (bool)  

**Returns** RectangleF


---

#### Render

**Render**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom

