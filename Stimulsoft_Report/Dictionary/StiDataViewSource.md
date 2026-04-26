---
title: "StiDataViewSource Class"
---

## StiDataViewSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the Data Source realizing access to DataView.

### Inheritance

Inherits from: [StiDataStoreSource](StiDataStoreSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataViewSource**() | Creates a new object of the type StiDataViewSource. |
| **StiDataViewSource**(string nameInSource, string name) | Creates a new object of the type StiDataViewSource. |
| **StiDataViewSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiDataViewSource. |
| **StiDataViewSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiDataViewSource. |
| **StiDataViewSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiDataViewSource. |

**StiDataViewSource**()

Creates a new object of the type StiDataViewSource.

---

**StiDataViewSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiDataViewSource.

**Parameters**

- **nameInSource** (string) — Name of DataView in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiDataViewSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiDataViewSource.

**Parameters**

- **nameInSource** (string) — Name of DataView in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiDataViewSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiDataViewSource.

**Parameters**

- **nameInSource** (string) — Name of DataView in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  

---

**StiDataViewSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string, **reconnectOnEachRow**: bool)

Creates a new object of the type StiDataViewSource.

**Parameters**

- **nameInSource** (string) — Name of DataView in the DataStore.  
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

