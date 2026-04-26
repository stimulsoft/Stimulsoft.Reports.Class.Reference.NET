---
title: "StiImageConverter Class"
---

## StiImageConverter Class

**Namespace:** `Stimulsoft.Base.Drawing`

Class realize methods for conversion image to string and string to image.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BytesToImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) | Convert Bytes to Image. |
| **ImageToBytes** `static` | byte[] | Convert Image to Bytes. |
| **ImageToPackedString** `static` | string | Convert Image to packed String. |
| **ImageToString** `static` | string | Convert Image to String. |
| **PackedStringToImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) | Convert packed String to Image. |
| **StringToByteArray** `static` | byte[] |  |
| **StringToImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) | Convert String to Image. |
| **TryBytesToImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |

---

### Method Details

#### BytesToImage `static`

**BytesToImage**(****: bytebytes, **width**: int, **height**: int, **stretch**: bool, **aspectRatio**: bool): [Image](../../Stimulsoft_Drawing/root/Image.md)

Convert Bytes to Image.

**Parameters**

- **** (bytebytes)  
- **width** (int)  
- **height** (int)  
- **stretch** (bool)  
- **aspectRatio** (bool)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### ImageToBytes `static`

**ImageToBytes**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **allowNulls**: bool): byte[]

Convert Image to Bytes.

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md)) — Image for converting.  
- **allowNulls** (bool) — Returns null when image equal to null. Otherwise, return byte[0].  

**Returns** byte[] — Result byte array.


---

#### ImageToPackedString `static`

**ImageToPackedString**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md)): string

Convert Image to packed String.

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md)) — Image for converting.  

**Returns** string — Result string.


---

#### ImageToString `static`

**ImageToString**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **allowNulls**: bool): string

Convert Image to String.

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md)) — Image for converting.  
- **allowNulls** (bool) — Returns null when image equal to null. Otherwise, return byte[0].  

**Returns** string — Result string.


---

#### PackedStringToImage `static`

**PackedStringToImage**(**str**: string): [Image](../../Stimulsoft_Drawing/root/Image.md)

Convert packed String to Image.

**Parameters**

- **str** (string) — String for converting.  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md) — Result Image.


---

#### StringToByteArray `static`

**StringToByteArray**(**str**: string): byte[]

**Parameters**

- **str** (string)  

**Returns** byte[]


---

#### StringToImage `static`

**StringToImage**(**str**: string): [Image](../../Stimulsoft_Drawing/root/Image.md)

Convert String to Image.

**Parameters**

- **str** (string) — String for converting.  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md) — Result Image.


---

#### TryBytesToImage `static`

**TryBytesToImage**(****: bytebytes, **width**: int, **height**: int, **stretch**: bool, **aspectRatio**: bool): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **** (bytebytes)  
- **width** (int)  
- **height** (int)  
- **stretch** (bool)  
- **aspectRatio** (bool)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)

