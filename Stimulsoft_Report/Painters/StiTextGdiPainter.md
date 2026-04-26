---
title: "StiTextGdiPainter Class"
---

## StiTextGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsThumbnailsMode** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **Paint** | void |  |
| **PaintBackground** *(+1 overloads)* | void |  |
| **PaintBorder** | void |  |
| **PaintIndicator** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **PaintLinesOfUnderlining** | void |  |
| **PaintOneLineOfUnderline** | void |  |
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

**PaintBackground**(**text**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **text** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

---

**PaintBackground**(**text**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **paintExtendedMargins**: bool): void

**Parameters**

- **text** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **paintExtendedMargins** (bool)  


---

#### PaintBorder

**PaintBorder**(**text**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **drawBorderFormatting**: bool, **drawTopmostBorderSides**: bool): void

**Parameters**

- **text** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **drawBorderFormatting** (bool)  
- **drawTopmostBorderSides** (bool)  


---

#### PaintIndicator

**PaintIndicator**(**textComp**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **textComp** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### PaintLinesOfUnderlining

**PaintLinesOfUnderlining**(**text**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **text** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintOneLineOfUnderline

**PaintOneLineOfUnderline**(**text**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **x1**: double, **x2**: double, **y**: double): void

**Parameters**

- **text** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md))  
- **x1** (double)  
- **x2** (double)  
- **y** (double)  


---

#### PaintText

**PaintText**(**textComp**: StiText, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **textComp** (StiText)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

