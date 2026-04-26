---
title: "StiRestDataConnector Class"
---

## StiRestDataConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRestDataConnector**(string connectionString) |  |

**StiRestDataConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillDataTable** | void |  |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the REST service. |

---

### Method Details

#### FillDataTable

**FillDataTable**(**table**: DataTable, **query**: string): void

**Parameters**

- **table** (DataTable)  
- **query** (string)  


---

#### GetNetType

**GetNetType**(**dbType**: string): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (string)  

**Returns** Type

---

**GetNetType**(**dbType**: int): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (int)  

**Returns** Type


---

#### GetSqlType

**GetSqlType**(**type**: Type): int

Returns a SQL based type from the .NET type.

**Parameters**

- **type** (Type)  

**Returns** int


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the REST service.

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)

