---
title: "StiSnowflakeSource Class"
---

## StiSnowflakeSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSnowflakeSource**() |  |
| **StiSnowflakeSource**(string nameInSource, string name) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

**StiSnowflakeSource**()

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  
- **commandTimeout** (int)  

---

**StiSnowflakeSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int, **key**: string)

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

