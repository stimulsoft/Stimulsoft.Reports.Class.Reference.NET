---
title: "StiFontCollection Class"
---

## StiFontCollection Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowFileCache** `static` | bool |  |
| **AllowFileCache** `static` | bool |  |
| **DefaultCachePath** `static` | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddFontBase64** `static` *(+1 overloads)* | void |  |
| **AddFontBytes** `static` *(+1 overloads)* | void |  |
| **AddFontFile** `static` | void |  |
| **AddFontStream** `static` | void |  |
| **AddMemoryFont** `static` | void |  |
| **AddResourceFont** `static` | void | Add font from report resources. For internal use only !!! |
| **CreateFont** `static` | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **GetCustomFontData** `static` | byte[] |  |
| **GetCustomFontPath** `static` | string |  |
| **GetFontFamilies** `static` | List<[FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)> |  |
| **GetFontFamiliesFirstCustom** `static` | List<[FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)> |  |
| **GetFontFamily** `static` | [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md) |  |
| **GetFontFamilyByContent** `static` | [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md) |  |
| **GetFontNamesByContent** `static` | List<string> |  |
| **IsCustomFont** `static` | bool |  |
| **IsStyleAvailable** `static` | bool |  |
| **RemoveResourceFont** `static` | void |  |

---

### Method Details

#### AddFontBase64 `static`

**AddFontBase64**(**fontBase64**: string, **alias**: string, **fontStyle**: FontStyle?): void

**Parameters**

- **fontBase64** (string)  
- **alias** (string)  
- **fontStyle** (FontStyle?)  

---

**AddFontBase64**(**collection**: [PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md), **fontBase64**: string): void

**Parameters**

- **collection** ([PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md))  
- **fontBase64** (string)  


---

#### AddFontBytes `static`

**AddFontBytes**(****: bytecontent, **alias**: string, **fontStyle**: FontStyle?): void

**Parameters**

- **** (bytecontent)  
- **alias** (string)  
- **fontStyle** (FontStyle?)  

---

**AddFontBytes**(**collection**: [PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md), ****: bytefontData): void

**Parameters**

- **collection** ([PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md))  
- **** (bytefontData)  


---

#### AddFontFile `static`

**AddFontFile**(**fileName**: string, **alias**: string, **fontStyle**: FontStyle?): void

**Parameters**

- **fileName** (string)  
- **alias** (string)  
- **fontStyle** (FontStyle?)  


---

#### AddFontStream `static`

**AddFontStream**(**collection**: [PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md), **fontStream**: Stream): void

**Parameters**

- **collection** ([PrivateFontCollection](../../Stimulsoft_Drawing/Text/PrivateFontCollection.md))  
- **fontStream** (Stream)  


---

#### AddMemoryFont `static`

**AddMemoryFont**(**memory**: IntPtr, **length**: int): void

**Parameters**

- **memory** (IntPtr)  
- **length** (int)  


---

#### AddResourceFont `static`

**AddResourceFont**(**name**: string, ****: bytecontent, **extension**: string, **alias**: string): void

Add font from report resources. For internal use only !!!

**Parameters**

- **name** (string) — Font name  
- **** (bytecontent)  
- **extension** (string) — Original font file extension  
- **alias** (string) — Font alias  


---

#### CreateFont `static`

**CreateFont**(**fontName**: string, **fontSize**: float, **fontStyle**: FontStyle): [Font](../../Stimulsoft_Drawing/root/Font.md)

**Parameters**

- **fontName** (string)  
- **fontSize** (float)  
- **fontStyle** (FontStyle)  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md)


---

#### GetCustomFontData `static`

**GetCustomFontData**(**fontName**: string, **baseFontStyle**: FontStyle): byte[]

**Parameters**

- **fontName** (string)  
- **baseFontStyle** (FontStyle)  

**Returns** byte[]


---

#### GetCustomFontPath `static`

**GetCustomFontPath**(**fontName**: string, **baseFontStyle**: FontStyle): string

**Parameters**

- **fontName** (string)  
- **baseFontStyle** (FontStyle)  

**Returns** string


---

#### GetFontFamilies `static`

**GetFontFamilies**(): List<[FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)>

**Returns** List<[FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)>


---

#### GetFontFamiliesFirstCustom `static`

**GetFontFamiliesFirstCustom**(): List<[FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)>

**Returns** List<[FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)>


---

#### GetFontFamily `static`

**GetFontFamily**(**fontName**: string, **baseFontStyle**: FontStyle, **allowNullResult**: bool): [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)

**Parameters**

- **fontName** (string)  
- **baseFontStyle** (FontStyle)  
- **allowNullResult** (bool)  

**Returns** [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)


---

#### GetFontFamilyByContent `static`

**GetFontFamilyByContent**(**name**: string, ****: bytecontent, **extension**: string, **alias**: string): [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)

**Parameters**

- **name** (string)  
- **** (bytecontent)  
- **extension** (string)  
- **alias** (string)  

**Returns** [FontFamily](../../Stimulsoft_Drawing/root/FontFamily.md)


---

#### GetFontNamesByContent `static`

**GetFontNamesByContent**(**name**: string, ****: bytecontent, **extension**: string, **alias**: string): List<string>

**Parameters**

- **name** (string)  
- **** (bytecontent)  
- **extension** (string)  
- **alias** (string)  

**Returns** List<string>


---

#### IsCustomFont `static`

**IsCustomFont**(**fontName**: string): bool

**Parameters**

- **fontName** (string)  

**Returns** bool


---

#### IsStyleAvailable `static`

**IsStyleAvailable**(**fontName**: string, **style**: FontStyle): bool

**Parameters**

- **fontName** (string)  
- **style** (FontStyle)  

**Returns** bool


---

#### RemoveResourceFont `static`

**RemoveResourceFont**(**name**: string, ****: bytecontent): void

**Parameters**

- **name** (string)  
- **** (bytecontent)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **GenerateFonts** | StiGenerateFontsEventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bold** | [FontV](../Drawing/FontV.md) |  |
| **BoldItalic** | [FontV](../Drawing/FontV.md) |  |
| **Italic** | [FontV](../Drawing/FontV.md) |  |
| **Regular** | [FontV](../Drawing/FontV.md) |  |
