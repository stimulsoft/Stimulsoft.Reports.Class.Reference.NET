---
title: "StiNoSqlAdapterService Class"
---

## StiNoSqlAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to SqlConnection.

### Inheritance

Inherits from: [StiDataStoreAdapterService](StiDataStoreAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnectionInDataStore** | void |  |
| **CreateConnector** | [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) | Returns new data connector for this type of the database. |
| **GetDataCategoryName** | string |  |
| **GetDataTypes** | Type[] |  |
| **TestConnection** | string |  |

---

### Method Details

#### CreateConnectionInDataStore

**CreateConnectionInDataStore**(**dictionary**: StiDictionary, **database**: [StiNoSqlDatabase](StiNoSqlDatabase.md)): void

**Parameters**

- **dictionary** (StiDictionary)  
- **database** ([StiNoSqlDatabase](StiNoSqlDatabase.md))  


---

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md)

Returns new data connector for this type of the database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiNoSqlDataConnector](../../Stimulsoft_Base/root/StiNoSqlDataConnector.md) — Created connector.


---

#### GetDataCategoryName

**GetDataCategoryName**(**data**: [StiData](StiData.md)): string

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** string


---

#### GetDataTypes

**GetDataTypes**(): Type[]

**Returns** Type[]


---

#### TestConnection

**TestConnection**(**connectionString**: string): string

**Parameters**

- **connectionString** (string)  

**Returns** string

