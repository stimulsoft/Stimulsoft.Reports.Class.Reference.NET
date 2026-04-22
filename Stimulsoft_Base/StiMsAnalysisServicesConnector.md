---
title: "StiMsAnalysisServicesConnector Class"
---

## StiMsAnalysisServicesConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiMsAnalysisServicesConnector
```

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMsAnalysisServicesConnector(string connectionString)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NuGetPackages** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> | Analysis services data structures may not be tables. Cannot get columns by table name, so query is used instead. |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) |  |
