---
title: "StiImageHelper Class"
---

## StiImageHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BytesFromFile** `static` | byte[] |  |
| **FromBytes** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **FromFile** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetImageBytesFromObject** `static` | byte[] |  |
| **IsBmp** `static` | bool |  |
| **IsEmf** `static` | bool |  |
| **IsEqualImages** `static` | bool |  |
| **IsGif** `static` | bool |  |
| **IsIcon** `static` | bool |  |
| **IsImage** `static` *(+2 overloads)* | bool |  |
| **IsJpeg** `static` | bool |  |
| **IsMetafile** `static` | bool |  |
| **IsPng** `static` | bool |  |
| **IsSvg** `static` | bool |  |
| **IsTiff** `static` | bool |  |
| **IsWmf** `static` | bool |  |
| **IsXml** `static` | bool |  |
| **RotateImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **TryBytesFromFile** `static` | byte[] |  |
| **TryFromBytes** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **TryFromFile** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |

---

### Method Details

#### BytesFromFile `static`

**BytesFromFile**(**fileName**: string): byte[]

**Parameters**

- **fileName** (string)  

**Returns** byte[]


---

#### FromBytes `static`

**FromBytes**(****: bytebytes, **width**: int, **height**: int, **stretch**: bool, **aspectRatio**: bool): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **** (bytebytes)  
- **width** (int)  
- **height** (int)  
- **stretch** (bool)  
- **aspectRatio** (bool)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### FromFile `static`

**FromFile**(**fileName**: string, **width**: int, **height**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **fileName** (string)  
- **width** (int)  
- **height** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetImageBytesFromObject `static`

**GetImageBytesFromObject**(**imageObject**: object): byte[]

**Parameters**

- **imageObject** (object)  

**Returns** byte[]


---

#### IsBmp `static`

**IsBmp**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsEmf `static`

**IsEmf**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsEqualImages `static`

**IsEqualImages**(****: byteimage1, ****: byteimage2, **bytesToCompare**: int): bool

**Parameters**

- **** (byteimage1)  
- **** (byteimage2)  
- **bytesToCompare** (int)  

**Returns** bool


---

#### IsGif `static`

**IsGif**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsIcon `static`

**IsIcon**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsImage `static`

**IsImage**(**data**: object): bool

**Parameters**

- **data** (object)  

**Returns** bool

---

**IsImage**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool

---

**IsImage**(**str**: string): bool

**Parameters**

- **str** (string)  

**Returns** bool


---

#### IsJpeg `static`

**IsJpeg**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsMetafile `static`

**IsMetafile**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsPng `static`

**IsPng**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsSvg `static`

**IsSvg**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsTiff `static`

**IsTiff**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsWmf `static`

**IsWmf**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsXml `static`

**IsXml**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### RotateImage `static`

**RotateImage**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **rotation**: [StiImageRotation](../Components/StiImageRotation.md), **disposeOriginal**: bool): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **rotation** ([StiImageRotation](../Components/StiImageRotation.md))  
- **disposeOriginal** (bool)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### TryBytesFromFile `static`

**TryBytesFromFile**(**fileName**: string): byte[]

**Parameters**

- **fileName** (string)  

**Returns** byte[]


---

#### TryFromBytes `static`

**TryFromBytes**(****: bytebytes, **width**: int, **height**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **** (bytebytes)  
- **width** (int)  
- **height** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### TryFromFile `static`

**TryFromFile**(**fileName**: string, **width**: int, **height**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **fileName** (string)  
- **width** (int)  
- **height** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)

