---
title: "StiPostnetBarCodeType Class"
---

## StiPostnetBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPostnetBarCodeType**() |  |
| **StiPostnetBarCodeType**(float module, float height, float space) |  |

**StiPostnetBarCodeType**()

---

**StiPostnetBarCodeType**(**module**: float, **height**: float, **space**: float)

**Parameters**

- **module** (float)  
- **height** (float)  
- **space** (float)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **context** (object)  
- **barCode** (StiBarCode)  
- **rect** (RectangleF)  
- **zoom** (float)  


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **PostnetLineHeightForCut** | float |  |
| **PostnetLineHeightLong** | float |  |
| **PostnetLineHeightShort** | float |  |
| **PostnetMainHeight** | float |  |
| **PostnetSpaceBottom** | float |  |
| **PostnetSpaceLeft** | float |  |
| **PostnetSpaceRight** | float |  |
| **PostnetSpaceTop** | float |  |
| **PostnetSymbols** | string |  |
| **PostnetTextHeight** | float |  |
| **PostnetTextPosition** | float |  |
