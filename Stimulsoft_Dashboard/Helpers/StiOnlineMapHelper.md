---
title: "StiOnlineMapHelper Class"
---

## StiOnlineMapHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`

This class helps working with the online-map element.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalculateMapData** `static` | Hashtable |  |
| **GetBingMapScript** `static` | string |  |
| **GetGisMeterIndex** `static` | int |  |
| **GetLatitudeMeterIndex** `static` | int |  |
| **GetLocationArgumentMeterIndex** `static` | int |  |
| **GetLocationColorMeterIndex** `static` | int |  |
| **GetLocationMeterIndex** `static` | int |  |
| **GetLocationValueMeterIndex** `static` | int |  |
| **GetLongitudeMeterIndex** `static` | int |  |
| **ToUnits** `static` | string |  |

---

### Method Details

#### CalculateMapData `static`

**CalculateMapData**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **onlineMapElement**: StiOnlineMapElement): Hashtable

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **onlineMapElement** (StiOnlineMapElement)  

**Returns** Hashtable


---

#### GetBingMapScript `static`

**GetBingMapScript**(**element**: IStiElement, **showTitle**: bool): string

**Parameters**

- **element** (IStiElement)  
- **showTitle** (bool)  

**Returns** string


---

#### GetGisMeterIndex `static`

**GetGisMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetLatitudeMeterIndex `static`

**GetLatitudeMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetLocationArgumentMeterIndex `static`

**GetLocationArgumentMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetLocationColorMeterIndex `static`

**GetLocationColorMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetLocationMeterIndex `static`

**GetLocationMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetLocationValueMeterIndex `static`

**GetLocationValueMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetLongitudeMeterIndex `static`

**GetLongitudeMeterIndex**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### ToUnits `static`

**ToUnits**(**number**: double): string

**Parameters**

- **number** (double)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Lat** | decimal |  |
| **Lon** | decimal |  |
| **MAX_SIZE** | byte |  |
| **Weight** | byte |  |
