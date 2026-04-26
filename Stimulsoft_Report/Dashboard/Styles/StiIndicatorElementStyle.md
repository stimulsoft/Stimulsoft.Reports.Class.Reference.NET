---
title: "StiIndicatorElementStyle Class"
---

## StiIndicatorElementStyle Class

**Namespace:** `Stimulsoft.Report.Dashboard.Styles`

### Inheritance

Inherits from: [StiElementStyle](StiElementStyle.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BackColor** | Color |  |
| **ForeColor** | Color |  |
| **GlyphColor** | Color |  |
| **HotBackColor** | Color |  |
| **LocalizedName** | string |  |
| **NegativeColor** | Color |  |
| **PositiveColor** | Color |  |
| **ToolTipBorder** | [StiSimpleBorder](../../../Stimulsoft_Base/Drawing/StiSimpleBorder.md) |  |
| **ToolTipBrush** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ToolTipCornerRadius** | StiCornerRadius |  |
| **ToolTipTextBrush** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawStyleForGallery** | void |  |
| **GetGalleryBackColor** | Color |  |
| **GetGalleryForeColor** | Color |  |

---

### Method Details

#### DrawStyleForGallery

**DrawStyleForGallery**(**g**: [Graphics](../../../Stimulsoft_Drawing/root/Graphics.md), **rect**: Rectangle, **indicatorFontIcons**: [StiFontIcons](../../../Stimulsoft_Base/Stimulsoft/Report/Helpers/StiFontIcons.md), **isDashboard**: bool, **isFormUI**: bool): void

**Parameters**

- **g** ([Graphics](../../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (Rectangle)  
- **indicatorFontIcons** ([StiFontIcons](../../../Stimulsoft_Base/Stimulsoft/Report/Helpers/StiFontIcons.md))  
- **isDashboard** (bool)  
- **isFormUI** (bool)  


---

#### GetGalleryBackColor

**GetGalleryBackColor**(): Color

**Returns** Color


---

#### GetGalleryForeColor

**GetGalleryForeColor**(): Color

**Returns** Color

