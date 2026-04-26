---
title: "StiCDataConnectCloudDatabase Class"
---

## StiCDataConnectCloudDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCDataConnectCloudDatabase**() |  |
| **StiCDataConnectCloudDatabase**(string name, string connectionString) |  |
| **StiCDataConnectCloudDatabase**(string name, string alias, string connectionString) |  |
| **StiCDataConnectCloudDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiCDataConnectCloudDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiCDataConnectCloudDatabase**()

---

**StiCDataConnectCloudDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiCDataConnectCloudDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiCDataConnectCloudDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiCDataConnectCloudDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationProcedures** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) |  |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### ApplyDatabaseInformationProcedures

**ApplyDatabaseInformationProcedures**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md)): void

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](StiDatabaseInformation.md))  


---

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiSqlSource](StiSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiSqlSource](StiSqlSource.md)


---

#### GetConnectionStringHelper

**GetConnectionStringHelper**(): string

**Returns** string


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

