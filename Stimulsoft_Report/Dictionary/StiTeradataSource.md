---
title: "StiTeradataSource Class"
---

## StiTeradataSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTeradataSource**() |  |
| **StiTeradataSource**(string dataName, string name) |  |
| **StiTeradataSource**(string dataName, string name, string alias) |  |
| **StiTeradataSource**(string dataName, string name, string alias, string sqlCommand) |  |

**StiTeradataSource**()

---

**StiTeradataSource**(**dataName**: string, **name**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  

---

**StiTeradataSource**(**dataName**: string, **name**: string, **alias**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiTeradataSource**(**dataName**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this datasource.

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

