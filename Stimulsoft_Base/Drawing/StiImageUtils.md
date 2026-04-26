---
title: "StiImageUtils Class"
---

## StiImageUtils Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertToDisabled** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **ConvertToGrayscale** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **ExistsImage** `static` *(+1 overloads)* | bool | Returns true if specified image exists. |
| **GetByteArray** `static` *(+4 overloads)* | byte[] |  |
| **GetImage** `static` *(+5 overloads)* | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **IconFromBytes** `static` | [Icon](../../Stimulsoft_Drawing/root/Icon.md) |  |
| **MakeImageBackgroundAlphaZero** `static` | void |  |
| **ReplaceImageColor** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **ResizeImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |

---

### Method Details

#### ConvertToDisabled `static`

**ConvertToDisabled**(**bmp**: [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **bmp** ([Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### ConvertToGrayscale `static`

**ConvertToGrayscale**(**bmp**: [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **bmp** ([Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### ExistsImage `static`

**ExistsImage**(**imageAssembly**: Assembly, **imageName**: string): bool

Returns true if specified image exists.

**Parameters**

- **imageAssembly** (Assembly) — Assembly in which is the Image object is placed.  
- **imageName** (string) — The name of the image file to look for.  

**Returns** bool — True if specified image exists.

---

**ExistsImage**(**imageAssembly**: string, **imageName**: string): bool

Returns true if specified image exists.

**Parameters**

- **imageAssembly** (string) — Assembly in which is the Image object is placed.  
- **imageName** (string) — The name of the image file to look for.  

**Returns** bool — True if specified image exists.


---

#### GetByteArray `static`

**GetByteArray**(**type**: Type, **imageName**: string, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): byte[]

**Parameters**

- **type** (Type)  
- **imageName** (string)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** byte[]

---

**GetByteArray**(**type**: Type, **imageName**: string, **makeTransparent**: bool, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): byte[]

**Parameters**

- **type** (Type)  
- **imageName** (string)  
- **makeTransparent** (bool)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** byte[]

---

**GetByteArray**(**assemblyName**: string, **imageName**: string, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): byte[]

**Parameters**

- **assemblyName** (string)  
- **imageName** (string)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** byte[]

---

**GetByteArray**(**assemblyName**: string, **imageName**: string, **makeTransparent**: bool, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): byte[]

**Parameters**

- **assemblyName** (string)  
- **imageName** (string)  
- **makeTransparent** (bool)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** byte[]

---

**GetByteArray**(**imageAssembly**: Assembly, **imageName**: string, **makeTransparent**: bool, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): byte[]

**Parameters**

- **imageAssembly** (Assembly)  
- **imageName** (string)  
- **makeTransparent** (bool)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** byte[]


---

#### GetImage `static`

**GetImage**(**type**: Type, **imageName**: string, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **type** (Type)  
- **imageName** (string)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

---

**GetImage**(**type**: Type, **imageName**: string, **makeTransparent**: bool, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Gets the Image object associated with Type.

**Parameters**

- **type** (Type) — The type with which Image object is associated.  
- **imageName** (string) — The name of the image file to look for.  
- **makeTransparent** (bool)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — The Image object.

---

**GetImage**(**assemblyName**: string, **imageName**: string, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **assemblyName** (string)  
- **imageName** (string)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

---

**GetImage**(**assemblyName**: string, **imageName**: string, **makeTransparent**: bool, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Gets the Image object placed in assembly.

**Parameters**

- **assemblyName** (string) — The name of assembly in which the Cursor object is placed.  
- **imageName** (string) — The name of the image file to look for.  
- **makeTransparent** (bool)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — The Image object.

---

**GetImage**(**imageAssembly**: Assembly, **imageName**: string, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **imageAssembly** (Assembly)  
- **imageName** (string)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

---

**GetImage**(**imageAssembly**: Assembly, **imageName**: string, **makeTransparent**: bool, **throwError**: [StiErrorProcessing](StiErrorProcessing.md)): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Gets the Image object placed in assembly.

**Parameters**

- **imageAssembly** (Assembly) — Assembly in which is the Image object is placed.  
- **imageName** (string) — The name of the image file to look for.  
- **makeTransparent** (bool)  
- **throwError** ([StiErrorProcessing](StiErrorProcessing.md))  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — The Image object.


---

#### IconFromBytes `static`

**IconFromBytes**(****: bytebytes): [Icon](../../Stimulsoft_Drawing/root/Icon.md)

**Parameters**

- **** (bytebytes)  

**Returns** [Icon](../../Stimulsoft_Drawing/root/Icon.md)


---

#### MakeImageBackgroundAlphaZero `static`

**MakeImageBackgroundAlphaZero**(**image**: [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)): void

**Parameters**

- **image** ([Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md))  


---

#### ReplaceImageColor `static`

**ReplaceImageColor**(**bmp**: [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md), **colorForReplace**: Color, **replacedColor**: Color): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **bmp** ([Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md))  
- **colorForReplace** (Color)  
- **replacedColor** (Color)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### ResizeImage `static`

**ResizeImage**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **width**: int, **height**: int): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **width** (int)  
- **height** (int)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

---

**ResizeImage**(**image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **canvasWidth**: int, **canvasHeight**: int, **imageWidth**: int, **imageHeight**: int, **allowSampling**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **canvasWidth** (int)  
- **canvasHeight** (int)  
- **imageWidth** (int)  
- **imageHeight** (int)  
- **allowSampling** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

