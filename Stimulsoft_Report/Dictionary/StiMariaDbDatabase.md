---
title: "StiMariaDbDatabase Class"
---

## StiMariaDbDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiMySqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMariaDbDatabase**() | Creates a new object of the type StiMariaDbDatabase. |
| **StiMariaDbDatabase**(string name, string connectionString) | Creates a new object of the type StiMariaDbDatabase. |
| **StiMariaDbDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiMariaDbDatabase. |
| **StiMariaDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiMariaDbDatabase. |
| **StiMariaDbDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiMariaDbDatabase. |

**StiMariaDbDatabase**()

Creates a new object of the type StiMariaDbDatabase.

---

**StiMariaDbDatabase**(**name**: string, **connectionString**: string)

Creates a new object of the type StiMariaDbDatabase.

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiMariaDbDatabase**(**name**: string, **alias**: string, **connectionString**: string)

Creates a new object of the type StiMariaDbDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiMariaDbDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

Creates a new object of the type StiMariaDbDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiMariaDbDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

Creates a new object of the type StiMariaDbDatabase.

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
| **GetDataAdapterType** | Type |  |

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

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

