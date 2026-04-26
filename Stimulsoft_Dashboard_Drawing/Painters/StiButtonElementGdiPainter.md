---
title: "StiButtonElementGdiPainter Class"
---

## StiButtonElementGdiPainter Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters`

### Inheritance

Inherits from: [StiControlElementGdiPainter](StiControlElementGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **PaintBackground** | void |  |
| **PaintButton** `static` | void |  |
| **PaintContent** | void |  |
| **PaintNotEnabled** | void |  |

---

### Method Details

#### PaintBackground

**PaintBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintButton `static`

**PaintButton**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **state**: StiButtonVisualState, **isChecked**: bool, **scale**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **state** (StiButtonVisualState)  
- **isChecked** (bool)  
- **scale** (float)  


---

#### PaintContent

**PaintContent**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintNotEnabled

**PaintNotEnabled**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **zoom** (double?)  

