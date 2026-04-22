---
title: "StiGoogleSheetsDatabase Class"
---

## StiGoogleSheetsDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Google`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGoogleSheetsDatabase
```

### Inheritance

Inherits from: StiDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGoogleSheetsDatabase**() |  |
| **StiGoogleSheetsDatabase**(string name, string alias, string key, string clientId, string clientSecret, string spreadsheetId, bool firstRowIsHeader) |  |

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
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateGoogleSheetsConnector** | [StiGoogleSheetsConnector](../../../../Stimulsoft_Base/Data/Connectors/Google/StiGoogleSheetsConnector.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapter** | [StiGoogleSheetsAdapterService](../../Adapters/Google/StiGoogleSheetsAdapterService.md) |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](../../StiDatabaseInformation.md) | Returns full database information. |
| **GetDatabaseInformationTables** | List<DataTable> |  |
| **RegData** | void | Registers the database in dictionary. |
