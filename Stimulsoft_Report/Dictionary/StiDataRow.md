---
title: "StiDataRow Class"
---

## StiDataRow Class

**Namespace:** `Stimulsoft.Report.Dictionary`

The class wrapper for DataRow.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataRow**([StiDataRow](StiDataRow.md) dataRow) | Creates a new object of the type StiDataRow. |
| **StiDataRow**(StiDataSource dataSource, DataRow dataRow) | Creates a new object of the type StiDataRow. |

**StiDataRow**(**dataRow**: [StiDataRow](StiDataRow.md))

Creates a new object of the type StiDataRow.

**Parameters**

- **dataRow** ([StiDataRow](StiDataRow.md)) — DataRow that is used for data extraction.  

---

**StiDataRow**(**dataSource**: StiDataSource, **dataRow**: DataRow)

Creates a new object of the type StiDataRow.

**Parameters**

- **dataSource** (StiDataSource) — Data Source in which DataRow is located.  
- **dataRow** (DataRow) — DataRow that is used for data extraction.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Row** | DataRow | DataRow that is used for data extraction. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetParentData** | [StiDataRow](StiDataRow.md) | Returns StiDataRow by name of the parent relation. |

---

### Method Details

#### GetParentData

**GetParentData**(**relation**: string): [StiDataRow](StiDataRow.md)

Returns StiDataRow by name of the parent relation.

**Parameters**

- **relation** (string) — Parent relation name.  

**Returns** [StiDataRow](StiDataRow.md) — Parent StiDataRow.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Dictionary** | StiDictionary |  |
