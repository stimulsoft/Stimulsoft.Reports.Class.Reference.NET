---
title: "StiExcelHelper Class"
---

## StiExcelHelper Class

**Namespace:** `Stimulsoft.Base.Excel`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCache** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CleanCache** `static` | void |  |
| **GetDataSetFromExcelDocument** `static` | DataSet |  |
| **GetDataSetFromXlsWithoutTypes** `static` | DataSet | Convert a stream with an XLS file to a DataSet without taking into account the types (converted to String). |
| **GetDataSetFromXlsxWithoutTypes** `static` | DataSet | Convert a stream with an XLSX file to a DataSet without taking into account types (cast to String). |

---

### Method Details

#### CleanCache `static`

**CleanCache**(): void


---

#### GetDataSetFromExcelDocument `static`

**GetDataSetFromExcelDocument**(****: bytecontent, **firstRowIsHeader**: bool, **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytecontent)  
- **firstRowIsHeader** (bool)  
- **maxDataRows** (int?)  

**Returns** DataSet


---

#### GetDataSetFromXlsWithoutTypes `static`

**GetDataSetFromXlsWithoutTypes**(**stream**: Stream, **firstRowIsHeader**: bool): DataSet

Convert a stream with an XLS file to a DataSet without taking into account the types (converted to String).

**Parameters**

- **stream** (Stream) — Input stream with XLS document.  
- **firstRowIsHeader** (bool)  

**Returns** DataSet — DataSet with data.


---

#### GetDataSetFromXlsxWithoutTypes `static`

**GetDataSetFromXlsxWithoutTypes**(**stream**: Stream, **firstRowIsHeader**: bool, **maxDataRows**: int): DataSet

Convert a stream with an XLSX file to a DataSet without taking into account types (cast to String).

**Parameters**

- **stream** (Stream) — Input stream with XLSX document.  
- **firstRowIsHeader** (bool)  
- **maxDataRows** (int)  

**Returns** DataSet — DataSet with data.

