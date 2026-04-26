---
title: "StiOdbcConnector Class"
---

## StiOdbcConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOdbcConnector**(string connectionString) |  |

**StiOdbcConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateAdapter** | DbDataAdapter | Returns new data adapter to this type of the database. |
| **CreateCommand** | DbCommand | Returns new data command for this type of the database. |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **Get** `static` | [StiOdbcConnector](StiOdbcConnector.md) |  |
| **GetDatabaseSpecificName** | string | Bracketing string with specials characters |
| **GetDbType** | Type | Returns the type of the DBType. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

---

### Method Details

#### CreateAdapter

**CreateAdapter**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbDataAdapter

Returns new data adapter to this type of the database.

**Parameters**

- **query** (string) — A SQL query.  
- **connection** (DbConnection) — A connection to database.  
- **commandType** (CommandType)  

**Returns** DbDataAdapter — Created adapter.


---

#### CreateCommand

**CreateCommand**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbCommand

Returns new data command for this type of the database.

**Parameters**

- **query** (string) — A SQL query.  
- **connection** (DbConnection) — A connection to database.  
- **commandType** (CommandType)  

**Returns** DbCommand — Created command.


---

#### CreateConnection

**CreateConnection**(): DbConnection

Returns new connection to this type of the database.

**Returns** DbConnection — Created connection.


---

#### CreateParameter

**CreateParameter**(**parameterName**: string, **value**: object, **size**: int): DbParameter

Returns new SQL parameter with specified parameter.

**Parameters**

- **parameterName** (string)  
- **value** (object)  
- **size** (int)  

**Returns** DbParameter

---

**CreateParameter**(**parameterName**: string, **type**: int, **size**: int): DbParameter

Returns new SQL parameter with specified parameter.

**Parameters**

- **parameterName** (string)  
- **type** (int)  
- **size** (int)  

**Returns** DbParameter


---

#### DeriveParameters

**DeriveParameters**(**command**: DbCommand): void

Retrieves SQL parameters for the specified command.

**Parameters**

- **command** (DbCommand)  


---

#### Get `static`

**Get**(**connectionString**: string): [StiOdbcConnector](StiOdbcConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiOdbcConnector](StiOdbcConnector.md)


---

#### GetDatabaseSpecificName

**GetDatabaseSpecificName**(**name**: string): string

Bracketing string with specials characters

**Parameters**

- **name** (string) — A input string  

**Returns** string — Bracketed string


---

#### GetDbType

**GetDbType**(): Type

Returns the type of the DBType.

**Returns** Type


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


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)

