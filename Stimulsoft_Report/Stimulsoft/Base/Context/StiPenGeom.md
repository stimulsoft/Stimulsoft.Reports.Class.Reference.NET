---
title: "StiPenGeom Class"
---

## StiPenGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPenGeom
```

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPenGeom(Color brush)` |  |
| `StiPenGeom([LinearGradientBrush](../../../../Stimulsoft_Drawing/Drawing2D/LinearGradientBrush.md) brush)` |  |
| `StiPenGeom(Color brush, float thickness)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiPenAlignment](StiPenAlignment.md) |  |
| **Brush** | Color |  |
| **Brush2** | [LinearGradientBrush](../../../../Stimulsoft_Drawing/Drawing2D/LinearGradientBrush.md) |  |
| **EndCap** | [StiPenLineCap](../../../../Stimulsoft_Base/Context/StiPenLineCap.md) |  |
| **PenStyle** | [StiPenStyle](../../../../Stimulsoft_Base/Drawing/StiPenStyle.md) |  |
| **StartCap** | [StiPenLineCap](../../../../Stimulsoft_Base/Context/StiPenLineCap.md) |  |
| **Thickness** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
