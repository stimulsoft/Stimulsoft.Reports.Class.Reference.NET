---
title: "StiMongoDbDatabase Class"
---

## StiMongoDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMongoDbDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMongoDbDatabase()` |  |
| `StiMongoDbDatabase(string name, string connectionString)` |  |
| `StiMongoDbDatabase(string name, string alias, string connectionString)` |  |
| `StiMongoDbDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiMongoDbDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |
