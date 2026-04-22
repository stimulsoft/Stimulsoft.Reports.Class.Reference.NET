---
title: "StiGoogleAnalyticsDatabase Class"
---

## StiGoogleAnalyticsDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Google`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGoogleAnalyticsDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](../../StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGoogleAnalyticsDatabase**() |  |
| **StiGoogleAnalyticsDatabase**(string name, string connectionString) |  |
| **StiGoogleAnalyticsDatabase**(string name, string alias, string connectionString) |  |
| **StiGoogleAnalyticsDatabase**(string name, string alias, string connectionString, bool promptUserNameAndPassword) |  |
| **StiGoogleAnalyticsDatabase**(string name, string alias, string connectionString, bool promptUserNameAndPassword, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](../../StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AccountId** | string |  |
| **Base64EncodedAuthSecret** | string |  |
| **Dimensions** | string |  |
| **EndDate** | string |  |
| **Metrics** | string |  |
| **PropertyId** | string |  |
| **StartDate** | string |  |
| **ViewId** | string |  |
