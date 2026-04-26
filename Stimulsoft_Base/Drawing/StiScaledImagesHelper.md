---
title: "StiScaledImagesHelper Class"
---

## StiScaledImagesHelper Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetImageFromResources** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **GetNearestImageFromResourcesAndResize** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |

---

### Method Details

#### GetImage `static`

**GetImage**(**assembly**: Assembly, **path**: string, **size**: [StiImageSize](../root/StiImageSize.md), **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **assembly** (Assembly)  
- **path** (string)  
- **size** ([StiImageSize](../root/StiImageSize.md))  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetImageFromResources `static`

**GetImageFromResources**(**assembly**: Assembly, **path**: string, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **assembly** (Assembly)  
- **path** (string)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### GetNearestImageFromResourcesAndResize `static`

**GetNearestImageFromResourcesAndResize**(**assembly**: Assembly, **path**: string, **canvasSize**: int): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **assembly** (Assembly)  
- **path** (string)  
- **canvasSize** (int)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

