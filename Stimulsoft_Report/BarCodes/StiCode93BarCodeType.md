---
title: "StiCode93BarCodeType Class"
---

## StiCode93BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCode93BarCodeType**() |  |
| **StiCode93BarCodeType**(float module, float height, float ratio) |  |

**StiCode93BarCodeType**()

---

**StiCode93BarCodeType**(**module**: float, **height**: float, **ratio**: float)

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
| **Code93LineHeightForCut** | float |  |
| **Code93LineHeightLong** | float |  |
| **Code93LineHeightShort** | float |  |
| **Code93MainHeight** | float |  |
| **Code93SpaceBottom** | float |  |
| **Code93SpaceLeft** | float |  |
| **Code93SpaceRight** | float |  |
| **Code93SpaceTop** | float |  |
| **Code93TextHeight** | float |  |
| **Code93TextPosition** | float |  |
