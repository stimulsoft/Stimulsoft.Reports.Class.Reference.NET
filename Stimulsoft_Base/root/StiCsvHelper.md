---
title: "StiCsvHelper Class"
---

## StiCsvHelper Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSet** `static` | DataSet | Convert dataset from bytes stored in CSV format. |
| **GetTable** `static` *(+4 overloads)* | DataTable | Convert table from CSV file. |

---

### Method Details

#### GetDataSet `static`

**GetDataSet**(****: bytedata, **tableName**: string, **codePage**: int, **separator**: string, **maxDataRows**: int?): DataSet

Convert dataset from bytes stored in CSV format.

**Parameters**

- **** (bytedata)  
- **tableName** (string)  
- **codePage** (int)  
- **separator** (string)  
- **maxDataRows** (int?)  

**Returns** DataSet


---

#### GetTable `static`

**GetTable**(**path**: string, **maxDataRows**: int?): DataTable

Convert table from CSV file.

**Parameters**

- **path** (string)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(**path**: string, **codePage**: int, **separator**: string, **maxDataRows**: int?): DataTable

Convert table from CSV file.

**Parameters**

- **path** (string)  
- **codePage** (int)  
- **separator** (string)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(****: bytedata, **maxDataRows**: int?): DataTable

Convert table from CSV file.

**Parameters**

- **** (bytedata)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(****: bytedata, **codePage**: int, **separator**: string, **maxDataRows**: int?): DataTable

Convert table from bytes stored in CSV format.

**Parameters**

- **** (bytedata)  
- **codePage** (int)  
- **separator** (string)  
- **maxDataRows** (int?)  

**Returns** DataTable

---

**GetTable**(****: bytedata, **codePage**: int, **separator**: string, **loadData**: bool, **maxDataRows**: int?): DataTable

Convert table from bytes stored in CSV format.

**Parameters**

- **** (bytedata)  
- **codePage** (int)  
- **separator** (string)  
- **loadData** (bool)  
- **maxDataRows** (int?)  

**Returns** DataTable

