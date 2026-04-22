---
title: "StiMariaDbDatabase Class"
---

## StiMariaDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMariaDbDatabase
```

### Inheritance

Inherits from: StiMySqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMariaDbDatabase()` | Creates a new object of the type StiMariaDbDatabase. |
| `StiMariaDbDatabase(string name, string connectionString)` | Creates a new object of the type StiMariaDbDatabase. |
| `StiMariaDbDatabase(string name, string alias, string connectionString)` | Creates a new object of the type StiMariaDbDatabase. |
| `StiMariaDbDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` | Creates a new object of the type StiMariaDbDatabase. |
| `StiMariaDbDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` | Creates a new object of the type StiMariaDbDatabase. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetDataAdapterType** | Type |  |
