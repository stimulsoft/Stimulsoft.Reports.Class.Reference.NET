---
title: "StiDataTableSchema Class"
---

## StiDataTableSchema Class

**Namespace:** `Stimulsoft.Base`

This class describes a table in data schema.

### Inheritance

Inherits from: [StiObjectSchema](StiObjectSchema.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataTableSchema**() |  |
| **StiDataTableSchema**(DataTable table) |  |
| **StiDataTableSchema**(string name, string query) |  |

**StiDataTableSchema**()

---

**StiDataTableSchema**(**table**: DataTable)

**Parameters**

- **table** (DataTable)  

---

**StiDataTableSchema**(**name**: string, **query**: string)

**Parameters**

- **name** (string)  
- **query** (string)  


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

---

### Method Details

#### NewProcedure `static`

**NewProcedure**(**name**: string, **connector**: [StiSqlDataConnector](StiSqlDataConnector.md), **query**: string): [StiDataTableSchema](StiDataTableSchema.md)

**Parameters**

- **name** (string)  
- **connector** ([StiSqlDataConnector](StiSqlDataConnector.md))  
- **query** (string)  

**Returns** [StiDataTableSchema](StiDataTableSchema.md)


---

#### NewTable `static`

**NewTable**(**name**: string, **connector**: [StiSqlDataConnector](StiSqlDataConnector.md), **query**: string): [StiDataTableSchema](StiDataTableSchema.md)

**Parameters**

- **name** (string)  
- **connector** ([StiSqlDataConnector](StiSqlDataConnector.md))  
- **query** (string)  

**Returns** [StiDataTableSchema](StiDataTableSchema.md)


---

#### NewTableOrView `static`

**NewTableOrView**(**name**: string, **connector**: [StiSqlDataConnector](StiSqlDataConnector.md), **query**: string): [StiDataTableSchema](StiDataTableSchema.md)

**Parameters**

- **name** (string)  
- **connector** ([StiSqlDataConnector](StiSqlDataConnector.md))  
- **query** (string)  

**Returns** [StiDataTableSchema](StiDataTableSchema.md)


---

#### NewView `static`

**NewView**(**name**: string, **connector**: [StiSqlDataConnector](StiSqlDataConnector.md), **query**: string): [StiDataTableSchema](StiDataTableSchema.md)

**Parameters**

- **name** (string)  
- **connector** ([StiSqlDataConnector](StiSqlDataConnector.md))  
- **query** (string)  

**Returns** [StiDataTableSchema](StiDataTableSchema.md)

