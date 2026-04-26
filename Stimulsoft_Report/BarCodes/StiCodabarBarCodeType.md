---
title: "StiCodabarBarCodeType Class"
---

## StiCodabarBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCodabarBarCodeType**() |  |
| **StiCodabarBarCodeType**(float module, float height, float ratio) |  |

**StiCodabarBarCodeType**()

---

**StiCodabarBarCodeType**(**module**: float, **height**: float, **ratio**: float)

**Parameters**

- **module** (float)  
- **height** (float)  
- **ratio** (float)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CodeToBar** | string |  |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### CodeToBar

**CodeToBar**(**inputCode**: string): string

**Parameters**

- **inputCode** (string)  

**Returns** string


---

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
| **CodabarLineHeightForCut** | float |  |
| **CodabarLineHeightLong** | float |  |
| **CodabarLineHeightShort** | float |  |
| **CodabarMainHeight** | float |  |
| **CodabarSpaceBottom** | float |  |
| **CodabarSpaceLeft** | float |  |
| **CodabarSpaceRight** | float |  |
| **CodabarSpaceTop** | float |  |
| **CodabarTextHeight** | float |  |
| **CodabarTextPosition** | float |  |
