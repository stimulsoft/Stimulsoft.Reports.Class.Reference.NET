---
title: "Bitmap Class"
---

## Bitmap Class

**Namespace:** `Stimulsoft.Drawing`

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

**Bitmap**(**stream**: Stream)

**Parameters**

- **stream** (Stream)  

---

**Bitmap**(**bitmap**: [Bitmap](Bitmap.md))

**Parameters**

- **bitmap** ([Bitmap](Bitmap.md))  

---

**Bitmap**(**image**: [Image](Image.md))

**Parameters**

- **image** ([Image](Image.md))  

---

**Bitmap**(**width**: int, **height**: int)

**Parameters**

- **width** (int)  
- **height** (int)  

---

**Bitmap**(**width**: int, **height**: int, **format**: System.Drawing.Imaging.PixelFormat)

**Parameters**

- **width** (int)  
- **height** (int)  
- **format** (System.Drawing.Imaging.PixelFormat)  

---

**Bitmap**(**width**: int, **height**: int, **g**: [Graphics](Graphics.md))

**Parameters**

- **width** (int)  
- **height** (int)  
- **g** ([Graphics](Graphics.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetPixel** | Color |  |
| **GetThumbnailImage** | [Bitmap](Bitmap.md) |  |
| **LockBits** | [BitmapData](../Imaging/BitmapData.md) |  |
| **MakeTransparent** *(+1 overloads)* | void |  |
| **SetPixel** | void |  |
| **SetResolution** | void |  |
| **UnlockBits** | void |  |

---

### Method Details

#### GetPixel

**GetPixel**(**x**: int, **y**: int): Color

**Parameters**

- **x** (int)  
- **y** (int)  

**Returns** Color


---

#### GetThumbnailImage

**GetThumbnailImage**(**width**: int, **height**: int, **callback**: object, **callbackData**: IntPtr): [Bitmap](Bitmap.md)

**Parameters**

- **width** (int)  
- **height** (int)  
- **callback** (object)  
- **callbackData** (IntPtr)  

**Returns** [Bitmap](Bitmap.md)


---

#### LockBits

**LockBits**(**rect**: Rectangle, **readWrite**: System.Drawing.Imaging.ImageLockMode, **format32bppArgb**: System.Drawing.Imaging.PixelFormat): [BitmapData](../Imaging/BitmapData.md)

**Parameters**

- **rect** (Rectangle)  
- **readWrite** (System.Drawing.Imaging.ImageLockMode)  
- **format32bppArgb** (System.Drawing.Imaging.PixelFormat)  

**Returns** [BitmapData](../Imaging/BitmapData.md)


---

#### MakeTransparent

**MakeTransparent**(): void

---

**MakeTransparent**(**transparentColor**: Color): void

**Parameters**

- **transparentColor** (Color)  


---

#### SetPixel

**SetPixel**(**x**: int, **y**: int, **color**: Color): void

**Parameters**

- **x** (int)  
- **y** (int)  
- **color** (Color)  


---

#### SetResolution

**SetResolution**(**horizontalResolution**: float, **verticalResolution**: float): void

**Parameters**

- **horizontalResolution** (float)  
- **verticalResolution** (float)  


---

#### UnlockBits

**UnlockBits**(**bits**: [BitmapData](../Imaging/BitmapData.md)): void

**Parameters**

- **bits** ([BitmapData](../Imaging/BitmapData.md))  

