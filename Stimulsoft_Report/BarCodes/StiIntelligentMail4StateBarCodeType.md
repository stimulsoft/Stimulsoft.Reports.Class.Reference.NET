---
title: "StiIntelligentMail4StateBarCodeType Class"
---

## StiIntelligentMail4StateBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIntelligentMail4StateBarCodeType**() |  |
| **StiIntelligentMail4StateBarCodeType**(float module, float height) |  |

**StiIntelligentMail4StateBarCodeType**()

---

**StiIntelligentMail4StateBarCodeType**(**module**: float, **height**: float)

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
| **IntelligentMail4StateLineHeightForCut** | float |  |
| **IntelligentMail4StateLineHeightLong** | float |  |
| **IntelligentMail4StateLineHeightShort** | float |  |
| **IntelligentMail4StateMainHeight** | float |  |
| **IntelligentMail4StateSpaceBottom** | float |  |
| **IntelligentMail4StateSpaceLeft** | float |  |
| **IntelligentMail4StateSpaceRight** | float |  |
| **IntelligentMail4StateSpaceTop** | float |  |
| **IntelligentMail4StateTextHeight** | float |  |
| **IntelligentMail4StateTextPosition** | float |  |
| **IntelligentMail4StateWideToNarrowRatio** | float |  |
