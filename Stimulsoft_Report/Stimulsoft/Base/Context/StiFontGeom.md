---
title: "StiFontGeom Class"
---

## StiFontGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFontGeom
```

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiFontGeom([Font](../../../../Stimulsoft_Drawing/Font.md) font)` |  |
| `StiFontGeom(string fontName, float fontSize, FontStyle style, GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont)` |  |
| `StiFontGeom([FontFamily](../../../../Stimulsoft_Drawing/FontFamily.md) fontFamily, string fontName, float fontSize, FontStyle style, GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FontFamily** | [FontFamily](../../../../Stimulsoft_Drawing/FontFamily.md) |  |
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
