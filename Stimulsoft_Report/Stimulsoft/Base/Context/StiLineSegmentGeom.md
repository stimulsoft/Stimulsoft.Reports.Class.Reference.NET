---
title: "StiLineSegmentGeom Class"
---

## StiLineSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiLineSegmentGeom
```

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLineSegmentGeom**(PointF start, PointF end) |  |
| **StiLineSegmentGeom**(PointF start, PointF end, [StiAnimation](Animation/StiAnimation.md) animation) |  |
| **StiLineSegmentGeom**(float x1, float y1, float x2, float y2) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
| **X1** | float |  |
| **X2** | float |  |
| **Y1** | float |  |
| **Y2** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
