---
title: "StiDataWorldDatabase Class"
---

## StiDataWorldDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiNoSqlDatabase](StiNoSqlDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataWorldDatabase**() |  |
| **StiDataWorldDatabase**(string name, string connectionString) |  |
| **StiDataWorldDatabase**(string name, string alias, string connectionString) |  |
| **StiDataWorldDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiDataWorldDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiDataWorldDatabase**()

---

**StiDataWorldDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiDataWorldDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiDataWorldDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiDataWorldDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) |  |
| **CreateDataSource** | [StiNoSqlSource](StiNoSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiNoSqlSource](StiNoSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiNoSqlSource](StiNoSqlSource.md)


---

#### Edit

**Edit**(**dictionary**: StiDictionary, **newDatabase**: bool): DialogResult

**Parameters**

- **dictionary** (StiDictionary)  
- **newDatabase** (bool)  

**Returns** DialogResult


---

#### EditAsync

**EditAsync**(**dictionary**: StiDictionary, **newDatabase**: bool): Task<DialogResult>

**Parameters**

- **dictionary** (StiDictionary)  
- **newDatabase** (bool)  

**Returns** Task<DialogResult>


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Database** | string |  |
| **Owner** | string |  |
| **Token** | string |  |
