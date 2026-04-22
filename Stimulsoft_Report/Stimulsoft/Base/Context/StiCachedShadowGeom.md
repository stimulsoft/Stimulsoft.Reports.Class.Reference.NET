---
title: "StiCachedShadowGeom Class"
---

## StiCachedShadowGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCachedShadowGeom
```

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCachedShadowGeom(RectangleF rect, [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) sides, bool isPrinting)` |  |
| `StiCachedShadowGeom(RectangleF rect, [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) sides, bool isPrinting, RectangleF clipRect)` |  |
| `StiCachedShadowGeom(RectangleF rect, [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) sides, bool isPrinting, RectangleF clipRect, StiCornerRadius cornerRadius)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClipRect** | RectangleF |  |
| **CornerRadius** | StiCornerRadius |  |
| **IsPrinting** | bool |  |
| **Rect** | RectangleF |  |
| **Sides** | [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
