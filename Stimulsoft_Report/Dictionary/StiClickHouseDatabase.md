---
title: "StiClickHouseDatabase Class"
---

## StiClickHouseDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiClickHouseDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiClickHouseDatabase()` |  |
| `StiClickHouseDatabase(string name, string connectionString)` |  |
| `StiClickHouseDatabase(string name, string alias, string connectionString)` |  |
| `StiClickHouseDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiClickHouseDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) |  |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
