---
title: "StiRegionMapAtom Class"
---

## StiRegionMapAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRegionMapAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |
| **StiRegionMapAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) animation) |  |

**StiRegionMapAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

---

**StiRegionMapAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **animation**: [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **animation** ([StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CheckedMapKeys** | List<string> |  |
| **MouseOverMapKey** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetValues** | List<object> |  |
| **Paint** | void |  |
| **Render** | void |  |

---

### Method Details

#### GetValues

**GetValues**(**meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)): List<object>

**Parameters**

- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** List<object>


---

#### Paint

**Paint**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### Render

**Render**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **RegionMapElement** | StiRegionMapElement |  |
