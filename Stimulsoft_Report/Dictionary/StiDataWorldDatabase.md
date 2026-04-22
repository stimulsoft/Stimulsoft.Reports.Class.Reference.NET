---
title: "StiDataWorldDatabase Class"
---

## StiDataWorldDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDataWorldDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataWorldDatabase**() |  |
| **StiDataWorldDatabase**(string name, string connectionString) |  |
| **StiDataWorldDatabase**(string name, string alias, string connectionString) |  |
| **StiDataWorldDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiDataWorldDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

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
| **Database** | string |  |
| **Owner** | string |  |
| **Token** | string |  |
