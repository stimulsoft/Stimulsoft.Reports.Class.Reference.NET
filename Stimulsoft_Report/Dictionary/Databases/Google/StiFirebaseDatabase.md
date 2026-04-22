---
title: "StiFirebaseDatabase Class"
---

## StiFirebaseDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Google`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFirebaseDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](../../StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiFirebaseDatabase()` |  |
| `StiFirebaseDatabase(string name, string connectionString)` |  |
| `StiFirebaseDatabase(string name, string alias, string connectionString)` |  |
| `StiFirebaseDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` |  |
| `StiFirebaseDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](../../StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AuthSecret** | string |  |
| **BasePath** | string |  |
