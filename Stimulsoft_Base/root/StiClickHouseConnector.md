---
title: "StiClickHouseConnector Class"
---

## StiClickHouseConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiClickHouseConnector**(string connectionString) |  |

**StiClickHouseConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NuGetPackages** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateAdapter** | DbDataAdapter |  |
| **CreateCommand** | DbCommand |  |
| **CreateParameter** *(+1 overloads)* | DbParameter |  |
| **GetDatabaseSpecificName** | string |  |
| **GetNetType** *(+1 overloads)* | Type |  |
| **GetSampleConnectionString** | string |  |
| **GetSqlType** | int |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |

---

### Method Details

#### CreateAdapter

**CreateAdapter**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbDataAdapter

**Parameters**

- **query** (string)  
- **connection** (DbConnection)  
- **commandType** (CommandType)  

**Returns** DbDataAdapter


---

#### CreateCommand

**CreateCommand**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbCommand

**Parameters**

- **query** (string)  
- **connection** (DbConnection)  
- **commandType** (CommandType)  

**Returns** DbCommand


---

#### CreateParameter

**CreateParameter**(**parameterName**: string, **type**: int, **size**: int): DbParameter

**Parameters**

- **parameterName** (string)  
- **type** (int)  
- **size** (int)  

**Returns** DbParameter

---

**CreateParameter**(**parameterName**: string, **value**: object, **size**: int): DbParameter

**Parameters**

- **parameterName** (string)  
- **value** (object)  
- **size** (int)  

**Returns** DbParameter


---

#### GetDatabaseSpecificName

**GetDatabaseSpecificName**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### GetNetType

**GetNetType**(**dbType**: string): Type

**Parameters**

- **dbType** (string)  

**Returns** Type

---

**GetNetType**(**dbType**: int): Type

**Parameters**

- **dbType** (int)  

**Returns** Type


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

**Returns** string


---

#### GetSqlType

**GetSqlType**(**type**: Type): int

**Parameters**

- **type** (Type)  

**Returns** int


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)

