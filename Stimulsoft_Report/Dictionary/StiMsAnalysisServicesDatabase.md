---
title: "StiMsAnalysisServicesDatabase Class"
---

## StiMsAnalysisServicesDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMsAnalysisServicesDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMsAnalysisServicesDatabase()` |  |
| `StiMsAnalysisServicesDatabase(string name, string connectionString)` |  |
| `StiMsAnalysisServicesDatabase(string name, string alias, string connectionString)` |  |
| `StiMsAnalysisServicesDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiMsAnalysisServicesDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) |  |
