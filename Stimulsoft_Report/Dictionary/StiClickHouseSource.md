---
title: "StiClickHouseSource Class"
---

## StiClickHouseSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiClickHouseSource**() |  |
| **StiClickHouseSource**(string nameInSource, string name) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

**StiClickHouseSource**()

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  
- **commandTimeout** (int)  

---

**StiClickHouseSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int, **key**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  
- **commandTimeout** (int)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

