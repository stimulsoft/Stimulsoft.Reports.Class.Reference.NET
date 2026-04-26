---
title: "StiGisElementControl Class"
---

## StiGisElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.Table`

### Inheritance

Inherits from: StiElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisElementControl**(IStiElement element) |  |

**StiGisElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateChild** | void |  |
| **GetObjectValues** | List<object> |  |
| **GetOrCreateData** | [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **GetStringValues** | List<string> |  |
| **RefreshChild** | void |  |

---

### Method Details

#### CreateChild

**CreateChild**(): void


---

#### GetObjectValues

**GetObjectValues**(**meter**: [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md)): List<object>

**Parameters**

- **meter** ([IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** List<object>


---

#### GetOrCreateData

**GetOrCreateData**(): [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)

**Returns** [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)


---

#### GetStringValues

**GetStringValues**(**meter**: [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md)): List<string>

**Parameters**

- **meter** ([IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** List<string>


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **OnlineMapElement** | StiOnlineMapElement |  |
