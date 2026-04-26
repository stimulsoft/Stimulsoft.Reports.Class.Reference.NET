---
title: "StiGaugeGdiPainter Class"
---

## StiGaugeGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawGauge** *(+2 overloads)* | void |  |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **Paint** | void |  |

---

### Method Details

#### DrawGauge

**DrawGauge**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **gauge**: StiGauge, **rect**: RectangleF): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **gauge** (StiGauge)  
- **rect** (RectangleF)  

---

**DrawGauge**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **gauge**: StiGauge, **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **gauge** (StiGauge)  
- **rect** (RectangleF)  
- **zoom** (float)  

---

**DrawGauge**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **gauge**: StiGauge, **rect**: RectangleF, **zoom**: float, **isClip**: bool, **drawBorder**: bool): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **gauge** (StiGauge)  
- **rect** (RectangleF)  
- **zoom** (float)  
- **isClip** (bool)  
- **drawBorder** (bool)  


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

