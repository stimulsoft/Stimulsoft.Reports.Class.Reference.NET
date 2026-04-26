---
title: "StiGoogleAnalyticsDatabase Class"
---

## StiGoogleAnalyticsDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Google`

### Inheritance

Inherits from: [StiNoSqlDatabase](../../StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGoogleAnalyticsDatabase**() |  |
| **StiGoogleAnalyticsDatabase**(string name, string connectionString) |  |
| **StiGoogleAnalyticsDatabase**(string name, string alias, string connectionString) |  |
| **StiGoogleAnalyticsDatabase**(string name, string alias, string connectionString, bool promptUserNameAndPassword) |  |
| **StiGoogleAnalyticsDatabase**(string name, string alias, string connectionString, bool promptUserNameAndPassword, string key) |  |

**StiGoogleAnalyticsDatabase**()

---

**StiGoogleAnalyticsDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiGoogleAnalyticsDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiGoogleAnalyticsDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndPassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndPassword** (bool)  

---

**StiGoogleAnalyticsDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndPassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndPassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](../../StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### ApplyDatabaseInformationSource

**ApplyDatabaseInformationSource**(**information**: [StiDatabaseInformation](../../StiDatabaseInformation.md), **report**: [StiReport](../../../root/StiReport.md), **informationAll**: [StiDatabaseInformation](../../StiDatabaseInformation.md), **dataTable**: DataTable, **type**: [StiSqlSourceType](../../StiSqlSourceType.md)): void

**Parameters**

- **information** ([StiDatabaseInformation](../../StiDatabaseInformation.md))  
- **report** ([StiReport](../../../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](../../StiDatabaseInformation.md))  
- **dataTable** (DataTable)  
- **type** ([StiSqlSourceType](../../StiSqlSourceType.md))  


---

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
| **AccountId** | string |  |
| **Base64EncodedAuthSecret** | string |  |
| **Dimensions** | string |  |
| **EndDate** | string |  |
| **Metrics** | string |  |
| **PropertyId** | string |  |
| **StartDate** | string |  |
| **ViewId** | string |  |
