---
title: "StiBusinessObjectAdapterService Class"
---

## StiBusinessObjectAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes the adapter for access to Business Objects.

### Inheritance

Inherits from: [StiDataTableAdapterService](StiDataTableAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |

---

### Method Details

#### GetDataCategoryName

**GetDataCategoryName**(**data**: [StiData](StiData.md)): string

Returns name of category for data.

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** string


---

#### GetDataSourceType

**GetDataSourceType**(): Type

Returns the type of the Data Source.

**Returns** Type — The type of Data Source.


---

#### GetDataTypes

**GetDataTypes**(): Type[]

Returns the array of data types to which the Data Source may refer.

**Returns** Type[] — Array of data types.

