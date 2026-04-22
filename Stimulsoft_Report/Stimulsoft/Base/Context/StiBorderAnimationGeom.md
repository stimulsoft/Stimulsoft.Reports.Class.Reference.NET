---
title: "StiBorderAnimationGeom Class"
---

## StiBorderAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiBorderAnimationGeom
```

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBorderAnimationGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) borderPen, object rect, object tag, [StiAnimation](Animation/StiAnimation.md) animation, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, string toolTip) |  |
| **StiBorderAnimationGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) wpfBackColor, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) borderPen, object rect, StiCornerRadius cornerRadius, object tag, [StiAnimation](Animation/StiAnimation.md) animation, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, string toolTip) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderPen** | [StiPenGeom](StiPenGeom.md) |  |
| **CornerRadius** | StiCornerRadius |  |
| **Rect** | object |  |
| **Tag** | object |  |
| **ToolTip** | string |  |
| **WpfBackColor** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
