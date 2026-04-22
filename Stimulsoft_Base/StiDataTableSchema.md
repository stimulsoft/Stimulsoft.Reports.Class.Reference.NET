---
title: "StiDataTableSchema Class"
---

## StiDataTableSchema Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

This class describes a table in data schema.

```csharp
public class StiDataTableSchema
```

### Inheritance

Inherits from: [StiObjectSchema](StiObjectSchema.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiDataTableSchema()` |  |
| `StiDataTableSchema(DataTable table)` |  |
| `StiDataTableSchema(string name, string query)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Columns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> | A list of the columns. |
| **Description** | string | A description of the schema object. |
| **Parameters** | List<[StiDataParameterSchema](StiDataParameterSchema.md)> | A list of the parameters. |
| **Query** | string | A query string. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **NewProcedure** `static` | [StiDataTableSchema](StiDataTableSchema.md) |  |
| **NewTable** `static` | [StiDataTableSchema](StiDataTableSchema.md) |  |
| **NewTableOrView** `static` | [StiDataTableSchema](StiDataTableSchema.md) |  |
| **NewView** `static` | [StiDataTableSchema](StiDataTableSchema.md) |  |
