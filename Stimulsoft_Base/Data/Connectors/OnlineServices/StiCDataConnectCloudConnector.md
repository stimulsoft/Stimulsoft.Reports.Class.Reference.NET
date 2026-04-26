---
title: "StiCDataConnectCloudConnector Class"
---

## StiCDataConnectCloudConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.OnlineServices`

### Inheritance

Inherits from: [StiMsSqlConnector](../../../root/StiMsSqlConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCDataConnectCloudConnector**(string connectionString) |  |

**StiCDataConnectCloudConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnection** | DbConnection |  |
| **GetNetType** *(+1 overloads)* | Type |  |
| **GetSampleConnectionString** | string |  |
| **GetSqlType** | int |  |
| **RetrieveSchema** | [StiDataSchema](../../../root/StiDataSchema.md) |  |

---

### Method Details

#### CreateConnection

**CreateConnection**(): DbConnection

**Returns** DbConnection


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

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](../../../root/StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](../../../root/StiDataSchema.md)

