---
title: "StiMetafileConverter Class"
---

## StiMetafileConverter Class

**Namespace:** `Stimulsoft.Base.Drawing`

Class realize methods for conversion Metafile to string and string to Metafile.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BytesToMetafile** `static` | [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md) | Convert Bytes to Metafile. |
| **MetafileToBitmap** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) | Converts metafile to bitmap. |
| **MetafileToBitmapBytes** `static` | byte[] | Converts metafile to bitmap bytes. |
| **MetafileToBytes** `static` | byte[] | Convert Metafile to Bytes. |
| **MetafileToPngBytes** `static` *(+1 overloads)* | byte[] | Converts metafile to bitmap in png format with specified size. |
| **MetafileToString** `static` | string | Convert Metafile to String. |
| **StringToMetafile** `static` | [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md) | Convert String to Metafile. |

---

### Method Details

#### BytesToMetafile `static`

**BytesToMetafile**(****: bytebytes): [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)

Convert Bytes to Metafile.

**Parameters**

- **** (bytebytes)  

**Returns** [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)


---

#### MetafileToBitmap `static`

**MetafileToBitmap**(****: bytemetafileBytes, **bitmapWidth**: int, **bitmapHeight**: int): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Converts metafile to bitmap.

**Parameters**

- **** (bytemetafileBytes)  
- **bitmapWidth** (int)  
- **bitmapHeight** (int)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

---

**MetafileToBitmap**(**metafile**: [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md), **bitmapWidth**: int, **bitmapHeight**: int): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Converts metafile to bitmap with specified size.

**Parameters**

- **metafile** ([Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md))  
- **bitmapWidth** (int)  
- **bitmapHeight** (int)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### MetafileToBitmapBytes `static`

**MetafileToBitmapBytes**(****: bytemetafileBytes, **bitmapWidth**: int, **bitmapHeight**: int): byte[]

Converts metafile to bitmap bytes.

**Parameters**

- **** (bytemetafileBytes)  
- **bitmapWidth** (int)  
- **bitmapHeight** (int)  

**Returns** byte[]


---

#### MetafileToBytes `static`

**MetafileToBytes**(**metafile**: [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)): byte[]

Convert Metafile to Bytes.

**Parameters**

- **metafile** ([Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md))  

**Returns** byte[]


---

#### MetafileToPngBytes `static`

**MetafileToPngBytes**(****: bytemetafileBytes, **bitmapWidth**: int, **bitmapHeight**: int): byte[]

Converts metafile to bitmap in png format with specified size.

**Parameters**

- **** (bytemetafileBytes)  
- **bitmapWidth** (int)  
- **bitmapHeight** (int)  

**Returns** byte[]

---

**MetafileToPngBytes**(**metafile**: [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md), **bitmapWidth**: int, **bitmapHeight**: int): byte[]

Converts metafile to bitmap in png format with specified size.

**Parameters**

- **metafile** ([Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md))  
- **bitmapWidth** (int)  
- **bitmapHeight** (int)  

**Returns** byte[]


---

#### MetafileToString `static`

**MetafileToString**(**metafile**: [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)): string

Convert Metafile to String.

**Parameters**

- **metafile** ([Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)) — Metafile for converting.  

**Returns** string — Result string.


---

#### StringToMetafile `static`

**StringToMetafile**(**str**: string): [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)

Convert String to Metafile.

**Parameters**

- **str** (string)  

**Returns** [Metafile](../../Stimulsoft_Drawing/Imaging/Metafile.md)

