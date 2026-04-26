---
title: "StiXAxisCoreXF Class"
---

## StiXAxisCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAxisCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiXAxisCoreXF**(IStiAxis axis) |  |

**StiXAxisCoreXF**(**axis**: IStiAxis)

**Parameters**

- **axis** (IStiAxis)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCenterAxisRect** | RectangleF |  |
| **GetStartFromZero** | bool |  |
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

#### GetStartFromZero

**GetStartFromZero**(): bool

**Returns** bool


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

**RenderScrollBar**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **axisRect**: RectangleF, **axisGeom**: [StiXAxisViewGeom](StiXAxisViewGeom.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **axisRect** (RectangleF)  
- **axisGeom** ([StiXAxisViewGeom](StiXAxisViewGeom.md))  


---

#### RenderView

**RenderView**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom

