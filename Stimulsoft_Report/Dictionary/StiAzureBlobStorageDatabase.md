---
title: "StiAzureBlobStorageDatabase Class"
---

## StiAzureBlobStorageDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAzureBlobStorageDatabase**() |  |
| **StiAzureBlobStorageDatabase**(string name, string connectionString) |  |
| **StiAzureBlobStorageDatabase**(string name, string alias, string connectionString) |  |
| **StiAzureBlobStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiAzureBlobStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiAzureBlobStorageDatabase**()

---

**StiAzureBlobStorageDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiAzureBlobStorageDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiAzureBlobStorageDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiAzureBlobStorageDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### ApplyDatabaseInformationSource

**ApplyDatabaseInformationSource**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md), **dataTable**: DataTable, **type**: [StiSqlSourceType](StiSqlSourceType.md)): void

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **dataTable** (DataTable)  
- **type** ([StiSqlSourceType](StiSqlSourceType.md))  


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

#### Edit

**Edit**(**dictionary**: StiDictionary, **isNewDatabase**: bool): DialogResult

**Parameters**

- **dictionary** (StiDictionary)  
- **isNewDatabase** (bool)  

**Returns** DialogResult


---

#### EditAsync

**EditAsync**(**dictionary**: StiDictionary, **isNewDatabase**: bool): Task<DialogResult>

**Parameters**

- **dictionary** (StiDictionary)  
- **isNewDatabase** (bool)  

**Returns** Task<DialogResult>


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AccountKey** | string |  |
| **AccountName** | string |  |
| **BlobContentType** | string |  |
| **BlobName** | string |  |
| **CodePage** | int |  |
| **ContainerName** | string |  |
| **Delimiter** | string |  |
| **FirstRowIsHeader** | bool |  |
