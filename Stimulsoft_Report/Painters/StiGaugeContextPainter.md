---
title: "StiGaugeContextPainter Class"
---

## StiGaugeContextPainter Class

**Namespace:** `Stimulsoft.Report.Painters`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiGaugeContextPainter
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiGaugeContextPainter(StiGauge gauge, RectangleF rect, float zoom)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animations** | List<[StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)> |  |
| **Gauge** | StiGauge |  |
| **Geoms** | List<[StiGaugeGeom](../Gauge/GaugeGeoms/StiGaugeGeom.md)> |  |
| **Rect** | RectangleF |  |
| **ScaleSystem** | double |  |
| **Zoom** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddEllipseGaugeGeom** | void |  |
| **AddGraphicsPathGaugeGeom** | void |  |
| **AddPieGaugeGeom** | void |  |
| **AddPopTranformGaugeGeom** | void |  |
| **AddPushMatrixGaugeGeom** | void |  |
| **AddRectangleGaugeGeom** | void |  |
| **AddRoundedRectangleGaugeGeom** | void |  |
| **AddTextGaugeGeom** | void |  |
| **ChangeFontSize** `static` | [Font](../../Stimulsoft_Drawing/Font.md) |  |
| **MeasureString** | SizeF |  |
| **Render** | void |  |
