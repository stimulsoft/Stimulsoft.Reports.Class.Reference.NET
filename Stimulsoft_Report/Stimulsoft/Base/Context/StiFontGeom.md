---
title: "StiFontGeom Class"
---

## StiFontGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFontGeom**([Font](../../../../Stimulsoft_Drawing/root/Font.md) font) |  |
| **StiFontGeom**(string fontName, float fontSize, FontStyle style, GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont) |  |
| **StiFontGeom**([FontFamily](../../../../Stimulsoft_Drawing/root/FontFamily.md) fontFamily, string fontName, float fontSize, FontStyle style, GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont) |  |

**StiFontGeom**(**font**: [Font](../../../../Stimulsoft_Drawing/root/Font.md))

**Parameters**

- **font** ([Font](../../../../Stimulsoft_Drawing/root/Font.md))  

---

**StiFontGeom**(**fontName**: string, **fontSize**: float, **style**: FontStyle, **unit**: GraphicsUnit, **gdiCharSet**: byte, **gdiVerticalFont**: bool)

**Parameters**

- **fontName** (string)  
- **fontSize** (float)  
- **style** (FontStyle)  
- **unit** (GraphicsUnit)  
- **gdiCharSet** (byte)  
- **gdiVerticalFont** (bool)  

---

**StiFontGeom**(**fontFamily**: [FontFamily](../../../../Stimulsoft_Drawing/root/FontFamily.md), **fontName**: string, **fontSize**: float, **style**: FontStyle, **unit**: GraphicsUnit, **gdiCharSet**: byte, **gdiVerticalFont**: bool)

**Parameters**

- **fontFamily** ([FontFamily](../../../../Stimulsoft_Drawing/root/FontFamily.md))  
- **fontName** (string)  
- **fontSize** (float)  
- **style** (FontStyle)  
- **unit** (GraphicsUnit)  
- **gdiCharSet** (byte)  
- **gdiVerticalFont** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FontFamily** | [FontFamily](../../../../Stimulsoft_Drawing/root/FontFamily.md) |  |
| **FontName** | string |  |
| **FontSize** | float |  |
| **FontStyle** | FontStyle |  |
| **GdiCharSet** | byte |  |
| **GdiVerticalFont** | bool |  |
| **Unit** | GraphicsUnit |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ChangeFontSize** `static` | [StiFontGeom](StiFontGeom.md) |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ChangeFontSize `static`

**ChangeFontSize**(**font**: [Font](../../../../Stimulsoft_Drawing/root/Font.md), **newFontSize**: float): [StiFontGeom](StiFontGeom.md)

**Parameters**

- **font** ([Font](../../../../Stimulsoft_Drawing/root/Font.md))  
- **newFontSize** (float)  

**Returns** [StiFontGeom](StiFontGeom.md)


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

