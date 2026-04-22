---
title: "StiGraphQLConnector Class"
---

## StiGraphQLConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiGraphQLConnector
```

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGraphQLConnector**(string connectionString) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiGraphQLConnector](StiGraphQLConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetDataSet** | DataSet |  |
| **GetDataTable** *(+1 overloads)* | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **LoadColumnsAndStringRowsFromPackedString** `static` | List<string[]> |  |
| **LoadColumnsAndStringRowsFromString** `static` | List<string[]> |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) |  |
