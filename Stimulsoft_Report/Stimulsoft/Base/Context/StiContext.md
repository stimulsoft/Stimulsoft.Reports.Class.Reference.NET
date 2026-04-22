---
title: "StiContext Class"
---

## StiContext Class

**Namespace:** `Stimulsoft.Base.Context`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiContext
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiContext([StiContextPainter](StiContextPainter.md) contextPainter, bool isGdi, bool isWpf, bool isPrinting, float zoom)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animations** | List<[StiAnimation](Animation/StiAnimation.md)> |  |
| **ContextPainter** | [StiContextPainter](StiContextPainter.md) |  |
| **Geoms** | List<[StiGeom](StiGeom.md)> |  |
| **Options** | [StiContextOptions](StiContextOptions.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateShadowGraphics** | [StiContext](StiContext.md) |  |
| **DrawAnimationBar** *(+1 overloads)* | void |  |
| **DrawAnimationCicledRectangle** | void |  |
| **DrawAnimationColumn** *(+1 overloads)* | void |  |
| **DrawAnimationCurve** | void |  |
| **DrawAnimationLines** | void |  |
| **DrawAnimationPathElement** *(+1 overloads)* | void |  |
| **DrawAnimationRectangle** | void |  |
| **DrawCachedShadow** *(+2 overloads)* | void |  |
| **DrawCicledRectangle** | void |  |
| **DrawCurve** | void |  |
| **DrawEllipse** *(+1 overloads)* | void |  |
| **DrawImage** | void |  |
| **DrawLine** | void |  |
| **DrawLines** | void |  |
| **DrawPath** | void |  |
| **DrawRectangle** *(+2 overloads)* | void |  |
| **DrawRotatedString** *(+1 overloads)* | [StiTextGeom](StiTextGeom.md) |  |
| **DrawShadow** | void |  |
| **DrawShadowCircle** | void |  |
| **DrawShadowRect** | void |  |
| **DrawString** *(+4 overloads)* | [StiTextGeom](StiTextGeom.md) |  |
| **FillCicledRectangle** | void |  |
| **FillDrawAnimationEllipse** *(+1 overloads)* | void |  |
| **FillDrawAnimationPath** *(+1 overloads)* | void |  |
| **FillEllipse** *(+2 overloads)* | void |  |
| **FillPath** | void |  |
| **FillRectangle** *(+2 overloads)* | void |  |
| **GetDefaultStringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **GetGenericStringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **GetPathBounds** | RectangleF |  |
| **MeasureRotatedString** *(+3 overloads)* | RectangleF |  |
| **MeasureString** *(+1 overloads)* | SizeF |  |
| **PopClip** | void |  |
| **PopSmoothingMode** | void |  |
| **PopTextRenderingHint** | void |  |
| **PopTransform** | void |  |
| **PushClip** | void |  |
| **PushClipPath** | void |  |
| **PushRotateTransform** | void |  |
| **PushSmoothingModeToAntiAlias** | void |  |
| **PushTextRenderingHintToAntiAlias** | void |  |
| **PushTranslateTransform** | void |  |
| **Render** | void |  |
