---
title: "StiGisCore Class"
---

## StiGisCore Class

**Namespace:** `Stimulsoft.Map.Gis.Core`

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

---

### Method Details

#### BeginDrag

**BeginDrag**(**pt**: [StiGisPoint](StiGisPoint.md)): void

**Parameters**

- **pt** ([StiGisPoint](StiGisPoint.md))  


---

#### CancelAsyncTasks

**CancelAsyncTasks**(): void


---

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  

---

**Dispose**(): void


---

#### Drag

**Drag**(**pt**: [StiGisPoint](StiGisPoint.md)): void

**Parameters**

- **pt** ([StiGisPoint](StiGisPoint.md))  


---

#### DragOffset

**DragOffset**(**offset**: [StiGisPoint](StiGisPoint.md)): void

**Parameters**

- **offset** ([StiGisPoint](StiGisPoint.md))  


---

#### EndDrag

**EndDrag**(): void


---

#### FromLatLngToLocal

**FromLatLngToLocal**(**latlng**: [StiGisPointLatLng](StiGisPointLatLng.md)): [StiGisPoint](StiGisPoint.md)

**Parameters**

- **latlng** ([StiGisPointLatLng](StiGisPointLatLng.md))  

**Returns** [StiGisPoint](StiGisPoint.md)


---

#### FromLocalToLatLng

**FromLocalToLatLng**(**x**: int, **y**: int): [StiGisPointLatLng](StiGisPointLatLng.md)

**Parameters**

- **x** (int)  
- **y** (int)  

**Returns** [StiGisPointLatLng](StiGisPointLatLng.md)


---

#### GetImageFrom

**GetImageFrom**(**provider**: [StiGisMapProvider](../Providers/StiGisMapProvider.md), **pos**: [StiGisPoint](StiGisPoint.md), **zoom**: int, **error**: Exception): [StiGisMapImage](StiGisMapImage.md)

**Parameters**

- **provider** ([StiGisMapProvider](../Providers/StiGisMapProvider.md))  
- **pos** ([StiGisPoint](StiGisPoint.md))  
- **zoom** (int)  
- **error** (Exception)  

**Returns** [StiGisMapImage](StiGisMapImage.md)


---

#### GetMaxZoomToFitRect

**GetMaxZoomToFitRect**(**rect**: [StiGisRectLatLng](StiGisRectLatLng.md)): int

**Parameters**

- **rect** ([StiGisRectLatLng](StiGisRectLatLng.md))  

**Returns** int


---

#### GoToCurrentPosition

**GoToCurrentPosition**(): void


---

#### OnMapSizeChanged

**OnMapSizeChanged**(**width**: int, **height**: int): void

**Parameters**

- **width** (int)  
- **height** (int)  


---

#### ReloadMap

**ReloadMap**(): void


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
