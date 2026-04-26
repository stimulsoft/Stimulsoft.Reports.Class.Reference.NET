---
title: "StiCosmosDbDatabase Class"
---

## StiCosmosDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Azure`

### Inheritance

Inherits from: [StiNoSqlDatabase](../../StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCosmosDbDatabase**() |  |
| **StiCosmosDbDatabase**(string name, string connectionString) |  |
| **StiCosmosDbDatabase**(string name, string alias, string connectionString) |  |
| **StiCosmosDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiCosmosDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiCosmosDbDatabase**()

---

**StiCosmosDbDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiCosmosDbDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiCosmosDbDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiCosmosDbDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](../../StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md)


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiNoSqlSource](../../StiNoSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiNoSqlSource](../../StiNoSqlSource.md)


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

