---
title: "StiYAxisGeom Class"
---

## StiYAxisGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiYAxisGeom**([IStiYAxis](IStiYAxis.md) axis, RectangleF clientRectangle, bool isCenterAxis) |  |

**StiYAxisGeom**(**axis**: [IStiYAxis](IStiYAxis.md), **clientRectangle**: RectangleF, **isCenterAxis**: bool)

**Parameters**

- **axis** ([IStiYAxis](IStiYAxis.md))  
- **clientRectangle** (RectangleF)  
- **isCenterAxis** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AllowChildDrawing** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |
| **DrawArrow** | void |  |

---

### Method Details

#### AllowChildDrawing

**AllowChildDrawing**(**cellGeom**: StiCellGeom): bool

**Parameters**

- **cellGeom** (StiCellGeom)  

**Returns** bool


---

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws area geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### DrawArrow

**DrawArrow**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

