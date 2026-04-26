---
title: "ImageAttributes Class"
---

## ImageAttributes Class

**Namespace:** `Stimulsoft.Drawing.Imaging`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **ImageAttributes**() |  |

**ImageAttributes**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **SetColorKey** | void |  |
| **SetColorMatrix** *(+1 overloads)* | void |  |
| **SetRemapTable** | void |  |
| **SetWrapMode** | void |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### SetColorKey

**SetColorKey**(**colorLow**: Color, **colorHigh**: Color): void

**Parameters**

- **colorLow** (Color)  
- **colorHigh** (Color)  


---

#### SetColorMatrix

**SetColorMatrix**(**newColorMatrix**: [ColorMatrix](ColorMatrix.md)): void

**Parameters**

- **newColorMatrix** ([ColorMatrix](ColorMatrix.md))  

---

**SetColorMatrix**(**newColorMatrix**: [ColorMatrix](ColorMatrix.md), **flags**: System.Drawing.Imaging.ColorMatrixFlag, **type**: System.Drawing.Imaging.ColorAdjustType): void

**Parameters**

- **newColorMatrix** ([ColorMatrix](ColorMatrix.md))  
- **flags** (System.Drawing.Imaging.ColorMatrixFlag)  
- **type** (System.Drawing.Imaging.ColorAdjustType)  


---

#### SetRemapTable

**SetRemapTable**(****: System.Drawing.Imaging.ColorMapmap): void

**Parameters**

- **** (System.Drawing.Imaging.ColorMapmap)  


---

#### SetWrapMode

**SetWrapMode**(**mode**: WrapMode): void

**Parameters**

- **mode** (WrapMode)  

