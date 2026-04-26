---
title: "StiDBaseHelper Class"
---

## StiDBaseHelper Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSet** `static` | DataSet | Convert dataset from bytes stored in DBase format. |
| **GetTable** `static` *(+3 overloads)* | DataTable | Convert table from the DBase file. |

---

### Method Details

#### GetDataSet `static`

**GetDataSet**(****: bytedata, **tableName**: string, **forceCodePage**: bool, **forcedCodePage**: int, **maxDataRows**: int?): DataSet

Convert dataset from bytes stored in DBase format.

**Parameters**

- **** (bytedata)  
- **tableName** (string)  
- **forceCodePage** (bool)  
- **forcedCodePage** (int)  
- **maxDataRows** (int?)  

**Returns** DataSet


---

#### GetTable `static`

**GetTable**(**path**: string, **maxDataRows**: int?): DataTable

Convert table from the DBase file.

**Parameters**

- **path** (string)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(**path**: string, **codePage**: int, **maxDataRows**: int?): DataTable

Convert table from the DBase file.

**Parameters**

- **path** (string)  
- **codePage** (int)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(****: bytedata, **codePage**: int, **maxDataRows**: int?): DataTable

Convert table from the bytes in which stored DBase.

**Parameters**

- **** (bytedata)  
- **codePage** (int)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(**memoryStream**: Stream, **memo**: Stream, **forceCodePage**: bool, **forcedCodePage**: int, **maxDataRows**: int?): DataTable

Convert table from the bytes in which stored DBase file.

**Parameters**

- **memoryStream** (Stream)  
- **memo** (Stream)  
- **forceCodePage** (bool)  
- **forcedCodePage** (int)  
- **maxDataRows** (int?)  

**Returns** DataTable


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CodePage** | byte |  |
| **Day** | int |  |
| **Flags** | DBaseFieldFlags |  |
| **FractionSize** | int |  |
| **HeaderSize** | uint |  |
| **Month** | int |  |
| **Name** | string |  |
| **Offset** | int |  |
| **RecordSize** | uint |  |
| **RecordsCount** | uint |  |
| **Size** | int |  |
| **TableType** | byte |  |
| **Type** | DBaseFieldType |  |
| **Year** | int |  |
