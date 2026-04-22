---
title: "Bitmap Class"
---

## Bitmap Class

**Namespace:** `Stimulsoft.Drawing`  
**Assembly:** `Stimulsoft.Drawing`

```csharp
public sealed class Bitmap
```

### Inheritance

Implements: [Image](Image.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **Bitmap**(Stream stream) |  |
| **Bitmap**([Bitmap](Bitmap.md) bitmap) |  |
| **Bitmap**([Image](Image.md) image) |  |
| **Bitmap**(int width, int height) |  |
| **Bitmap**(int width, int height, System.Drawing.Imaging.PixelFormat format) |  |
| **Bitmap**(int width, int height, [Graphics](Graphics.md) g) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetPixel** | Color |  |
| **GetThumbnailImage** | [Bitmap](Bitmap.md) |  |
| **LockBits** | [BitmapData](Imaging/BitmapData.md) |  |
| **MakeTransparent** *(+1 overloads)* | void |  |
| **SetPixel** | void |  |
| **SetResolution** | void |  |
| **UnlockBits** | void |  |
