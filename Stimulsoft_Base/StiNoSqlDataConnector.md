---
title: "StiNoSqlDataConnector Class"
---

## StiNoSqlDataConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public abstract class StiNoSqlDataConnector
```

### Inheritance

Inherits from: [StiDataConnector](StiDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiNoSqlDataConnector**(string connectionString) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionString** | string | Gets connection string to the database. |
| **FolderAssembly** | string |  |
| **NameAssembly** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiNoSqlDataConnector](StiNoSqlDataConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |
