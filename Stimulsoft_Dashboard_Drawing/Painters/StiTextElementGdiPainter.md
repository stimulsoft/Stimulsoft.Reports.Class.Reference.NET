---
title: "StiTextElementGdiPainter Class"
---

## StiTextElementGdiPainter Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters`

### Inheritance

Inherits from: [StiAtomElementGdiPainter](StiAtomElementGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IsDefined** | bool |  |
| **PaintAtom** | void |  |
| **PaintNoResult** | void |  |
| **PaintNotDefined** | void |  |

---

### Method Details

#### IsDefined

**IsDefined**(**component**: StiComponent): bool

**Parameters**

- **component** (StiComponent)  

**Returns** bool


---

#### PaintAtom

**PaintAtom**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintNoResult

**PaintNoResult**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **zoom** (double?)  


---

#### PaintNotDefined

**PaintNotDefined**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **zoom** (double?)  

