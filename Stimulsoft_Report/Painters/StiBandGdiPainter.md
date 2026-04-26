---
title: "StiBandGdiPainter Class"
---

## StiBandGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiContainerGdiPainter](StiContainerGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Paint** | void |  |
| **PaintBandContent** | void |  |
| **PaintBandHeader** | void |  |
| **PaintColumns** | void | Paints the columns. |
| **PaintDataBandColumns** | void |  |
| **PaintDataBandHeader** | void |  |
| **PaintSelection** | void |  |
| **PaintSpecialDockService** | void |  |

---

### Method Details

#### Paint

**Paint**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintBandContent

**PaintBandContent**(**band**: StiBand, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **band** (StiBand)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintBandHeader

**PaintBandHeader**(**band**: StiBand, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **headerRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **band** (StiBand)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **headerRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintColumns

**PaintColumns**(**container**: StiContainer, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

Paints the columns.

**Parameters**

- **container** (StiContainer)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  


---

#### PaintDataBandColumns

**PaintDataBandColumns**(**band**: StiBand, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **band** (StiBand)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### PaintDataBandHeader

**PaintDataBandHeader**(**band**: StiBand, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **headerRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **stringFormat**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md), **font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **band** (StiBand)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **headerRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **stringFormat** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md))  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  


---

#### PaintSelection

**PaintSelection**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintSpecialDockService

**PaintSpecialDockService**(**band**: StiBand, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **headerRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **fullRect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **band** (StiBand)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **headerRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **fullRect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

