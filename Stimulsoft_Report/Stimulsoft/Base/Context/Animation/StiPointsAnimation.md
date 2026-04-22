---
title: "StiPointsAnimation Class"
---

## StiPointsAnimation Class

**Namespace:** `Stimulsoft.Base.Context.Animation`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPointsAnimation
```

### Inheritance

Inherits from: [StiAnimation](StiAnimation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPointsAnimation**(PointFpointsFrom , TimeSpan duration, TimeSpan beginTime) |  |
| **StiPointsAnimation**(PointFpointsFrom , PointFpointsTo , stringpointsIds , TimeSpan duration, TimeSpan beginTime) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PointsFrom** | PointF[] |  |
| **PointsIds** | string[] |  |
| **PointsTo** | PointF[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyPreviousAnimation** | void |  |
| **IsAnimationChangingValues** `static` *(+1 overloads)* | bool |  |
| **Reverse** | void |  |
