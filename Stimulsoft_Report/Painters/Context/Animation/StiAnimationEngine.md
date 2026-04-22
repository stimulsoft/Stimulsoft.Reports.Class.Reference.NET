---
title: "StiAnimationEngine Class"
---

## StiAnimationEngine Class

**Namespace:** `Stimulsoft.Report.Painters.Context.Animation`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAnimationEngine
```

### Inheritance

Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AnimationExist** | bool |  |
| **IsReverse** | bool |  |
| **Speed** | double |  |
| **Tag** | object |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Continue** | void |  |
| **CorrectAnimationTimes** `static` | void |  |
| **Dispose** | void |  |
| **Finish** | void |  |
| **GetAnimationAngle** `static` *(+1 overloads)* | List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)> |  |
| **GetAnimationOpacity** `static` *(+3 overloads)* | [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md) |  |
| **GetAnimationPoint** `static` *(+1 overloads)* | PointF |  |
| **GetAnimationPoint3DY** `static` | [StiPoint3D](../../../Chart/StiPoint3D.md) |  |
| **GetAnimationPoints** `static` | PointF[] |  |
| **GetAnimationRectangle** `static` | RectangleF |  |
| **GetAnimationRectangle3D** `static` | [StiRectangle3D](../../../Chart/StiRectangle3D.md) |  |
| **GetAnimationRotation** `static` | PointF[] |  |
| **GetAnimationScale** `static` *(+2 overloads)* | RectangleF |  |
| **GetAnimationScale1** `static` | PointF[] |  |
| **GetAnimationTranslation** `static` *(+1 overloads)* | [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md) |  |
| **IsRunning** | bool |  |
| **RegisterContextPainter** | void |  |
| **Start** *(+2 overloads)* | void |  |
| **StartReverse** *(+1 overloads)* | void |  |
| **Stop** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Animation** | AnimationHandler |  |
| **ReverseEnd** | ReverseEndHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **contextPainter** | [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T> |  |
| **geoms** | List<T> |  |
