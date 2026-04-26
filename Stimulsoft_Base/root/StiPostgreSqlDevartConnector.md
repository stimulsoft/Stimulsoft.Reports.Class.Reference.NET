---
title: "StiPostgreSqlDevartConnector Class"
---

## StiPostgreSqlDevartConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiPostgreSqlConnector](StiPostgreSqlConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPostgreSqlDevartConnector**(string connectionString) |  |

**StiPostgreSqlDevartConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetNetType** | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |

---

### Method Details

#### GetNetType

**GetNetType**(**dbType**: int): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (int)  

**Returns** Type


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

Returns sample of the connection string to this connector.

**Returns** string


---

#### GetSqlType

**GetSqlType**(**type**: Type): int

Returns a SQL based type from the .NET type.

**Parameters**

- **type** (Type)  

**Returns** int

