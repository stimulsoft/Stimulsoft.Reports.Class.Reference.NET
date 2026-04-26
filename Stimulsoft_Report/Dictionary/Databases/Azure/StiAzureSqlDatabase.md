---
title: "StiAzureSqlDatabase Class"
---

## StiAzureSqlDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary.Databases.Azure`

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAzureSqlDatabase**() | Creates a new object of the type StiAzureSqlDatabase. |
| **StiAzureSqlDatabase**(string name, string connectionString) | Creates a new object of the type StiAzureSqlDatabase. |
| **StiAzureSqlDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiAzureSqlDatabase. |
| **StiAzureSqlDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiAzureSqlDatabase. |
| **StiAzureSqlDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiAzureSqlDatabase. |

**StiAzureSqlDatabase**()

Creates a new object of the type StiAzureSqlDatabase.

---

**StiAzureSqlDatabase**(**name**: string, **connectionString**: string)

Creates a new object of the type StiAzureSqlDatabase.

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiAzureSqlDatabase**(**name**: string, **alias**: string, **connectionString**: string)

Creates a new object of the type StiAzureSqlDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiAzureSqlDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

Creates a new object of the type StiAzureSqlDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiAzureSqlDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

Creates a new object of the type StiAzureSqlDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **GetConnectionStringHelper** | string |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../../../Stimulsoft_Base/root/StiDataConnector.md)


---

#### GetConnectionStringHelper

**GetConnectionStringHelper**(): string

**Returns** string

