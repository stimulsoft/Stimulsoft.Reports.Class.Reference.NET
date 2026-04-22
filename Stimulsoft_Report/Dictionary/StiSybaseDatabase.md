---
title: "StiSybaseDatabase Class"
---

## StiSybaseDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiSybaseDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSybaseDatabase**() | Creates a new object of the type StiSybaseDatabase. |
| **StiSybaseDatabase**(string name, string connectionString) | Creates a new object of the type StiSybaseDatabase. |
| **StiSybaseDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiSybaseDatabase. |
| **StiSybaseDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiSybaseDatabase. |
| **StiSybaseDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiSybaseDatabase. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |
