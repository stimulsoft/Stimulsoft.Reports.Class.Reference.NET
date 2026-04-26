---
title: "StiOracleConnector Class"
---

## StiOracleConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOracleConnector**(string connectionString) |  |

**StiOracleConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowDevart** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **Get** `static` | [StiOracleConnector](StiOracleConnector.md) |  |
| **GetDatabaseSpecificName** | string | Bracketing string with specials characters |
| **GetFamilyConnectors** | [StiDataConnector](StiDataConnector.md)[] | Return an array of the data connectors which can be used also to access data for this type of the connector. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **LoadClientConnector** `static` | [StiOracleClientConnector](StiOracleClientConnector.md) |  |
| **LoadDevartConnector** `static` | [StiOracleDevartConnector](StiOracleDevartConnector.md) |  |
| **LoadGenericConnector** `static` | [StiOracleConnector](StiOracleConnector.md) |  |
| **LoadManagedConnector** `static` | [StiOracleManagedConnector](StiOracleManagedConnector.md) |  |
| **ResetSettings** | void |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

---

### Method Details

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

#### Get `static`

**Get**(**connectionString**: string): [StiOracleConnector](StiOracleConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiOracleConnector](StiOracleConnector.md)


---

#### GetDatabaseSpecificName

**GetDatabaseSpecificName**(**name**: string): string

Bracketing string with specials characters

**Parameters**

- **name** (string) — unput string  

**Returns** string — Bracketed string


---

#### GetFamilyConnectors

**GetFamilyConnectors**(): [StiDataConnector](StiDataConnector.md)[]

Return an array of the data connectors which can be used also to access data for this type of the connector.

**Returns** [StiDataConnector](StiDataConnector.md)[]


---

#### GetNetType

**GetNetType**(**dbType**: int): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (int)  

**Returns** Type

---

**GetNetType**(**dbType**: string): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (string)  

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

#### LoadClientConnector `static`

**LoadClientConnector**(**connectionString**: string): [StiOracleClientConnector](StiOracleClientConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiOracleClientConnector](StiOracleClientConnector.md)


---

#### LoadDevartConnector `static`

**LoadDevartConnector**(**connectionString**: string): [StiOracleDevartConnector](StiOracleDevartConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiOracleDevartConnector](StiOracleDevartConnector.md)


---

#### LoadGenericConnector `static`

**LoadGenericConnector**(**connectionString**: string): [StiOracleConnector](StiOracleConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiOracleConnector](StiOracleConnector.md)


---

#### LoadManagedConnector `static`

**LoadManagedConnector**(**connectionString**: string): [StiOracleManagedConnector](StiOracleManagedConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiOracleManagedConnector](StiOracleManagedConnector.md)


---

#### ResetSettings

**ResetSettings**(): void


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)

