---
title: "StiNoSqlDatabase Class"
---

## StiNoSqlDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiNoSqlDatabase**() |  |
| **StiNoSqlDatabase**(string name, string connectionString) |  |
| **StiNoSqlDatabase**(string name, string alias, string connectionString) |  |
| **StiNoSqlDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiNoSqlDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiNoSqlDatabase**()

---

**StiNoSqlDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiNoSqlDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiNoSqlDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiNoSqlDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionString** | string |  |
| **PromptUserNameAndPassword** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** *(+1 overloads)* | void | Adds tables, views and stored procedures to report dictionary from database information. |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **CreateNoSqlConnector** | [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) | Returns new sql data connector for this database. |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **EditConnectionString** | string |  |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapter** | [StiNoSqlAdapterService](StiNoSqlAdapterService.md) |  |
| **GetDataAdapterType** | Type |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) | Returns full database information. |
| **GetDatabaseInformationTables** | List<DataTable> |  |
| **LoadFromJsonObject** | void |  |
| **MapUserNameAndPassword** | string |  |
| **RegData** | void | Registers the database in dictionary. |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ApplyDatabaseInformation

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md)): void

Adds tables, views and stored procedures to report dictionary from database information.

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](StiDatabaseInformation.md))  

---

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md)): void

Adds tables, views and stored procedures to report dictionary from database information.

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  


---

#### ApplyDatabaseInformationSource

**ApplyDatabaseInformationSource**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md), **dataTable**: DataTable, **type**: [StiSqlSourceType](StiSqlSourceType.md)): void

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **dataTable** (DataTable)  
- **type** ([StiSqlSourceType](StiSqlSourceType.md))  


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiNoSqlSource](StiNoSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiNoSqlSource](StiNoSqlSource.md)


---

#### CreateNoSqlConnector

**CreateNoSqlConnector**(**connectionString**: string): [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md)

Returns new sql data connector for this database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) — Created sql connector.


---

#### Edit

**Edit**(**dictionary**: StiDictionary, **newDatabase**: bool): DialogResult

**Parameters**

- **dictionary** (StiDictionary)  
- **newDatabase** (bool)  

**Returns** DialogResult


---

#### EditAsync

**EditAsync**(**dictionary**: StiDictionary, **newDatabase**: bool): Task<DialogResult>

**Parameters**

- **dictionary** (StiDictionary)  
- **newDatabase** (bool)  

**Returns** Task<DialogResult>


---

#### EditConnectionString

**EditConnectionString**(**connectionString**: string): string

**Parameters**

- **connectionString** (string)  

**Returns** string


---

#### GetConnectionStringHelper

**GetConnectionStringHelper**(): string

**Returns** string


---

#### GetDataAdapter

**GetDataAdapter**(): [StiNoSqlAdapterService](StiNoSqlAdapterService.md)

**Returns** [StiNoSqlAdapterService](StiNoSqlAdapterService.md)


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


---

#### GetDatabaseInformation

**GetDatabaseInformation**(**report**: [StiReport](../root/StiReport.md)): [StiDatabaseInformation](StiDatabaseInformation.md)

Returns full database information.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [StiDatabaseInformation](StiDatabaseInformation.md)


---

#### GetDatabaseInformationTables

**GetDatabaseInformationTables**(**dataSchema**: [StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md)): List<DataTable>

**Parameters**

- **dataSchema** ([StiDataSchema](../../Stimulsoft_Base/root/StiDataSchema.md))  

**Returns** List<DataTable>


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### MapUserNameAndPassword

**MapUserNameAndPassword**(**userName**: string, **password**: string): string

**Parameters**

- **userName** (string)  
- **password** (string)  

**Returns** string


---

#### RegData

**RegData**(**dictionary**: StiDictionary, **loadData**: bool): void

Registers the database in dictionary.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which is registered database.  
- **loadData** (bool) — Load the data or no.  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

