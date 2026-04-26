---
title: "StiGdiGaugeContextPainter Class"
---

## StiGdiGaugeContextPainter Class

**Namespace:** `Stimulsoft.Gauge.Painters`

### Inheritance

Inherits from: [StiGaugeContextPainter](../../../Painters/StiGaugeContextPainter.md)  
Implements: [IStiAnimationContextPainter](../../../Painters/Context/Animation/IStiAnimationContextPainter.md)<[StiGaugeGeom](../../../Gauge/GaugeGeoms/StiGaugeGeom.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGdiGaugeContextPainter**([Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md) g, StiGauge gauge, RectangleF rect, float zoom) |  |

**StiGdiGaugeContextPainter**(**g**: [Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md), **gauge**: StiGauge, **rect**: RectangleF, **zoom**: float)

**Parameters**

- **g** ([Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md))  
- **gauge** (StiGauge)  
- **rect** (RectangleF)  
- **zoom** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AnimationEngine** | [StiAnimationEngine](../../../Painters/Context/Animation/StiAnimationEngine.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **MeasureString** | SizeF |  |
| **Render** | void |  |

---

### Method Details

#### MeasureString

**MeasureString**(**text**: string, **font**: [Font](../../../../Stimulsoft_Drawing/root/Font.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](../../../../Stimulsoft_Drawing/root/Font.md))  

**Returns** SizeF


---

#### Render

**Render**(): void

