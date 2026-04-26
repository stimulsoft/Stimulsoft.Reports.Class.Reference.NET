---
title: "StiAzureTableStorageDatabase Class"
---

## StiAzureTableStorageDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAzureTableStorageDatabase**() |  |
| **StiAzureTableStorageDatabase**(string name, string connectionString) |  |
| **StiAzureTableStorageDatabase**(string name, string alias, string connectionString) |  |
| **StiAzureTableStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiAzureTableStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiAzureTableStorageDatabase**()

---

**StiAzureTableStorageDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiAzureTableStorageDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiAzureTableStorageDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiAzureTableStorageDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

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

