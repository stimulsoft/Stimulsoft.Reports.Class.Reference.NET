---
title: "StiTeradataDatabase Class"
---

## StiTeradataDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiTeradataDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiTeradataDatabase()` | Creates a new object of the type StiTeradataDatabase. |
| `StiTeradataDatabase(string name, string connectionString)` | Creates a new object of the type StiTeradataDatabase. |
| `StiTeradataDatabase(string name, string alias, string connectionString)` | Creates a new object of the type StiTeradataDatabase. |
| `StiTeradataDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` | Creates a new object of the type StiTeradataDatabase. |
| `StiTeradataDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` | Creates a new object of the type StiTeradataDatabase. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
