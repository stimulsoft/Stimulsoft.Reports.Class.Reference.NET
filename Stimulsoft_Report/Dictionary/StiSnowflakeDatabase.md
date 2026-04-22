---
title: "StiSnowflakeDatabase Class"
---

## StiSnowflakeDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiSnowflakeDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSnowflakeDatabase()` |  |
| `StiSnowflakeDatabase(string name, string connectionString)` |  |
| `StiSnowflakeDatabase(string name, string alias, string connectionString)` |  |
| `StiSnowflakeDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiSnowflakeDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) |  |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
