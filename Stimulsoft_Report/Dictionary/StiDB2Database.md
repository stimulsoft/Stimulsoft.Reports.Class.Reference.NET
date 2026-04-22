---
title: "StiDB2Database Class"
---

## StiDB2Database Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDB2Database
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDB2Database**() | Creates a new object of the type StiDB2Database. |
| **StiDB2Database**(string name, string connectionString) | Creates a new object of the type StiDB2Database. |
| **StiDB2Database**(string name, string alias, string connectionString) | Creates a new object of the type StiDB2Database. |
| **StiDB2Database**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiDB2Database. |
| **StiDB2Database**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiDB2Database. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
