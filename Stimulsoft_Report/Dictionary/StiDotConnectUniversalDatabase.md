---
title: "StiDotConnectUniversalDatabase Class"
---

## StiDotConnectUniversalDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDotConnectUniversalDatabase**() | Creates a new object of the type StiDotConnectUniversalDatabase. |
| **StiDotConnectUniversalDatabase**(string name, string connectionString) | Creates a new object of the type StiDotConnectUniversalDatabase. |
| **StiDotConnectUniversalDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiDotConnectUniversalDatabase. |
| **StiDotConnectUniversalDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiDotConnectUniversalDatabase. |
| **StiDotConnectUniversalDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiDotConnectUniversalDatabase. |

**StiDotConnectUniversalDatabase**()

Creates a new object of the type StiDotConnectUniversalDatabase.

---

**StiDotConnectUniversalDatabase**(**name**: string, **connectionString**: string)

Creates a new object of the type StiDotConnectUniversalDatabase.

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiDotConnectUniversalDatabase**(**name**: string, **alias**: string, **connectionString**: string)

Creates a new object of the type StiDotConnectUniversalDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiDotConnectUniversalDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

Creates a new object of the type StiDotConnectUniversalDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiDotConnectUniversalDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

Creates a new object of the type StiDotConnectUniversalDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **MapUserNameAndPassword** | string |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)

Returns new data connector for this database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) — Created connector.


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiSqlSource](StiSqlSource.md)

Returns new data source for this database.

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiSqlSource](StiSqlSource.md) — Created data source.


---

#### GetConnectionStringHelper

**GetConnectionStringHelper**(): string

**Returns** string


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


---

#### MapUserNameAndPassword

**MapUserNameAndPassword**(**userName**: string, **password**: string): string

**Parameters**

- **userName** (string)  
- **password** (string)  

**Returns** string

