---
title: "StiGoogleSheetsDatabase Class"
---

## StiGoogleSheetsDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Google`

### Inheritance

Inherits from: StiDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGoogleSheetsDatabase**() |  |
| **StiGoogleSheetsDatabase**(string name, string alias, string key, string clientId, string clientSecret, string spreadsheetId, bool firstRowIsHeader) |  |

**StiGoogleSheetsDatabase**()

---

**StiGoogleSheetsDatabase**(**name**: string, **alias**: string, **key**: string, **clientId**: string, **clientSecret**: string, **spreadsheetId**: string, **firstRowIsHeader**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **key** (string)  
- **clientId** (string)  
- **clientSecret** (string)  
- **spreadsheetId** (string)  
- **firstRowIsHeader** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClientId** | string |  |
| **ClientSecret** | string |  |
| **FirstRowIsHeader** | bool |  |
| **SpreadsheetId** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** *(+1 overloads)* | void | Adds tables, views and stored procedures to report dictionary from database information. |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateGoogleSheetsConnector** | [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapter** | [StiGoogleSheetsAdapterService](../../Adapters/Google/StiGoogleSheetsAdapterService.md) |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](../../StiDatabaseInformation.md) | Returns full database information. |
| **GetDatabaseInformationTables** | List<DataTable> |  |
| **RegData** | void | Registers the database in dictionary. |

---

### Method Details

#### ApplyDatabaseInformation

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](../../StiDatabaseInformation.md), **report**: [StiReport](../../../root/StiReport.md)): void

Adds tables, views and stored procedures to report dictionary from database information.

**Parameters**

- **information** ([StiDatabaseInformation](../../StiDatabaseInformation.md))  
- **report** ([StiReport](../../../root/StiReport.md))  

---

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](../../StiDatabaseInformation.md), **report**: [StiReport](../../../root/StiReport.md), **informationAll**: [StiDatabaseInformation](../../StiDatabaseInformation.md)): void

Adds tables, views and stored procedures to report dictionary from database information.

**Parameters**

- **information** ([StiDatabaseInformation](../../StiDatabaseInformation.md))  
- **report** ([StiReport](../../../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](../../StiDatabaseInformation.md))  


---

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

#### CreateGoogleSheetsConnector

**CreateGoogleSheetsConnector**(): [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md)

**Returns** [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md)


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

#### GetDataAdapter

**GetDataAdapter**(): [StiGoogleSheetsAdapterService](../../Adapters/Google/StiGoogleSheetsAdapterService.md)

**Returns** [StiGoogleSheetsAdapterService](../../Adapters/Google/StiGoogleSheetsAdapterService.md)


---

#### GetDatabaseInformation

**GetDatabaseInformation**(**report**: [StiReport](../../../root/StiReport.md)): [StiDatabaseInformation](../../StiDatabaseInformation.md)

Returns full database information.

**Parameters**

- **report** ([StiReport](../../../root/StiReport.md))  

**Returns** [StiDatabaseInformation](../../StiDatabaseInformation.md)


---

#### GetDatabaseInformationTables

**GetDatabaseInformationTables**(**dataSchema**: [StiDataSchema](../../../../Stimulsoft_Base/root/StiDataSchema.md)): List<DataTable>

**Parameters**

- **dataSchema** ([StiDataSchema](../../../../Stimulsoft_Base/root/StiDataSchema.md))  

**Returns** List<DataTable>


---

#### RegData

**RegData**(**dictionary**: StiDictionary, **loadData**: bool): void

Registers the database in dictionary.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which is registered database.  
- **loadData** (bool) — Load the data or no.  

