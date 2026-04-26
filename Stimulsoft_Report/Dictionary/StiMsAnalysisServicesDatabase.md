---
title: "StiMsAnalysisServicesDatabase Class"
---

## StiMsAnalysisServicesDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMsAnalysisServicesDatabase**() |  |
| **StiMsAnalysisServicesDatabase**(string name, string connectionString) |  |
| **StiMsAnalysisServicesDatabase**(string name, string alias, string connectionString) |  |
| **StiMsAnalysisServicesDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiMsAnalysisServicesDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiMsAnalysisServicesDatabase**()

---

**StiMsAnalysisServicesDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiMsAnalysisServicesDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiMsAnalysisServicesDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiMsAnalysisServicesDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) |  |

---

### Method Details

#### ApplyDatabaseInformation

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md)): void

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

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiNoSqlSource](StiNoSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiNoSqlSource](StiNoSqlSource.md)


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


---

#### GetDatabaseInformation

**GetDatabaseInformation**(**report**: [StiReport](../root/StiReport.md)): [StiDatabaseInformation](StiDatabaseInformation.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [StiDatabaseInformation](StiDatabaseInformation.md)

