---
title: "Image Class"
---

## Image Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Implements: IDisposable, ICloneable  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **Dispose** | void |  |
| **FromFile** `static` | [Image](Image.md) |  |
| **FromStream** `static` *(+1 overloads)* | [Image](Image.md) |  |
| **GetPropertyItem** | System.Drawing.Imaging.PropertyItem? |  |
| **GetPropertyValue** | byte |  |
| **MakeTransparent** | bool |  |
| **RemovePropertyItem** | void |  |
| **RotateFlip** | void |  |
| **Save** *(+2 overloads)* | void |  |
| **SaveAdd** *(+1 overloads)* | void |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### Dispose

**Dispose**(): void


---

#### FromFile `static`

**FromFile**(**filename**: string): [Image](Image.md)

**Parameters**

- **filename** (string)  

**Returns** [Image](Image.md)


---

#### FromStream `static`

**FromStream**(**stream**: Stream): [Image](Image.md)

**Parameters**

- **stream** (Stream)  

**Returns** [Image](Image.md)

---

**FromStream**(**stream**: Stream, **useEmbeddedColorManagement**: bool): [Image](Image.md)

**Parameters**

- **stream** (Stream)  
- **useEmbeddedColorManagement** (bool)  

**Returns** [Image](Image.md)


---

#### GetPropertyItem

**GetPropertyItem**(**propId**: int): System.Drawing.Imaging.PropertyItem?

**Parameters**

- **propId** (int)  

**Returns** System.Drawing.Imaging.PropertyItem?


---

#### GetPropertyValue

**GetPropertyValue**(**propId**: int): byte

**Parameters**

- **propId** (int)  

**Returns** byte


---

#### MakeTransparent

**MakeTransparent**(**transparency**: float): bool

**Parameters**

- **transparency** (float)  

**Returns** bool


---

#### RemovePropertyItem

**RemovePropertyItem**(**propId**: int): void

**Parameters**

- **propId** (int)  


---

#### RotateFlip

**RotateFlip**(**type**: System.Drawing.RotateFlipType): void

**Parameters**

- **type** (System.Drawing.RotateFlipType)  


---

#### Save

**Save**(**stream**: Stream, **encoder**: [ImageCodecInfo](../Imaging/ImageCodecInfo.md), **encoderParams**: [EncoderParameters](../Imaging/EncoderParameters.md)): void

**Parameters**

- **stream** (Stream)  
- **encoder** ([ImageCodecInfo](../Imaging/ImageCodecInfo.md))  
- **encoderParams** ([EncoderParameters](../Imaging/EncoderParameters.md))  

---

**Save**(**stream**: Stream, **format**: [ImageFormat](../Imaging/ImageFormat.md)): void

**Parameters**

- **stream** (Stream)  
- **format** ([ImageFormat](../Imaging/ImageFormat.md))  

---

**Save**(**filePath**: string, **format**: [ImageFormat](../Imaging/ImageFormat.md)): void

**Parameters**

- **filePath** (string)  
- **format** ([ImageFormat](../Imaging/ImageFormat.md))  


---

#### SaveAdd

**SaveAdd**(**encoderParams**: [EncoderParameters](../Imaging/EncoderParameters.md)): void

**Parameters**

- **encoderParams** ([EncoderParameters](../Imaging/EncoderParameters.md))  

---

**SaveAdd**(**image**: [Image](Image.md), **encoderParams**: [EncoderParameters](../Imaging/EncoderParameters.md)): void

**Parameters**

- **image** ([Image](Image.md))  
- **encoderParams** ([EncoderParameters](../Imaging/EncoderParameters.md))  

