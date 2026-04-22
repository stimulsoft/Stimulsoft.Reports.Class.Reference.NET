---
title: "StiCDataConnectCloudDatabase Class"
---

## StiCDataConnectCloudDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCDataConnectCloudDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCDataConnectCloudDatabase()` |  |
| `StiCDataConnectCloudDatabase(string name, string connectionString)` |  |
| `StiCDataConnectCloudDatabase(string name, string alias, string connectionString)` |  |
| `StiCDataConnectCloudDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiCDataConnectCloudDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationProcedures** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) |  |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
