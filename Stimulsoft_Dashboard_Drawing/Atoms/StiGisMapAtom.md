---
title: "StiGisMapAtom Class"
---

## StiGisMapAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisMapAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, bool isExporting) |  |

**StiGisMapAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **isExporting**: bool)

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **isExporting** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetObjectValues** | List<object> |  |
| **GetStringValues** | List<string> |  |
| **Paint** | void |  |
| **Render** | void |  |

---

### Method Details

#### GetObjectValues

**GetObjectValues**(**meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)): List<object>

**Parameters**

- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** List<object>


---

#### GetStringValues

**GetStringValues**(**meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)): List<string>

**Parameters**

- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** List<string>


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
| **OnlineMapElement** | StiOnlineMapElement |  |
| **Size** | Size |  |
