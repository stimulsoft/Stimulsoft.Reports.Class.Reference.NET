---
title: "StiDataStoreSource Class"
---

## StiDataStoreSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiDataSource  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataStoreSource**() | Creates a new object of the type StiDataStoreSource. |
| **StiDataStoreSource**(string nameInSource, string name) | Creates a new object of the type StiDataTableSource. |
| **StiDataStoreSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiDataStoreSource. |
| **StiDataStoreSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiDataStoreSource. |
| **StiDataStoreSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiDataStoreSource. |

**StiDataStoreSource**()

Creates a new object of the type StiDataStoreSource.

---

**StiDataStoreSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiDataTableSource.

**Parameters**

- **nameInSource** (string) — Name of data in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiDataStoreSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiDataStoreSource.

**Parameters**

- **nameInSource** (string) — Name of data in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiDataStoreSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiDataStoreSource.

**Parameters**

- **nameInSource** (string) — Name of data in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string)  

---

**StiDataStoreSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string, **reconnectOnEachRow**: bool)

Creates a new object of the type StiDataStoreSource.

**Parameters**

- **nameInSource** (string) — Name of data in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string)  
- **reconnectOnEachRow** (bool) — Reconnect on each master row in master-detail reports.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NameInSource** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCategoryName** | string | Returns the name to categories of the Data Source. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetCategoryName

**GetCategoryName**(): string

Returns the name to categories of the Data Source.

**Returns** string


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

