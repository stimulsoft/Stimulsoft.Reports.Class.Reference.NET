---
title: "StiDataSchema Class"
---

## StiDataSchema Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

This class describes a data schema in data source.

```csharp
public class StiDataSchema
```

### Inheritance

Inherits from: [StiObjectSchema](StiObjectSchema.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataSchema**() |  |
| **StiDataSchema**([StiConnectionIdent](StiConnectionIdent.md) ident) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionIdent** | [StiConnectionIdent](StiConnectionIdent.md) | A type of the connection from which this schema is created. |
| **Queries** | List<[StiDataTableSchema](StiDataTableSchema.md)> | A list of sql queries in the schema. |
| **Relations** | List<[StiDataRelationSchema](StiDataRelationSchema.md)> | A list of relations for this schema. |
| **StoredProcedures** | List<[StiDataTableSchema](StiDataTableSchema.md)> | A list of stored procedures in the schema. |
| **Tables** | List<[StiDataTableSchema](StiDataTableSchema.md)> | A list of tables in the schema. |
| **Views** | List<[StiDataTableSchema](StiDataTableSchema.md)> | A list of views in the schema. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSet** | DataSet |  |
| **IsEmpty** | bool |  |
| **Sort** | [StiDataSchema](StiDataSchema.md) |  |
