---
title: "StiCosmosDbDatabase Class"
---

## StiCosmosDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Azure`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCosmosDbDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](../../StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCosmosDbDatabase()` |  |
| `StiCosmosDbDatabase(string name, string connectionString)` |  |
| `StiCosmosDbDatabase(string name, string alias, string connectionString)` |  |
| `StiCosmosDbDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiCosmosDbDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](../../StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |
