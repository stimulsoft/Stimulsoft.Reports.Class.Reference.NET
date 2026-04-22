---
title: "StiArcSegmentGeom Class"
---

## StiArcSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiArcSegmentGeom
```

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiArcSegmentGeom(RectangleF rect, float startAngle, float sweepAngle)` |  |
| `StiArcSegmentGeom(RectangleF rect, float startAngle, float sweepAngle, float realStartAngle, float realSweepAngle)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
| **CrossElipseDraw** | bool |  |
| **RealStartAngle** | float? |  |
| **RealSweepAngle** | float? |  |
| **Rect** | RectangleF |  |
| **StartAngle** | float |  |
| **SweepAngle** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
