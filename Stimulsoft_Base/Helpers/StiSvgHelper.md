---
title: "StiSvgHelper Class"
---

## StiSvgHelper Class

**Namespace:** `Stimulsoft.Base.Helpers`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **TryToLoadAssembly** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertSvgToImage** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **DrawSvg** `static` | bool |  |
| **DrawWithSvg** `static` | bool |  |
| **DrawWithSvgInternal** `static` | void |  |
| **GetSvgSize** `static` *(+1 overloads)* | SizeF |  |
| **IsSvg** `static` | bool |  |
| **IsSvgFile** `static` | bool |  |
| **OpenSvg** `static` | object |  |

---

### Method Details

#### ConvertSvgToImage `static`

**ConvertSvgToImage**(**svgLocator**: string, **rectF**: Rectangle, **rectSVG**: RectangleF, **zoom**: double): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **svgLocator** (string)  
- **rectF** (Rectangle)  
- **rectSVG** (RectangleF)  
- **zoom** (double)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### DrawSvg `static`

**DrawSvg**(****: bytesvgObject, **rect**: RectangleF, **stretch**: bool, **aspectRatio**: bool, **zoom**: double, **gr**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): bool

**Parameters**

- **** (bytesvgObject)  
- **rect** (RectangleF)  
- **stretch** (bool)  
- **aspectRatio** (bool)  
- **zoom** (double)  
- **gr** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  

**Returns** bool


---

#### DrawWithSvg `static`

**DrawWithSvg**(**svgLocator**: string, **rectF**: RectangleF, **rectSVG**: RectangleF, **zoom**: double, **gr**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): bool

**Parameters**

- **svgLocator** (string)  
- **rectF** (RectangleF)  
- **rectSVG** (RectangleF)  
- **zoom** (double)  
- **gr** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  

**Returns** bool


---

#### DrawWithSvgInternal `static`

**DrawWithSvgInternal**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **typeSvgDocument**: Type, **svgLocator**: string): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **typeSvgDocument** (Type)  
- **svgLocator** (string)  


---

#### GetSvgSize `static`

**GetSvgSize**(****: bytedata): SizeF

**Parameters**

- **** (bytedata)  

**Returns** SizeF

---

**GetSvgSize**(**document**: object): SizeF

**Parameters**

- **document** (object)  

**Returns** SizeF


---

#### IsSvg `static`

**IsSvg**(****: bytedata): bool

**Parameters**

- **** (bytedata)  

**Returns** bool


---

#### IsSvgFile `static`

**IsSvgFile**(**fileName**: string): bool

**Parameters**

- **fileName** (string)  

**Returns** bool


---

#### OpenSvg `static`

**OpenSvg**(****: bytesvgObject): object

**Parameters**

- **** (bytesvgObject)  

**Returns** object


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AssemblyName** | string |  |
| **AssemblyVersion** | string |  |
| **IsSvgAssemblyLoaded** | bool |  |
| **SvgAssemblyPrefix** | string |  |
