---
title: "StiOleDbSource Class"
---

## StiOleDbSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOleDbSource**() | Creates a new object of the type StiDataViewSource. |
| **StiOleDbSource**(string nameInSource, string name) | Creates a new object of the type StiOleDbSource. |
| **StiOleDbSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiOleDbSource. |
| **StiOleDbSource**(string nameInSource, string name, string alias, string sqlCommand) | Creates a new object of the type StiOleDbSource. |
| **StiOleDbSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

**StiOleDbSource**()

Creates a new object of the type StiDataViewSource.

---

**StiOleDbSource**(**nameInSource**: string, **name**: string)

Creates a new object of the type StiOleDbSource.

**Parameters**

- **nameInSource** (string) — Name of OleDbConnection in the DataStore.  
- **name** (string) — Data Source name.  

---

**StiOleDbSource**(**nameInSource**: string, **name**: string, **alias**: string)

Creates a new object of the type StiOleDbSource.

**Parameters**

- **nameInSource** (string) — Name of OleDbConnection in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiOleDbSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string)

Creates a new object of the type StiOleDbSource.

**Parameters**

- **nameInSource** (string) — Name of OleDbConnection in the DataStore.  
- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **sqlCommand** (string) — Transact-SQL statement to execute at the Data Source.  

---

**StiOleDbSource**(**nameInSource**: string, **name**: string, **alias**: string, **sqlCommand**: string, **connectOnStart**: bool, **reconnectOnEachRow**: bool, **commandTimeout**: int, **key**: string)

**Parameters**

- **nameInSource** (string)  
- **name** (string)  
- **alias** (string)  
- **sqlCommand** (string)  
- **connectOnStart** (bool)  
- **reconnectOnEachRow** (bool)  
- **commandTimeout** (int)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this datasource.

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type

