---
title: "StiCosmosDbConnector Class"
---

## StiCosmosDbConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Azure`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiCosmosDbConnector
```

### Inheritance

Inherits from: StiDbNoSqlDataConnector  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCosmosDbConnector**(string connectionString, [StiCosmosDbApi](../../../StiCosmosDbApi.md) api) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Api** | [StiCosmosDbApi](../../../StiCosmosDbApi.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertDateTimeToJsonStr** | string |  |
| **Get** `static` | [StiCosmosDbConnector](StiCosmosDbConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **GetSampleConnectionString** | string |  |
| **RetrieveSchema** | [StiDataSchema](../../../StiDataSchema.md) |  |
| **TestConnection** | [StiTestConnectionResult](../../../StiTestConnectionResult.md) |  |
