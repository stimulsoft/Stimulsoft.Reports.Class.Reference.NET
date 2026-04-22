---
title: "StiAzureBlobStorageDatabase Class"
---

## StiAzureBlobStorageDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAzureBlobStorageDatabase
```

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAzureBlobStorageDatabase**() |  |
| **StiAzureBlobStorageDatabase**(string name, string connectionString) |  |
| **StiAzureBlobStorageDatabase**(string name, string alias, string connectionString) |  |
| **StiAzureBlobStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiAzureBlobStorageDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformationSource** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AccountKey** | string |  |
| **AccountName** | string |  |
| **BlobContentType** | string |  |
| **BlobName** | string |  |
| **CodePage** | int |  |
| **ContainerName** | string |  |
| **Delimiter** | string |  |
| **FirstRowIsHeader** | bool |  |
