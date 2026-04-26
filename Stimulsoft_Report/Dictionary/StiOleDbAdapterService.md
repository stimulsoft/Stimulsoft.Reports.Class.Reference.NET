---
title: "StiOleDbAdapterService Class"
---

## StiOleDbAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to OleDbConnection.

### Inheritance

Inherits from: [StiSqlAdapterService](StiSqlAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) | Returns new data connector for this type of the database. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |

---

### Method Details

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md)

Returns new data connector for this type of the database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiSqlDataConnector](../../Stimulsoft_Base/root/StiSqlDataConnector.md) — Created connector.


---

#### GetDataSourceType

**GetDataSourceType**(): Type

Returns the type of the Data Source.

**Returns** Type — The type of Data Source.

