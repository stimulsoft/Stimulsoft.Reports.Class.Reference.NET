---
title: "StiMongoDbDatabase Class"
---

## StiMongoDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMongoDbDatabase**() |  |
| **StiMongoDbDatabase**(string name, string connectionString) |  |
| **StiMongoDbDatabase**(string name, string alias, string connectionString) |  |
| **StiMongoDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiMongoDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiMongoDbDatabase**()

---

**StiMongoDbDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiMongoDbDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiMongoDbDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiMongoDbDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiNoSqlSource](StiNoSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiNoSqlSource](StiNoSqlSource.md)


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

