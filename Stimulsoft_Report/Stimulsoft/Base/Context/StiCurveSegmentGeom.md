---
title: "StiCurveSegmentGeom Class"
---

## StiCurveSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCurveSegmentGeom
```

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCurveSegmentGeom**(PointFpoints , float tension) |  |
| **StiCurveSegmentGeom**(PointFpoints , float tension, [StiAnimation](Animation/StiAnimation.md) animation) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
| **Points** | PointF[] |  |
| **Tension** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
