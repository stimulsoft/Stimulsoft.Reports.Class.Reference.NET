---
title: "StiFileAdapterService Class"
---

## StiFileAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to Csv files.

### Inheritance

Inherits from: [StiDataStoreAdapterService](StiDataStoreAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md) | Returns new data connector for this type of the database. |
| **GetDataCategoryName** | string | Returns name of category for data. |

---

### Method Details

#### CreateConnector

**CreateConnector**(): [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md)

Returns new data connector for this type of the database.

**Returns** [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md) — Created connector.


---

#### GetDataCategoryName

**GetDataCategoryName**(**data**: [StiData](StiData.md)): string

Returns name of category for data.

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** string

