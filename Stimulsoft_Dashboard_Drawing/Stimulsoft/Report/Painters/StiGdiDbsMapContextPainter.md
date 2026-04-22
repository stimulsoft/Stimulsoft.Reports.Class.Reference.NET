---
title: "StiGdiDbsMapContextPainter Class"
---

## StiGdiDbsMapContextPainter Class

**Namespace:** `Stimulsoft.Report.Painters`  
**Assembly:** `Stimulsoft.Dashboard.Drawing`

```csharp
public class StiGdiDbsMapContextPainter
```

### Inheritance

Implements: [IStiAnimationContextPainter](../../../../Stimulsoft_Report/Painters/Context/Animation/IStiAnimationContextPainter.md)<[StiGeom](../../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiGeom.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiGdiDbsMapContextPainter(StiRegionMapElement map)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AnimationEngine** | [StiAnimationEngine](../../../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) |  |
| **CheckedMapKeys** | List<string> |  |
| **ColorValues** | List<object> |  |
| **Data** | [StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md) |  |
| **Fill** | [Brush](../../../../Stimulsoft_Drawing/Brush.md) |  |
| **Geoms** | List<[StiGeom](../../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiGeom.md)> |  |
| **GroupValues** | List<object> |  |
| **KeyValues** | List<string> |  |
| **MouseOverKey** | string |  |
| **NameValues** | List<object> |  |
| **ShadowFill** | [Brush](../../../../Stimulsoft_Drawing/Brush.md) |  |
| **ValueValues** | List<object> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBrush** | [StiSolidBrush](../../../../Stimulsoft_Base/Drawing/StiSolidBrush.md) |  |
| **GetBubbleSize** | float |  |
| **GetColor** *(+2 overloads)* | Color |  |
| **GetGeomBrush** | [Brush](../../../../Stimulsoft_Drawing/Brush.md) |  |
| **GetMapStyle** `static` | StiMapStyle |  |
| **Init** | void |  |
| **Render** *(+1 overloads)* | void |  |
| **UpdateGroupedData** | void |  |
| **UpdateHeatmapWithGroup** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **MaxValue** | double? |  |
| **MinValue** | double? |  |
