---
title: "StiPdfGeomWriter Class"
---

## StiPdfGeomWriter Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPdfGeomWriter
```

### Inheritance

Implements: [IStiExportGeomWriter](IStiExportGeomWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPdfGeomWriter()` |  |
| `StiPdfGeomWriter(StreamWriter stream, [StiPdfExportService](StiPdfExportService.md) service, bool assembleData, bool allowThinLines, float cornerScaling)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BeginPath** | void |  |
| **CloseFigure** | void |  |
| **ConvertSplineToCubicBezier** | PointF[] |  |
| **DrawArc** *(+1 overloads)* | void |  |
| **DrawBezier** | void |  |
| **DrawBezierTo** | void |  |
| **DrawEllipse** | void |  |
| **DrawImage** | void |  |
| **DrawLine** | void |  |
| **DrawLineTo** | void |  |
| **DrawPie** | void |  |
| **DrawPolygon** | void |  |
| **DrawPolyline** *(+1 overloads)* | void |  |
| **DrawPolylineTo** | void |  |
| **DrawRectangle** | void |  |
| **DrawSpline** | void |  |
| **DrawString** | void |  |
| **DrawText** | void |  |
| **EndPath** | void |  |
| **FillEllipse** | void |  |
| **FillPath** | void |  |
| **FillPolygon** | void |  |
| **FillPolygons** | void |  |
| **FillRectangle** *(+1 overloads)* | void |  |
| **MeasureString** | SizeF |  |
| **MoveTo** | void |  |
| **RestoreState** | void |  |
| **RotateTransform** *(+1 overloads)* | void |  |
| **SaveState** | void |  |
| **ScaleTransform** | void |  |
| **SetBrush** | bool |  |
| **SetClip** | void |  |
| **SetClipPath** | void |  |
| **SetPen** | bool |  |
| **SetPixel** | void |  |
| **StrokePath** | void |  |
| **TranslateTransform** | void |  |
