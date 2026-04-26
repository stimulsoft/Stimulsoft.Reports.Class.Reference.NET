---
title: "StiViewGdiPainter Class"
---

## StiViewGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **Paint** | void |  |
| **PaintImage** | void |  |
| **RotateImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |

---

### Method Details

#### GetImage

**GetImage**(**component**: StiComponent, **zoom**: float, **format**: [StiExportFormat](../root/StiExportFormat.md)): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **component** (StiComponent)  
- **zoom** (float)  
- **format** ([StiExportFormat](../root/StiExportFormat.md))  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### Paint

**Paint**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintImage

**PaintImage**(**view**: StiView, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **view** (StiView)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### RotateImage

**RotateImage**(**gdiImage**: [Image](../../Stimulsoft_Drawing/root/Image.md), **viewComp**: StiView): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **gdiImage** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **viewComp** (StiView)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)

