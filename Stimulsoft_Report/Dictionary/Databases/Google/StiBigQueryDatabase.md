---
title: "StiBigQueryDatabase Class"
---

## StiBigQueryDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Google`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiBigQueryDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](../../StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiBigQueryDatabase()` |  |
| `StiBigQueryDatabase(string name, string connectionString)` |  |
| `StiBigQueryDatabase(string name, string alias, string connectionString)` |  |
| `StiBigQueryDatabase(string name, string alias, string connectionString, bool promptUserNameAndPassword)` |  |
| `StiBigQueryDatabase(string name, string alias, string connectionString, bool promptUserNameAndPassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](../../StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Base64EncodedAuthSecret** | string |  |
| **DatasetId** | string |  |
| **ProjectId** | string |  |
