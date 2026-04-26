---
title: "StiData Class"
---

## StiData Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiData**(string name, object data) | Creates a new object of the type StiData. |
| **StiData**(string name, string alias, object data) | Creates a new object of the type StiData. |
| **StiData**(string name, object data, object viewData) | Creates a new object of the type StiData. |

**StiData**(**name**: string, **data**: object)

Creates a new object of the type StiData.

**Parameters**

- **name** (string) — Name of Data.  
- **data** (object) — Data.  

---

**StiData**(**name**: string, **alias**: string, **data**: object)

Creates a new object of the type StiData.

**Parameters**

- **name** (string) — Name of Data.  
- **alias** (string) — Alias of Data.  
- **data** (object) — Data.  

---

**StiData**(**name**: string, **data**: object, **viewData**: object)

Creates a new object of the type StiData.

**Parameters**

- **name** (string) — Name of Data.  
- **data** (object) — Data.  
- **viewData** (object) — Data for view.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Alias** | string | Gets or sets alias of Data. |
| **Data** | object | Gets or sets Data. |
| **IsBusinessObjectData** | bool | Gets or sets value, which indicates that data is business object. |
| **IsReportData** | bool | Gets or sets value, which indicates that data registered of report engine. |
| **ViewData** | object | Gets or sets ViewData. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string |  |

---

### Method Details

#### ToString

**ToString**(): string

**Returns** string

