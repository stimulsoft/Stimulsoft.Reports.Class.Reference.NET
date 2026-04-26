---
title: "StiJsonToDataSetConverterV2 Class"
---

## StiJsonToDataSetConverterV2 Class

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
| **Object** | [JToken](../Json/Linq/JToken.md) |  |
| **ParentTableName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSet** `static` *(+7 overloads)* | DataSet |  |
| **GetDataSetFromFile** `static` *(+1 overloads)* | DataSet |  |
| **GetDataSetFromXml** `static` *(+1 overloads)* | DataSet |  |

---

### Method Details

#### GetDataSet `static`

**GetDataSet**(**json**: [JToken](../Json/Linq/JToken.md), **maxDataRows**: int?): DataSet

**Parameters**

- **json** ([JToken](../Json/Linq/JToken.md))  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSet**(**json**: [JToken](../Json/Linq/JToken.md), **relationDirection**: [StiRelationDirection](StiRelationDirection.md), **maxDataRows**: int?): DataSet

**Parameters**

- **json** ([JToken](../Json/Linq/JToken.md))  
- **relationDirection** ([StiRelationDirection](StiRelationDirection.md))  
- **maxDataRows** (int?)  

**Returns** DataSet

---

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

**GetDataSet**(**element**: XElement, **maxDataRows**: int?): DataSet

**Parameters**

- **element** (XElement)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSet**(**element**: XElement, **relationDirection**: [StiRelationDirection](StiRelationDirection.md), **maxDataRows**: int?): DataSet

**Parameters**

- **element** (XElement)  
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


---

#### GetDataSetFromXml `static`

**GetDataSetFromXml**(****: bytearray, **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytearray)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSetFromXml**(****: bytearray, **relationDirection**: [StiRelationDirection](StiRelationDirection.md), **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytearray)  
- **relationDirection** ([StiRelationDirection](StiRelationDirection.md))  
- **maxDataRows** (int?)  

**Returns** DataSet

