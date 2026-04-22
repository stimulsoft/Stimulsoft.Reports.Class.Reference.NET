---
title: "StiGisCore Class"
---

## StiGisCore Class

**Namespace:** `Stimulsoft.Map.Gis.Core`  
**Assembly:** `Stimulsoft.Map`

```csharp
public sealed class StiGisCore
```

### Inheritance

Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LanguageStr** | string |  |
| **MouseWheelZoomType** | [StiGeoMouseWheelZoomType](StiGeoMouseWheelZoomType.md) |  |
| **RenderMode** | [StiGeoRenderMode](StiGeoRenderMode.md) |  |
| **WpfFontFamily** | System.Windows.Media.FontFamily |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BeginDrag** | void |  |
| **CancelAsyncTasks** | void |  |
| **Dispose** *(+1 overloads)* | void |  |
| **Drag** | void |  |
| **DragOffset** | void |  |
| **EndDrag** | void |  |
| **FromLatLngToLocal** | [StiGisPoint](StiGisPoint.md) |  |
| **FromLocalToLatLng** | [StiGisPointLatLng](StiGisPointLatLng.md) |  |
| **GetImageFrom** | [StiGisMapImage](StiGisMapImage.md) |  |
| **GetMaxZoomToFitRect** | int |  |
| **GoToCurrentPosition** | void |  |
| **OnMapSizeChanged** | void |  |
| **ReloadMap** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **OnCurrentPositionChanged** | StiGisPositionChanged |  |
| **OnMapTypeChanged** | StiGisMapTypeChanged |  |
| **OnMapZoomChanged** | StiGisMapZoomChanged |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AllowLocalCache** | bool |  |
| **LevelsKeepInMemmory** | int |  |
| **centerTileXYLocation** | [StiGisPoint](StiGisPoint.md) |  |
| **centerTileXYLocationLast** | [StiGisPoint](StiGisPoint.md) |  |
| **compensationOffset** | [StiGisPoint](StiGisPoint.md) |  |
| **dragPoint** | [StiGisPoint](StiGisPoint.md) |  |
| **mouseCurrent** | [StiGisPoint](StiGisPoint.md) |  |
| **mouseDown** | [StiGisPoint](StiGisPoint.md) |  |
| **mouseLastZoom** | [StiGisPoint](StiGisPoint.md) |  |
| **position** | [StiGisPointLatLng](StiGisPointLatLng.md) |  |
| **positionPixel** | [StiGisPoint](StiGisPoint.md) |  |
| **renderOffset** | [StiGisPoint](StiGisPoint.md) |  |
