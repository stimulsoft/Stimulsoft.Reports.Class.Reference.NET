---
title: "StiTeradataDatabase Class"
---

## StiTeradataDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTeradataDatabase**() | Creates a new object of the type StiTeradataDatabase. |
| **StiTeradataDatabase**(string name, string connectionString) | Creates a new object of the type StiTeradataDatabase. |
| **StiTeradataDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiTeradataDatabase. |
| **StiTeradataDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiTeradataDatabase. |
| **StiTeradataDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiTeradataDatabase. |

**StiTeradataDatabase**()

Creates a new object of the type StiTeradataDatabase.

---

**StiTeradataDatabase**(**name**: string, **connectionString**: string)

Creates a new object of the type StiTeradataDatabase.

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiTeradataDatabase**(**name**: string, **alias**: string, **connectionString**: string)

Creates a new object of the type StiTeradataDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiTeradataDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

Creates a new object of the type StiTeradataDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiTeradataDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

Creates a new object of the type StiTeradataDatabase.

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

