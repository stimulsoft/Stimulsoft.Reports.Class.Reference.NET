---
title: "StiSnowflakeConnector Class"
---

## StiSnowflakeConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSnowflakeConnector**(string connectionString) |  |

**StiSnowflakeConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NuGetPackages** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateCommand** | DbCommand |  |
| **GetDatabaseSpecificName** | string |  |
| **GetNetType** *(+1 overloads)* | Type |  |
| **GetSampleConnectionString** | string |  |
| **GetSqlType** | int |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |

---

### Method Details

#### CreateCommand

**CreateCommand**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbCommand

**Parameters**

- **query** (string)  
- **connection** (DbConnection)  
- **commandType** (CommandType)  

**Returns** DbCommand


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

