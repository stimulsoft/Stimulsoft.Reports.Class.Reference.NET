---
title: "StiInformixSource Class"
---

## StiInformixSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiInformixSource**() |  |
| **StiInformixSource**(string dataName, string name) |  |
| **StiInformixSource**(string dataName, string name, string alias) |  |
| **StiInformixSource**(string dataName, string name, string alias, string sqlCommand) |  |

**StiInformixSource**()

---

**StiInformixSource**(**dataName**: string, **name**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  

---

**StiInformixSource**(**dataName**: string, **name**: string, **alias**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiInformixSource**(**dataName**: string, **name**: string, **alias**: string, **sqlCommand**: string)

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

