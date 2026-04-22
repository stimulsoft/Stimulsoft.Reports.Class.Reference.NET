---
title: "StiPathGeom Class"
---

## StiPathGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPathGeom
```

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPathGeom([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) pen, List<[StiSegmentGeom](StiSegmentGeom.md)> geoms, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, object tag)` |  |
| `StiPathGeom([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) pen, List<[StiSegmentGeom](StiSegmentGeom.md)> geoms, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, string toolTip, object tag)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ElementIndex** | int |  |
| **Geoms** | List<[StiSegmentGeom](StiSegmentGeom.md)> |  |
| **GetBoundsState** `static` | object |  |
| **Interaction** | [StiInteractionDataGeom](StiInteractionDataGeom.md) |  |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Rect** | object |  |
| **Tag** | object |  |
| **ToolTip** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
