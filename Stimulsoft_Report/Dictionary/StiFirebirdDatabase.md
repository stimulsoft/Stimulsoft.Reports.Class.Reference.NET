---
title: "StiFirebirdDatabase Class"
---

## StiFirebirdDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFirebirdDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiFirebirdDatabase()` | Creates a new object of the type StiFirebirdDatabase. |
| `StiFirebirdDatabase(string name, string connectionString)` | Creates a new object of the type StiFirebirdDatabase. |
| `StiFirebirdDatabase(string name, string alias, string connectionString)` | Creates a new object of the type StiFirebirdDatabase. |
| `StiFirebirdDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` | Creates a new object of the type StiFirebirdDatabase. |
| `StiFirebirdDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` | Creates a new object of the type StiFirebirdDatabase. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
