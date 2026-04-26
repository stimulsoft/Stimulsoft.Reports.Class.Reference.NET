---
title: "StiAxisAreaGeom Class"
---

## StiAxisAreaGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiAreaGeom](StiAreaGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxisAreaGeom**([StiAxisAreaViewGeom](StiAxisAreaViewGeom.md) view, IStiArea area, RectangleF clientRectangle) |  |

**StiAxisAreaGeom**(**view**: [StiAxisAreaViewGeom](StiAxisAreaViewGeom.md), **area**: IStiArea, **clientRectangle**: RectangleF)

**Parameters**

- **view** ([StiAxisAreaViewGeom](StiAxisAreaViewGeom.md))  
- **area** (IStiArea)  
- **clientRectangle** (RectangleF)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **X1** | float |  |
| **X2** | float |  |
| **Y1** | float |  |
| **Y2** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AllowChildDrawing** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |
| **IsChildVisibleInView** | bool | Returns true if specified child visible in area. |

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

#### IsChildVisibleInView

**IsChildVisibleInView**(**cellGeom**: StiCellGeom): bool

Returns true if specified child visible in area.

**Parameters**

- **cellGeom** (StiCellGeom)  

**Returns** bool

