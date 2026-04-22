---
title: "StiPieSegmentGeom Class"
---

## StiPieSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPieSegmentGeom
```

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPieSegmentGeom**(RectangleF rect, float startAngle, float sweepAngle, [StiAnimation](Animation/StiAnimation.md) animation) |  |
| **StiPieSegmentGeom**(RectangleF rect, float startAngle, float sweepAngle, float realStartAngle, float realSweepAngle, [StiAnimation](Animation/StiAnimation.md) animation) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **EndAngle** | float |  |
