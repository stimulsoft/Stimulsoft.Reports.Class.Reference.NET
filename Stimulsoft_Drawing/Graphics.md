---
title: "Graphics Class"
---

## Graphics Class

**Namespace:** `Stimulsoft.Drawing`  
**Assembly:** `Stimulsoft.Drawing`

```csharp
public class Graphics
```

### Inheritance

Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GraphicsEngine** `static` | [GraphicsEngine](GraphicsEngine.md) |  |
| **SixLaborsFontsKerning** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Dispose** | void |  |
| **DrawArc** *(+1 overloads)* | void |  |
| **DrawCurve** *(+1 overloads)* | void |  |
| **DrawEllipse** *(+3 overloads)* | void |  |
| **DrawImage** *(+14 overloads)* | void |  |
| **DrawImageUnscaled** *(+3 overloads)* | void |  |
| **DrawImageUnscaledAndClipped** | void |  |
| **DrawLine** *(+3 overloads)* | void |  |
| **DrawLines** *(+1 overloads)* | void |  |
| **DrawPath** | void |  |
| **DrawPie** | void |  |
| **DrawPolygon** | void |  |
| **DrawRectangle** *(+2 overloads)* | void |  |
| **DrawString** *(+5 overloads)* | void |  |
| **EnumerateMetafile** | void |  |
| **FillEllipse** *(+3 overloads)* | void |  |
| **FillPath** | void |  |
| **FillPie** | void |  |
| **FillPolygon** | void |  |
| **FillRectangle** *(+3 overloads)* | void |  |
| **FillRegion** | void |  |
| **Flush** | void |  |
| **FromHdc** `static` | [Graphics](Graphics.md) |  |
| **FromHwnd** `static` | [Graphics](Graphics.md) |  |
| **FromImage** `static` | [Graphics](Graphics.md) |  |
| **GetHdc** | IntPtr |  |
| **MeasureCharacterRanges** | [Region](Region.md)[] |  |
| **MeasureString** *(+5 overloads)* | SizeF |  |
| **MultiplyTransform** | void |  |
| **ReleaseHdc** *(+1 overloads)* | void |  |
| **ResetClip** | void |  |
| **ResetTransform** | void |  |
| **Restore** | void |  |
| **RotateTransform** *(+1 overloads)* | void |  |
| **Save** | [GraphicsState](Drawing2D/GraphicsState.md) |  |
| **ScaleTransform** *(+1 overloads)* | void |  |
| **SetClip** *(+5 overloads)* | void |  |
| **TransformPoints** | void |  |
| **TranslateTransform** *(+3 overloads)* | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DefaultImageSharpDpi** | float |  |
| **DefaultTabSize** | int |  |
| **ReplaceTabWithSpaces** | bool |  |
