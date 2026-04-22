---
title: "StiGraphQLDatabase Class"
---

## StiGraphQLDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGraphQLDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiGraphQLDatabase()` |  |
| `StiGraphQLDatabase(string name, string connectionString)` |  |
| `StiGraphQLDatabase(string name, string alias, string connectionString)` |  |
| `StiGraphQLDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiGraphQLDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **EndPoint** | string |  |
| **Headers** | string |  |
| **Query** | string |  |
