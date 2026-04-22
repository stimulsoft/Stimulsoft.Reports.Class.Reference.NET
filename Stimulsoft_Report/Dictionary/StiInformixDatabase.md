---
title: "StiInformixDatabase Class"
---

## StiInformixDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiInformixDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiInformixDatabase**() | Creates a new object of the type StiInformixDatabase. |
| **StiInformixDatabase**(string name, string connectionString) | Creates a new object of the type StiInformixDatabase. |
| **StiInformixDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiInformixDatabase. |
| **StiInformixDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiInformixDatabase. |
| **StiInformixDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiInformixDatabase. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
