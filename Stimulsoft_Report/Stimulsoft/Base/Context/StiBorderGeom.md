---
title: "StiBorderGeom Class"
---

## StiBorderGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiBorderGeom
```

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiBorderGeom([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) backgroundMouseOver, [StiPenGeom](StiPenGeom.md) borderPen, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex)` |  |
| `StiBorderGeom([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) backgroundMouseOver, [StiPenGeom](StiPenGeom.md) borderPen, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, float angle, [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md) rotationMode)` |  |
| `StiBorderGeom([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) backgroundMouseOver, [StiPenGeom](StiPenGeom.md) borderPen, object rect, StiCornerRadius cornerRadius, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, string tooltip, int elementIndex)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Angle** | float |  |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BackgroundMouseOver** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderPen** | [StiPenGeom](StiPenGeom.md) |  |
| **CornerRadius** | StiCornerRadius |  |
| **ElementIndex** | int |  |
| **Interaction** | [StiInteractionDataGeom](StiInteractionDataGeom.md) |  |
| **Rect** | object |  |
| **RotationMode** | [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md) |  |
| **ToolTip** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
