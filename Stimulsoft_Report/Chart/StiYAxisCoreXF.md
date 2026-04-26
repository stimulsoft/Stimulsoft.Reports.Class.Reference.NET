---
title: "StiYAxisCoreXF Class"
---

## StiYAxisCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAxisCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiYAxisCoreXF**(IStiAxis axis) |  |

**StiYAxisCoreXF**(**axis**: IStiAxis)

**Parameters**

- **axis** (IStiAxis)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCenterAxisRect** | RectangleF |  |
| **Render** | StiCellGeom |  |
| **RenderCenter** | StiCellGeom |  |
| **RenderCenterView** | StiCellGeom |  |
| **RenderScrollBar** | void |  |
| **RenderView** | StiCellGeom |  |

---

### Method Details

#### GetCenterAxisRect

**GetCenterAxisRect**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **includeAxisArrow**: bool, **includeLabelsHeight**: bool, **isDrawing**: bool): RectangleF

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


---

#### RenderCenter

**RenderCenter**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom


---

#### RenderCenterView

**RenderCenterView**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom


---

#### RenderScrollBar

**RenderScrollBar**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **axisRect**: RectangleF, **axisGeom**: [StiYAxisViewGeom](StiYAxisViewGeom.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **axisRect** (RectangleF)  
- **axisGeom** ([StiYAxisViewGeom](StiYAxisViewGeom.md))  


---

#### RenderView

**RenderView**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom

