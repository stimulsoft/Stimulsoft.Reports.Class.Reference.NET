---
title: "StiPdfImageCache Class"
---

## StiPdfImageCache Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfImageCache**() |  |

**StiPdfImageCache**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **GetImageInfo** | StiGdiImageInfo |  |
| **GetImageInfo2** | StiGdiImageInfo |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### GetImageInfo

**GetImageInfo**(**stiImage**: StiImage, **dispose**: bool, **rotation**: [StiImageRotation](../Components/StiImageRotation.md), **svgFlags**: int, **resolution**: float): StiGdiImageInfo

**Parameters**

- **stiImage** (StiImage)  
- **dispose** (bool)  
- **rotation** ([StiImageRotation](../Components/StiImageRotation.md))  
- **svgFlags** (int)  
- **resolution** (float)  

**Returns** StiGdiImageInfo


---

#### GetImageInfo2

**GetImageInfo2**(**stiImage**: StiImage, **baseInfo**: StiGdiImageInfo, **resolution**: float): StiGdiImageInfo

**Parameters**

- **stiImage** (StiImage)  
- **baseInfo** (StiGdiImageInfo)  
- **resolution** (float)  

**Returns** StiGdiImageInfo

