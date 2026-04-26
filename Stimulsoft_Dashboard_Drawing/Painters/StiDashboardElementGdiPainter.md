---
title: "StiDashboardElementGdiPainter Class"
---

## StiDashboardElementGdiPainter Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters`

### Inheritance

Inherits from: StiPageGdiPainter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDashboardGridDotsColor** | Color |  |
| **GetDashboardGridLinesColor** | Color |  |
| **GetSelectionBackgroundColor** | Color |  |
| **GetSelectionBorderColor** | Color |  |
| **GetSelectionCornerColor** | Color |  |
| **GetTableLinesColor** | Color |  |
| **PaintBackground** | void |  |
| **PaintBorder** | void |  |
| **PaintContentBorder** | void |  |
| **PaintGridDots** | void |  |
| **PaintGridLines** | void |  |
| **PaintTopWatermark** | void |  |
| **PaintWatermark** | void |  |

---

### Method Details

#### GetDashboardGridDotsColor

**GetDashboardGridDotsColor**(**page**: StiPage): Color

**Parameters**

- **page** (StiPage)  

**Returns** Color


---

#### GetDashboardGridLinesColor

**GetDashboardGridLinesColor**(**page**: StiPage): Color

**Parameters**

- **page** (StiPage)  

**Returns** Color


---

#### GetSelectionBackgroundColor

**GetSelectionBackgroundColor**(**page**: StiPage): Color

**Parameters**

- **page** (StiPage)  

**Returns** Color


---

#### GetSelectionBorderColor

**GetSelectionBorderColor**(**page**: StiPage): Color

**Parameters**

- **page** (StiPage)  

**Returns** Color


---

#### GetSelectionCornerColor

**GetSelectionCornerColor**(**page**: StiPage): Color

**Parameters**

- **page** (StiPage)  

**Returns** Color


---

#### GetTableLinesColor

**GetTableLinesColor**(**page**: StiPage): Color

**Parameters**

- **page** (StiPage)  

**Returns** Color


---

#### PaintBackground

**PaintBackground**(**e**: StiPaintEventArgs, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **page**: StiPage, **width**: double, **height**: double): void

**Parameters**

- **e** (StiPaintEventArgs)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **page** (StiPage)  
- **width** (double)  
- **height** (double)  


---

#### PaintBorder

**PaintBorder**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **zoom**: float, **drawBorderFormatting**: bool, **drawBorderSides**: bool): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **zoom** (float)  
- **drawBorderFormatting** (bool)  
- **drawBorderSides** (bool)  


---

#### PaintContentBorder

**PaintContentBorder**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **page**: StiPage, **width**: double, **height**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **page** (StiPage)  
- **width** (double)  
- **height** (double)  


---

#### PaintGridDots

**PaintGridDots**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **page**: StiPage, **width**: double, **height**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **page** (StiPage)  
- **width** (double)  
- **height** (double)  


---

#### PaintGridLines

**PaintGridLines**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **page**: StiPage, **width**: double, **height**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **page** (StiPage)  
- **width** (double)  
- **height** (double)  


---

#### PaintTopWatermark

**PaintTopWatermark**(**page**: StiPage, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **printerMargins**: RectangleF): void

**Parameters**

- **page** (StiPage)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **printerMargins** (RectangleF)  


---

#### PaintWatermark

**PaintWatermark**(**page**: StiPage, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **isBehind**: bool): void

**Parameters**

- **page** (StiPage)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **isBehind** (bool)  

