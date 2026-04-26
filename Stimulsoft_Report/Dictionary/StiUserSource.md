---
title: "StiUserSource Class"
---

## StiUserSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the Data Source realizing access to UserSource.

### Inheritance

Inherits from: [StiDataStoreSource](StiDataStoreSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUserSource**() | Creates a new object of the type StiUserSource. |
| **StiUserSource**(string nameInSource, string name) | Creates a new object of the type StiUserSource. |
| **StiUserSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiUserSource. |
| **StiUserSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiUserSource. |
| **StiUserSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiUserSource. |

**StiUserSource**()

Creates a new object of the type StiUserSource.

---

**StiUserSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiUserSource.

**Parameters**

- **nameInSource** (string) — Name of UserSource in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiUserSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiUserSource.

**Parameters**

- **nameInSource** (string) — Name of UserSource in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiUserSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiUserSource.

**Parameters**

- **nameInSource** (string) — Name of UserSource in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  

---

**StiUserSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string, **reconnectOnEachRow**: bool)

Creates a new object of the type StiUserSource.

**Parameters**

- **nameInSource** (string) — Name of UserSource in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  
- **reconnectOnEachRow** (bool) — Reconnect on each master row in master-detail reports.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

