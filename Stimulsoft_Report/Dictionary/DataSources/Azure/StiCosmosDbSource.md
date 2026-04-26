---
title: "StiCosmosDbSource Class"
---

## StiCosmosDbSource Class

**Namespace:** `Stimulsoft.Report.Dictionary.DataSources.Azure`

### Inheritance

Inherits from: [StiNoSqlSource](../../StiNoSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCosmosDbSource**() |  |
| **StiCosmosDbSource**(string nameInSource, string name) |  |
| **StiCosmosDbSource**(string nameInSource, string name, string alias) |  |
| **StiCosmosDbSource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiCosmosDbSource**()

---

**StiCosmosDbSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiCosmosDbSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiCosmosDbSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../../../Stimulsoft_Base/root/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this datasource.

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

