---
title: "StiDataTableSource Class"
---

## StiDataTableSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the Data Source realizing access to DataTable.

### Inheritance

Inherits from: [StiDataStoreSource](StiDataStoreSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataTableSource**() | Creates a new object of the type StiDataTableSource. |
| **StiDataTableSource**(string nameInSource, string name) | Creates a new object of the type StiDataTableSource. |
| **StiDataTableSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiDataTableSource. |
| **StiDataTableSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiDataTableSource. |
| **StiDataTableSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiDataTableSource. |

**StiDataTableSource**()

Creates a new object of the type StiDataTableSource.

---

**StiDataTableSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiDataTableSource.

**Parameters**

- **nameInSource** (string) — Name of DataTable in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiDataTableSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiDataTableSource.

**Parameters**

- **nameInSource** (string) — Name of DataTable in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiDataTableSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiDataTableSource.

**Parameters**

- **nameInSource** (string) — Name of DataTable in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  

---

**StiDataTableSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string, **reconnectOnEachRow**: bool)

Creates a new object of the type StiDataTableSource.

**Parameters**

- **nameInSource** (string) — Name of DataTable in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  
- **reconnectOnEachRow** (bool) — Reconnect on each master row in master-detail reports.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCategoryName** | string |  |
| **GetDataAdapterType** | Type |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetCategoryName

**GetCategoryName**(): string

**Returns** string


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

