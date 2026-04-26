---
title: "StiEnumerableSource Class"
---

## StiEnumerableSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the Data Source realizing access to IEnumerable. This type of data source is obsolete.

### Inheritance

Inherits from: [StiBusinessObjectSource](StiBusinessObjectSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEnumerableSource**() | Creates a new object of the type StiEnumerableSource. |
| **StiEnumerableSource**(string nameInSource, string name) | Creates a new object of the type StiEnumerableSource. |
| **StiEnumerableSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiEnumerableSource. |
| **StiEnumerableSource**(string nameInSource, string name, string alias, string key) | Creates a new object of the type StiEnumerableSource. |
| **StiEnumerableSource**(string nameInSource, string name, string alias, string key, bool reconnectOnEachRow) | Creates a new object of the type StiEnumerableSource. |

**StiEnumerableSource**()

Creates a new object of the type StiEnumerableSource.

---

**StiEnumerableSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiEnumerableSource.

**Parameters**

- **nameInSource** (string) — Name of IEnumerable in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiEnumerableSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiEnumerableSource.

**Parameters**

- **nameInSource** (string) — Name of IEnumerable in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiEnumerableSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiEnumerableSource.

**Parameters**

- **nameInSource** (string) — Name of IEnumerable in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  

---

**StiEnumerableSource**(**nameInSource**: string, **name**: string, **alias**: string, **key**: string, **reconnectOnEachRow**: bool)

Creates a new object of the type StiEnumerableSource.

**Parameters**

- **nameInSource** (string) — Name of IEnumerable in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  
- **reconnectOnEachRow** (bool) — Reconnect on each master row in master-detail reports.  

