---
title: "StiGisToDataSetConverter Class"
---

## StiGisToDataSetConverter Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSetFromGeoJson** `static` *(+1 overloads)* | DataSet |  |
| **GetDataSetFromWkt** `static` *(+1 overloads)* | DataSet |  |

---

### Method Details

#### GetDataSetFromGeoJson `static`

**GetDataSetFromGeoJson**(****: bytecontent, **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytecontent)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSetFromGeoJson**(**jObject**: [JObject](../Json/Linq/JObject.md), **maxDataRows**: int?): DataSet

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  
- **maxDataRows** (int?)  

**Returns** DataSet


---

#### GetDataSetFromWkt `static`

**GetDataSetFromWkt**(****: bytecontent, **separator**: string, **maxDataRows**: int?): DataSet

**Parameters**

- **** (bytecontent)  
- **separator** (string)  
- **maxDataRows** (int?)  

**Returns** DataSet

---

**GetDataSetFromWkt**(**text**: string, **separator**: string, **maxDataRows**: int?): DataSet

**Parameters**

- **text** (string)  
- **separator** (string)  
- **maxDataRows** (int?)  

**Returns** DataSet

