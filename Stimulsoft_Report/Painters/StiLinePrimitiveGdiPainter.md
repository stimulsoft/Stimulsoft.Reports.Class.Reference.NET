---
title: "StiLinePrimitiveGdiPainter Class"
---

## StiLinePrimitiveGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddDotToPath** | void |  |
| **CheckRectForOverflow** | void |  |
| **DrawDot** | void |  |
| **PaintHighlight** | void |  |

---

### Method Details

#### AddDotToPath

**AddDotToPath**(**path**: [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md), **x**: double, **y**: double, **size**: float): void

**Parameters**

- **path** ([GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md))  
- **x** (double)  
- **y** (double)  
- **size** (float)  


---

#### CheckRectForOverflow

**CheckRectForOverflow**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### DrawDot

**DrawDot**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **x**: double, **y**: double, **size**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md))  
- **x** (double)  
- **y** (double)  
- **size** (float)  


---

#### PaintHighlight

**PaintHighlight**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  

