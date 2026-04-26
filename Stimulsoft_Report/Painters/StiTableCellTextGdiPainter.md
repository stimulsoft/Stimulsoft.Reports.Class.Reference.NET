---
title: "StiTableCellTextGdiPainter Class"
---

## StiTableCellTextGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **Paint** | void |  |
| **PaintBackground** | void |  |
| **PaintBorder** | void |  |
| **PaintLinesOfUnderlining** | void |  |
| **PaintOneLineOfUnderline** | void |  |
| **PaintSelection** | void |  |
| **PaintText** | void |  |

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

#### PaintBackground

**PaintBackground**(**text**: StiTableCell, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **text** (StiTableCell)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintBorder

**PaintBorder**(**text**: StiTableCell, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **drawBorderFormatting**: bool, **drawTopmostBorderSides**: bool): void

**Parameters**

- **text** (StiTableCell)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **drawBorderFormatting** (bool)  
- **drawTopmostBorderSides** (bool)  


---

#### PaintLinesOfUnderlining

**PaintLinesOfUnderlining**(**text**: StiTableCell, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **text** (StiTableCell)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintOneLineOfUnderline

**PaintOneLineOfUnderline**(**text**: StiTableCell, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **x1**: double, **x2**: double, **y**: double): void

**Parameters**

- **text** (StiTableCell)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md))  
- **x1** (double)  
- **x2** (double)  
- **y** (double)  


---

#### PaintSelection

**PaintSelection**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintText

**PaintText**(**textComp**: StiTableCell, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **textComp** (StiTableCell)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

