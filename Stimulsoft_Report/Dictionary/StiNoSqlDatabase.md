---
title: "StiNoSqlDatabase Class"
---

## StiNoSqlDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiNoSqlDatabase
```

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
| **CreateNoSqlConnector** | [StiNoSqlDataConnector](../../Stimulsoft_Base/StiNoSqlDataConnector.md) | Returns new sql data connector for this database. |
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
