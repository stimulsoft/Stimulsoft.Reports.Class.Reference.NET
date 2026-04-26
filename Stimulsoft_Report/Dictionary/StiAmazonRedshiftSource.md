---
title: "StiAmazonRedshiftSource Class"
---

## StiAmazonRedshiftSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiPostgreSQLSource](StiPostgreSQLSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAmazonRedshiftSource**() |  |
| **StiAmazonRedshiftSource**(string nameInSource, string name) |  |
| **StiAmazonRedshiftSource**(string nameInSource, string name, string alias) |  |
| **StiAmazonRedshiftSource**(string nameInSource, string name, string alias, string sqlCommand) |  |

**StiAmazonRedshiftSource**()

---

**StiAmazonRedshiftSource**(**nameInSource**: string, **name**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

---

**StiAmazonRedshiftSource**(**nameInSource**: string, **name**: string, **alias**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  

---

**StiAmazonRedshiftSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

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

