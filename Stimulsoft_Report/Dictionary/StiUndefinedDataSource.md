---
title: "StiUndefinedDataSource Class"
---

## StiUndefinedDataSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUndefinedDataSource**() | Creates a new object of the type StiUndefinedDataSource. |
| **StiUndefinedDataSource**(string nameInSource, string name) | Creates a new object of the type StiUndefinedDataSource. |
| **StiUndefinedDataSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiSqlSource. |
| **StiUndefinedDataSource**(string nameInSource, string name, string alias, string sqlCommand) | Creates a new object of the type StiSqlSource. |
| **StiUndefinedDataSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

**StiUndefinedDataSource**()

Creates a new object of the type StiUndefinedDataSource.

---

**StiUndefinedDataSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiUndefinedDataSource.

**Parameters**

- **nameInSource** (string) — Name of Sql Connection in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiUndefinedDataSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiSqlSource.

**Parameters**

- **nameInSource** (string) — Name of Sql Connection in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiUndefinedDataSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

Creates a new object of the type StiSqlSource.

**Parameters**

- **nameInSource** (string) — Name of SqlConnection in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **sqlCommand** (string) — SQL statement to execute at the Data Source.  

---

**StiUndefinedDataSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int, **key**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  
- **commandTimeout** (int)  
- **key** (string)  

