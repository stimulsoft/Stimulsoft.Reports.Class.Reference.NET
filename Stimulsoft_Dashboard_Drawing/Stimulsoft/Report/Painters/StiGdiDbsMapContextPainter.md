---
title: "StiGdiDbsMapContextPainter Class"
---

## StiGdiDbsMapContextPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Implements: [IStiAnimationContextPainter](../../../../Stimulsoft_Report/Painters/Context/Animation/IStiAnimationContextPainter.md)<[StiGeom](../../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiGeom.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGdiDbsMapContextPainter**(StiRegionMapElement map) |  |

**StiGdiDbsMapContextPainter**(**map**: StiRegionMapElement)

**Parameters**

- **map** (StiRegionMapElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AnimationEngine** | [StiAnimationEngine](../../../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) |  |
| **CheckedMapKeys** | List<string> |  |
| **ColorValues** | List<object> |  |
| **Data** | [StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md) |  |
| **Fill** | [Brush](../../../../Stimulsoft_Drawing/root/Brush.md) |  |
| **Geoms** | List<[StiGeom](../../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiGeom.md)> |  |
| **GroupValues** | List<object> |  |
| **KeyValues** | List<string> |  |
| **MouseOverKey** | string |  |
| **NameValues** | List<object> |  |
| **ShadowFill** | [Brush](../../../../Stimulsoft_Drawing/root/Brush.md) |  |
| **ValueValues** | List<object> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBrush** | [StiSolidBrush](../../../../Stimulsoft_Base/Drawing/StiSolidBrush.md) |  |
| **GetBubbleSize** | float |  |
| **GetColor** *(+2 overloads)* | Color |  |
| **GetGeomBrush** | [Brush](../../../../Stimulsoft_Drawing/root/Brush.md) |  |
| **GetMapStyle** `static` | StiMapStyle |  |
| **Init** | void |  |
| **Render** *(+1 overloads)* | void |  |
| **UpdateGroupedData** | void |  |
| **UpdateHeatmapWithGroup** | void |  |

---

### Method Details

#### GetBrush

**GetBrush**(): [StiSolidBrush](../../../../Stimulsoft_Base/Drawing/StiSolidBrush.md)

**Returns** [StiSolidBrush](../../../../Stimulsoft_Base/Drawing/StiSolidBrush.md)


---

#### GetBubbleSize

**GetBubbleSize**(**key**: string): float

**Parameters**

- **key** (string)  

**Returns** float


---

#### GetColor

**GetColor**(**index**: int, **count**: int): Color

**Parameters**

- **index** (int)  
- **count** (int)  

**Returns** Color

---

**GetColor**(**data**: [StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md)): Color

**Parameters**

- **data** ([StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md))  

**Returns** Color

---

**GetColor**(**data**: [StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md)): Color

**Parameters**

- **data** ([StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md))  

**Returns** Color


---

#### GetGeomBrush

**GetGeomBrush**(**data**: [StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md), **is3D**: bool): [Brush](../../../../Stimulsoft_Drawing/root/Brush.md)

**Parameters**

- **data** ([StiMapData](../../../../Stimulsoft_Report/Maps/StiMapData.md))  
- **is3D** (bool)  

**Returns** [Brush](../../../../Stimulsoft_Drawing/root/Brush.md)


---

#### GetMapStyle `static`

**GetMapStyle**(**map**: StiRegionMapElement): StiMapStyle

**Parameters**

- **map** (StiRegionMapElement)  

**Returns** StiMapStyle


---

#### Init

**Init**(**map**: StiRegionMapElement, **painter**: [StiGdiDbsMapContextPainter](StiGdiDbsMapContextPainter.md)): void

**Parameters**

- **map** (StiRegionMapElement)  
- **painter** ([StiGdiDbsMapContextPainter](StiGdiDbsMapContextPainter.md))  


---

#### Render

**Render**(**graphics**: [Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md), **useZoom**: bool): void

**Parameters**

- **graphics** ([Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md))  
- **useZoom** (bool)  

---

**Render**(**g**: [Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md), **useZoom**: bool, **rect**: [RectangleD](../../../../Stimulsoft_Base/Drawing/RectangleD.md), **center**: bool): void

**Parameters**

- **g** ([Graphics](../../../../Stimulsoft_Drawing/root/Graphics.md))  
- **useZoom** (bool)  
- **rect** ([RectangleD](../../../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **center** (bool)  


---

#### UpdateGroupedData

**UpdateGroupedData**(): void


---

#### UpdateHeatmapWithGroup

**UpdateHeatmapWithGroup**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **MaxValue** | double? |  |
| **MinValue** | double? |  |
