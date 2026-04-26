---
title: "StiQuickBooksDatabase Class"
---

## StiQuickBooksDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiQuickBooksDatabase**() |  |
| **StiQuickBooksDatabase**(string name, string connectionString) |  |
| **StiQuickBooksDatabase**(string name, string alias, string connectionString) |  |
| **StiQuickBooksDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) |  |
| **StiQuickBooksDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) |  |

**StiQuickBooksDatabase**()

---

**StiQuickBooksDatabase**(**name**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiQuickBooksDatabase**(**name**: string, **alias**: string, **connectionString**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiQuickBooksDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiQuickBooksDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

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
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) |  |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetDataAdapterType** | Type |  |
| **RegData** | void |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiSqlSource](StiSqlSource.md)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiSqlSource](StiSqlSource.md)


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


---

#### RegData

**RegData**(**dictionary**: StiDictionary, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **loadData** (bool)  

