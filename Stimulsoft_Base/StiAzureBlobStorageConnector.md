---
title: "StiAzureBlobStorageConnector Class"
---

## StiAzureBlobStorageConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiAzureBlobStorageConnector
```

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiAzureBlobStorageConnector](StiAzureBlobStorageConnector.md) |  |
| **GetBlobContentTypeOrDefault** | string | Try to connect to Azure Blob Storage using current connection string, download blob contents and infer type of data stored. |
| **GetBlobNamesList** | List<string> | Retrieve all blob names starting with specified , or all names if no specified. |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetContainerNamesList** | List<string> | Retrieve all container names starting with specified , or all names if no specified. |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) |  |
