---
title: "StiConstantLinesVerticalGeom Class"
---

## StiConstantLinesVerticalGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiConstantLinesVerticalGeom**(IStiConstantLines line, RectangleF clientRectangle, PointF point, [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md) mode) |  |

**StiConstantLinesVerticalGeom**(**line**: IStiConstantLines, **clientRectangle**: RectangleF, **point**: PointF, **mode**: [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md))

**Parameters**

- **line** (IStiConstantLines)  
- **clientRectangle** (RectangleF)  
- **point** (PointF)  
- **mode** ([StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Line** | IStiConstantLines |  |
| **Mode** | [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md) |  |
| **Point** | PointF |  |

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

