---
title: "StiVistaDBSource Class"
---

## StiVistaDBSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiVistaDBSource**() |  |
| **StiVistaDBSource**(string nameInSource, string name) |  |
| **StiVistaDBSource**(string nameInSource, string name, string alias) |  |
| **StiVistaDBSource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiVistaDBSource**()

---

**StiVistaDBSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiVistaDBSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiVistaDBSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

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

