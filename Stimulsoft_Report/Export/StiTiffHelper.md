---
title: "StiTiffHelper Class"
---

## StiTiffHelper Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **MakeMonochromeImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) | Make monochrome image (1 bit per plane) from normal 32bit image |

---

### Method Details

#### MakeMonochromeImage `static`

**MakeMonochromeImage**(**inputImage**: [Image](../../Stimulsoft_Drawing/root/Image.md), **ditheringType**: [StiMonochromeDitheringType](StiMonochromeDitheringType.md), **diffusionPower**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

Make monochrome image (1 bit per plane) from normal 32bit image

**Parameters**

- **inputImage** ([Image](../../Stimulsoft_Drawing/root/Image.md)) — Input image 32bit  
- **ditheringType** ([StiMonochromeDitheringType](StiMonochromeDitheringType.md)) — Dithering type (None, FloydSteinberg or Ordered)  
- **diffusionPower** (int) — Power of diffusion, from 1 to 255; default value is 128  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md) — Monochrome image

