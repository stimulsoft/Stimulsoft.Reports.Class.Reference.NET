---
title: "StiSybaseAdsConnector Class"
---

## StiSybaseAdsConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSybaseAdsConnector**(string connectionString) |  |

**StiSybaseAdsConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **Get** `static` | [StiSybaseAdsConnector](StiSybaseAdsConnector.md) |  |
| **GetDatabaseSpecificName** | string | Bracketing string with specials characters |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
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

**Get**(**connectionString**: string): [StiSybaseAdsConnector](StiSybaseAdsConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiSybaseAdsConnector](StiSybaseAdsConnector.md)


---

#### GetDatabaseSpecificName

**GetDatabaseSpecificName**(**name**: string): string

Bracketing string with specials characters

**Parameters**

- **name** (string) — A input string  

**Returns** string — Bracketed string


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

