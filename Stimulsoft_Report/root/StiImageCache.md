---
title: "StiImageCache Class"
---

## StiImageCache Class

**Namespace:** `Stimulsoft.Report`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiImageCache**(bool useImageComparer) |  |
| **StiImageCache**(bool useImageComparer, [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md) imageFormat, float imageQuality) | ImageCache initialization |
| **StiImageCache**(bool useImageComparer, [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md) imageFormat, float imageQuality, bool useImageTransparency, int paletteSize) | ImageCache initialization |

**StiImageCache**(**useImageComparer**: bool)

**Parameters**

- **useImageComparer** (bool)  

---

**StiImageCache**(**useImageComparer**: bool, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md), **imageQuality**: float)

ImageCache initialization

**Parameters**

- **useImageComparer** (bool) — Allow use image comparer  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)) — Image format to save  
- **imageQuality** (float) — Quality of Jpeg compression; from 0.0 to 1.0  

---

**StiImageCache**(**useImageComparer**: bool, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md), **imageQuality**: float, **useImageTransparency**: bool, **paletteSize**: int)

ImageCache initialization

**Parameters**

- **useImageComparer** (bool) — Allow use image comparer  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)) — Image format to save  
- **imageQuality** (float) — Quality of Jpeg compression; from 0.0 to 1.0  
- **useImageTransparency** (bool) — Allow use image transparency  
- **paletteSize** (int)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ImageFormatStore** | List<[ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)> |  |
| **ImageIndex** | ArrayList |  |
| **ImageMaskStore** | ArrayList |  |
| **ImagePackedStore** | ArrayList |  |
| **ImagePaletteStore** | ArrayList |  |
| **ImageStore** | ArrayList |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddImageInt** *(+2 overloads)* | int |  |
| **Clear** | void |  |

---

### Method Details

#### AddImageInt

**AddImageInt**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **imageForMask**: [Image](../../Stimulsoft_Drawing/root/Image.md)): int

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **imageForMask** ([Image](../../Stimulsoft_Drawing/root/Image.md))  

**Returns** int

---

**AddImageInt**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **imageQuality**: float, **imageForMask**: [Image](../../Stimulsoft_Drawing/root/Image.md)): int

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **imageQuality** (float)  
- **imageForMask** ([Image](../../Stimulsoft_Drawing/root/Image.md))  

**Returns** int

---

**AddImageInt**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md), **imageForMask**: [Image](../../Stimulsoft_Drawing/root/Image.md)): int

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md))  
- **imageForMask** ([Image](../../Stimulsoft_Drawing/root/Image.md))  

**Returns** int


---

#### Clear

**Clear**(): void

