---
title: "StiContainerGdiPainter Class"
---

## StiContainerGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Paint** | void |  |
| **PaintBandInteraction** | void |  |
| **PaintColumns** | void |  |
| **PaintComponents** | void | Paints components. |
| **PaintSelectionComponents** | void | Paints selection of components. |

---

### Method Details

#### Paint

**Paint**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintBandInteraction

**PaintBandInteraction**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### PaintColumns

**PaintColumns**(**container**: StiContainer, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **container** (StiContainer)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### PaintComponents

**PaintComponents**(**container**: StiContainer, **e**: StiPaintEventArgs): void

Paints components.

**Parameters**

- **container** (StiContainer)  
- **e** (StiPaintEventArgs) — Argument for painting.  


---

#### PaintSelectionComponents

**PaintSelectionComponents**(**container**: StiContainer, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

Paints selection of components.

**Parameters**

- **container** (StiContainer)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  

