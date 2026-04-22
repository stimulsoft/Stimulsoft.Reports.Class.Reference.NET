---
title: "StiShadowAnimationGeom Class"
---

## StiShadowAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiShadowAnimationGeom
```

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiShadowAnimationGeom**(RectangleF rect, int shadowWidth, StiCornerRadius cornerRadius, [StiAnimation](Animation/StiAnimation.md) animation) |  |
| **StiShadowAnimationGeom**(RectangleF rect, double radiusX, double radiusY, int shadowWidth, [StiAnimation](Animation/StiAnimation.md) animation) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CornerRadius** | StiCornerRadius |  |
| **RadiusX** | double |  |
| **RadiusY** | double |  |
| **Rect** | RectangleF |  |
| **ShadowWidth** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
