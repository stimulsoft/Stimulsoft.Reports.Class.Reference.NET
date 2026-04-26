---
title: "StiTextInCellsGdiPainter Class"
---

## StiTextInCellsGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiTextGdiPainter](StiTextGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **PaintBackground** | void |  |
| **PaintBorder** | void |  |
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

#### PaintBackground

**PaintBackground**(**textComp**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **textComp** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintBorder

**PaintBorder**(**textComp**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **drawBorderFormatting**: bool, **drawTopmostBorderSides**: bool): void

**Parameters**

- **textComp** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **drawBorderFormatting** (bool)  
- **drawTopmostBorderSides** (bool)  


---

#### PaintText

**PaintText**(**textComp**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **textComp** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

