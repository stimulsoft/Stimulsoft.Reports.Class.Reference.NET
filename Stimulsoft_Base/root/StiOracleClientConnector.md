---
title: "StiOracleClientConnector Class"
---

## StiOracleClientConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiOracleConnector](StiOracleConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOracleClientConnector**(string connectionString) |  |

**StiOracleClientConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetNetType** | Type | Returns a .NET type from the specified string representaion of the database type. |
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

#### GetSqlType

**GetSqlType**(**type**: Type): int

Returns a SQL based type from the .NET type.

**Parameters**

- **type** (Type)  

**Returns** int

