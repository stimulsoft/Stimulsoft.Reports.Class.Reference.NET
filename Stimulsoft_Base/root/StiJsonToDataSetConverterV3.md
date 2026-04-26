---
title: "StiJsonToDataSetConverterV3 Class"
---

## StiJsonToDataSetConverterV3 Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Address** | string |  |
| **Cast** | string |  |
| **ChildColumn** | DataColumn |  |
| **ChildTable** | DataTable |  |
| **CollectionName** | string |  |
| **IsEmpty** | bool |  |
| **ParentTableName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSet** `static` *(+3 overloads)* | DataSet |  |
| **GetDataSetFromFile** `static` *(+1 overloads)* | DataSet |  |

---

### Method Details

#### GetDataSet `static`

**GetDataSet**(****: bytecontent, **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytecontent)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSet**(****: bytecontent, **relationDirection**: [StiRelationDirection](StiRelationDirection.md), **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytecontent)  
- **relationDirection** ([StiRelationDirection](StiRelationDirection.md))  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSet**(**text**: string, **maxDataRows**: int?): DataSet

**Parameters**

- **text** (string)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSet**(**text**: string, **relationDirection**: [StiRelationDirection](StiRelationDirection.md), **maxDataRows**: int?): DataSet

**Parameters**

- **text** (string)  
- **relationDirection** ([StiRelationDirection](StiRelationDirection.md))  
- **maxDataRows** (int?)  

**Returns** DataSet


---

#### GetDataSetFromFile `static`

**GetDataSetFromFile**(**path**: string, **maxDataRows**: int?): DataSet

**Parameters**

- **path** (string)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSetFromFile**(**path**: string, **relationDirection**: [StiRelationDirection](StiRelationDirection.md), **maxDataRows**: int?): DataSet

**Parameters**

- **path** (string)  
- **relationDirection** ([StiRelationDirection](StiRelationDirection.md))  
- **maxDataRows** (int?)  

**Returns** DataSet

