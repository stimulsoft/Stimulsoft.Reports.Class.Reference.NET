---
title: "StiAppsDbDatabase Class"
---

## StiAppsDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAppsDbDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAppsDbDatabase**() |  |
| **StiAppsDbDatabase**(string name, string connectionString) |  |
| **StiAppsDbDatabase**(string name, string alias, string connectionString) |  |
| **StiAppsDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiAppsDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CloudDatabaseKey** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
