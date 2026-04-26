---
title: "StiJsonToDataSetConverter Class"
---

## StiJsonToDataSetConverter Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSet** `static` *(+4 overloads)* | DataSet |  |
| **GetDataSetFromFile** `static` | DataSet |  |
| **GetDataSetFromXml** `static` | DataSet |  |
| **GetDataSetFromXmlFile** `static` | DataSet |  |

---

### Method Details

#### GetDataSet `static`

**GetDataSet**(**token**: [JToken](../Json/Linq/JToken.md)): DataSet

**Parameters**

- **token** ([JToken](../Json/Linq/JToken.md))  

**Returns** DataSet

---

**GetDataSet**(**tokens**: List<[JToken](../Json/Linq/JToken.md)>, **useOneTable**: bool): DataSet

**Parameters**

- **tokens** (List<[JToken](../Json/Linq/JToken.md)>)  
- **useOneTable** (bool)  

**Returns** DataSet

---

**GetDataSet**(****: bytecontent): DataSet

**Parameters**

- **** (bytecontent)  

**Returns** DataSet

---

**GetDataSet**(**text**: string): DataSet

**Parameters**

- **text** (string)  

**Returns** DataSet

---

**GetDataSet**(**element**: XElement): DataSet

**Parameters**

- **element** (XElement)  

**Returns** DataSet


---

#### GetDataSetFromFile `static`

**GetDataSetFromFile**(**path**: string): DataSet

**Parameters**

- **path** (string)  

**Returns** DataSet


---

#### GetDataSetFromXml `static`

**GetDataSetFromXml**(****: bytearray): DataSet

**Parameters**

- **** (bytearray)  

**Returns** DataSet


---

#### GetDataSetFromXmlFile `static`

**GetDataSetFromXmlFile**(**path**: string): DataSet

**Parameters**

- **path** (string)  

**Returns** DataSet

