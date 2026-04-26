---
title: "StiSybaseAdsSource Class"
---

## StiSybaseAdsSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSybaseAdsSource**() |  |
| **StiSybaseAdsSource**(string nameInSource, string name) |  |
| **StiSybaseAdsSource**(string nameInSource, string name, string alias) |  |
| **StiSybaseAdsSource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiSybaseAdsSource**()

---

**StiSybaseAdsSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiSybaseAdsSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiSybaseAdsSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

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

