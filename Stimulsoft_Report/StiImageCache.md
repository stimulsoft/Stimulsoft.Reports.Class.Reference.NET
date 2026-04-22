---
title: "StiImageCache Class"
---

## StiImageCache Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiImageCache
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiImageCache**(bool useImageComparer) |  |
| **StiImageCache**(bool useImageComparer, [ImageFormat](../Stimulsoft_Drawing/Imaging/ImageFormat.md) imageFormat, float imageQuality) | ImageCache initialization |
| **StiImageCache**(bool useImageComparer, [ImageFormat](../Stimulsoft_Drawing/Imaging/ImageFormat.md) imageFormat, float imageQuality, bool useImageTransparency, int paletteSize) | ImageCache initialization |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ImageFormatStore** | List<[ImageFormat](../Stimulsoft_Drawing/Imaging/ImageFormat.md)> |  |
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
