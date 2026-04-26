---
title: "StiCDataConnectCloudSource Class"
---

## StiCDataConnectCloudSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCDataConnectCloudSource**() |  |
| **StiCDataConnectCloudSource**(string nameInSource, string name) |  |
| **StiCDataConnectCloudSource**(string nameInSource, string name, string alias) |  |
| **StiCDataConnectCloudSource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiCDataConnectCloudSource**()

---

**StiCDataConnectCloudSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiCDataConnectCloudSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiCDataConnectCloudSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  


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

