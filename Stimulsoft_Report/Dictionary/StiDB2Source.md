---
title: "StiDB2Source Class"
---

## StiDB2Source Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDB2Source**() |  |
| **StiDB2Source**(string dataName, string name) |  |
| **StiDB2Source**(string dataName, string name, string alias) |  |
| **StiDB2Source**(string dataName, string name, string alias, string sqlCommand) |  |

**StiDB2Source**()

---

**StiDB2Source**(**dataName**: string, **name**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  

---

**StiDB2Source**(**dataName**: string, **name**: string, **alias**: string)

**Parameters**

- **dataName** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiDB2Source**(**dataName**: string, **name**: string, **alias**: string, **sqlCommand**: string)

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

