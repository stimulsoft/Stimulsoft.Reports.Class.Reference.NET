---
title: "StiChartGdiPainter Class"
---

## StiChartGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawChart** | void |  |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **Paint** | void |  |
| **PaintChart** | void |  |

---

### Method Details

#### DrawChart

**DrawChart**(**chart**: [StiChart](../Chart/StiChart.md), **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **useMargins**: bool, **useBackground**: bool, **zoom**: double?): void

**Parameters**

- **chart** ([StiChart](../Chart/StiChart.md))  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **useMargins** (bool)  
- **useBackground** (bool)  
- **zoom** (double?)  


---

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

#### PaintChart

**PaintChart**(**chart**: [StiChart](../Chart/StiChart.md), **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **drawBorder**: bool, **drawFormatting**: bool): void

**Parameters**

- **chart** ([StiChart](../Chart/StiChart.md))  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **drawBorder** (bool)  
- **drawFormatting** (bool)  

