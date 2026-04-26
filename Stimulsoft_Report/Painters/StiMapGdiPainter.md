---
title: "StiMapGdiPainter Class"
---

## StiMapGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UseBackground** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawMap** | void |  |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetScaleImage** | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **Paint** | void |  |
| **PaintOnlineMap** | void |  |

---

### Method Details

#### DrawMap

**DrawMap**(**map**: StiMap, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **drawBorder**: bool, **drawFormatting**: bool, **useZoom**: bool): void

**Parameters**

- **map** (StiMap)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **drawBorder** (bool)  
- **drawFormatting** (bool)  
- **useZoom** (bool)  


---

#### GetImage

**GetImage**(**component**: StiComponent, **zoom**: float, **format**: [StiExportFormat](../root/StiExportFormat.md)): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **component** (StiComponent)  
- **zoom** (float)  
- **format** ([StiExportFormat](../root/StiExportFormat.md))  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetScaleImage

**GetScaleImage**(**component**: StiComponent): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **component** (StiComponent)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### Paint

**Paint**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintOnlineMap

**PaintOnlineMap**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **map**: StiMap): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **map** (StiMap)  

