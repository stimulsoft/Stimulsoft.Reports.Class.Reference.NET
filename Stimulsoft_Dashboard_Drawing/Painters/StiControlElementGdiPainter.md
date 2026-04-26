---
title: "StiControlElementGdiPainter Class"
---

## StiControlElementGdiPainter Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters`

### Inheritance

Inherits from: [StiElementGdiPainter](StiElementGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Format** | string |  |
| **GetBackColor** | Color |  |
| **GetFont** | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **GetForeColor** | Color |  |
| **GetGlyphColor** | Color |  |
| **GetSelectedBackColor** | Color |  |
| **GetSelectedForeColor** | Color |  |
| **GetSeparatorColor** | Color |  |
| **PaintBackground** | void |  |
| **PaintButton** | void |  |
| **PaintCheckBoxTitle** | void |  |

---

### Method Details

#### Format

**Format**(**element**: IStiControlElement, **value**: object): string

**Parameters**

- **element** (IStiControlElement)  
- **value** (object)  

**Returns** string


---

#### GetBackColor

**GetBackColor**(**element**: IStiControlElement): Color

**Parameters**

- **element** (IStiControlElement)  

**Returns** Color


---

#### GetFont

**GetFont**(**element**: IStiControlElement): [Font](../../Stimulsoft_Drawing/root/Font.md)

**Parameters**

- **element** (IStiControlElement)  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md)


---

#### GetForeColor

**GetForeColor**(**element**: IStiControlElement): Color

**Parameters**

- **element** (IStiControlElement)  

**Returns** Color


---

#### GetGlyphColor

**GetGlyphColor**(**element**: IStiControlElement): Color

**Parameters**

- **element** (IStiControlElement)  

**Returns** Color


---

#### GetSelectedBackColor

**GetSelectedBackColor**(**element**: IStiControlElement): Color

**Parameters**

- **element** (IStiControlElement)  

**Returns** Color


---

#### GetSelectedForeColor

**GetSelectedForeColor**(**element**: IStiControlElement): Color

**Parameters**

- **element** (IStiControlElement)  

**Returns** Color


---

#### GetSeparatorColor

**GetSeparatorColor**(**element**: IStiControlElement): Color

**Parameters**

- **element** (IStiControlElement)  

**Returns** Color


---

#### PaintBackground

**PaintBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintButton

**PaintButton**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiControlElement, **scale**: float, **isDown**: bool): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiControlElement)  
- **scale** (float)  
- **isDown** (bool)  


---

#### PaintCheckBoxTitle

**PaintCheckBoxTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  

