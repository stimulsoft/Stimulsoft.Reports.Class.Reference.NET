---
title: "StiAzureTableStorageDatabase Class"
---

## StiAzureTableStorageDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAzureTableStorageDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAzureTableStorageDatabase**() |  |
| **StiAzureTableStorageDatabase**(string name, string connectionString) |  |
| **StiAzureTableStorageDatabase**(string name, string alias, string connectionString) |  |
| **StiAzureTableStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiAzureTableStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **GetDataAdapterType** | Type |  |
