---
title: "StiOracleDevartConnector Class"
---

## StiOracleDevartConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiOracleConnector](StiOracleConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOracleDevartConnector**(string connectionString) |  |

**StiOracleDevartConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

---

### Method Details

#### CreateConnection

**CreateConnection**(): DbConnection

Returns new connection to this type of the database.

**Returns** DbConnection — Created connection.


---

#### DeriveParameters

**DeriveParameters**(**command**: DbCommand): void

Retrieves SQL parameters for the specified command.

**Parameters**

- **command** (DbCommand)  


---

#### GetNetType

**GetNetType**(**dbType**: int): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (int)  

**Returns** Type

---

**GetNetType**(**dbType**: string): Type

**Parameters**

- **dbType** (string)  

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

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)

