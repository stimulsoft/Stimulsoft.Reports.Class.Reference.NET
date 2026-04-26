---
title: "StiAustraliaPost4StateBarCodeType Class"
---

## StiAustraliaPost4StateBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAustraliaPost4StateBarCodeType**() |  |
| **StiAustraliaPost4StateBarCodeType**(float module, float height) |  |

**StiAustraliaPost4StateBarCodeType**()

---

**StiAustraliaPost4StateBarCodeType**(**module**: float, **height**: float)

**Parameters**

- **module** (float)  
- **height** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **TextAlignment** | StringAlignment |  |

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
| **AustraliaPost4StateLineHeightForCut** | float |  |
| **AustraliaPost4StateLineHeightLong** | float |  |
| **AustraliaPost4StateLineHeightShort** | float |  |
| **AustraliaPost4StateMainHeight** | float |  |
| **AustraliaPost4StateSpaceBottom** | float |  |
| **AustraliaPost4StateSpaceLeft** | float |  |
| **AustraliaPost4StateSpaceRight** | float |  |
| **AustraliaPost4StateSpaceTop** | float |  |
| **AustraliaPost4StateSymbolsC** | string |  |
| **AustraliaPost4StateSymbolsN** | string |  |
| **AustraliaPost4StateTextHeight** | float |  |
| **AustraliaPost4StateTextPosition** | float |  |
