---
title: "StiBusinessObjectSource Class"
---

## StiBusinessObjectSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the Data Source realizing access to Business Objects.

### Inheritance

Inherits from: [StiDataTableSource](StiDataTableSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBusinessObjectSource**() | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name) | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiBusinessObjectSource. |
| **StiBusinessObjectSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiBusinessObjectSource. |

**StiBusinessObjectSource**()

Creates a new object of the type StiBusinessObjectSource.

---

**StiBusinessObjectSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiBusinessObjectSource.

**Parameters**

- **nameInSource** (string) — Name of business object.  
- **name** (string) — Data Source name.  

---

**StiBusinessObjectSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiBusinessObjectSource.

**Parameters**

- **nameInSource** (string) — Name of business object.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiBusinessObjectSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiBusinessObjectSource.

**Parameters**

- **nameInSource** (string) — Name of business object.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  

---

**StiBusinessObjectSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string, **reconnectOnEachRow**: bool)

Creates a new object of the type StiBusinessObjectSource.

**Parameters**

- **nameInSource** (string) — Name of data in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  
- **reconnectOnEachRow** (bool) — Reconnect on each master row in master-detail reports.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCategoryName** | string | Returns the name to categories of the Data Source. |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### GetCategoryName

**GetCategoryName**(): string

Returns the name to categories of the Data Source.

**Returns** string


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

