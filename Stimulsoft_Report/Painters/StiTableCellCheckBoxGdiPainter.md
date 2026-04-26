---
title: "StiTableCellCheckBoxGdiPainter Class"
---

## StiTableCellCheckBoxGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **Paint** | void |  |
| **PaintCheck** `static` | void |  |
| **PaintSelection** | void |  |

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

#### PaintCheck `static`

**PaintCheck**(**checkBox**: StiTableCellCheckBox, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **zoom**: float): void

**Parameters**

- **checkBox** (StiTableCellCheckBox)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **zoom** (float)  


---

#### PaintSelection

**PaintSelection**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  

