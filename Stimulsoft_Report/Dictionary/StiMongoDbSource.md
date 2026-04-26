---
title: "StiMongoDbSource Class"
---

## StiMongoDbSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlSource](StiNoSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMongoDbSource**() |  |
| **StiMongoDbSource**(string nameInSource, string name) |  |
| **StiMongoDbSource**(string nameInSource, string name, string alias) |  |
| **StiMongoDbSource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiMongoDbSource**()

---

**StiMongoDbSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiMongoDbSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiMongoDbSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **nameInSource** (string)  
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

