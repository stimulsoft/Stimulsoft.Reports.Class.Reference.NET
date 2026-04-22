---
title: "StiFontCollection Class"
---

## StiFontCollection Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public static class StiFontCollection
```

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
| **CreateFont** `static` | [Font](../Stimulsoft_Drawing/Font.md) |  |
| **GetCustomFontData** `static` | byte[] |  |
| **GetCustomFontPath** `static` | string |  |
| **GetFontFamilies** `static` | List<[FontFamily](../Stimulsoft_Drawing/FontFamily.md)> |  |
| **GetFontFamiliesFirstCustom** `static` | List<[FontFamily](../Stimulsoft_Drawing/FontFamily.md)> |  |
| **GetFontFamily** `static` | [FontFamily](../Stimulsoft_Drawing/FontFamily.md) |  |
| **GetFontFamilyByContent** `static` | [FontFamily](../Stimulsoft_Drawing/FontFamily.md) |  |
| **GetFontNamesByContent** `static` | List<string> |  |
| **IsCustomFont** `static` | bool |  |
| **IsStyleAvailable** `static` | bool |  |
| **RemoveResourceFont** `static` | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **GenerateFonts** | StiGenerateFontsEventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bold** | [FontV](Drawing/FontV.md) |  |
| **BoldItalic** | [FontV](Drawing/FontV.md) |  |
| **Italic** | [FontV](Drawing/FontV.md) |  |
| **Regular** | [FontV](Drawing/FontV.md) |  |
