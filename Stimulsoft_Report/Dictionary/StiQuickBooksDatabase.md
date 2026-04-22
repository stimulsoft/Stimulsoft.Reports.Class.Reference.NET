---
title: "StiQuickBooksDatabase Class"
---

## StiQuickBooksDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiQuickBooksDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiQuickBooksDatabase()` |  |
| `StiQuickBooksDatabase(string name, string connectionString)` |  |
| `StiQuickBooksDatabase(string name, string alias, string connectionString)` |  |
| `StiQuickBooksDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiQuickBooksDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |
| **RegData** | void |  |
