---
title: "StiRoyalMail4StateBarCodeType Class"
---

## StiRoyalMail4StateBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRoyalMail4StateBarCodeType**() |  |
| **StiRoyalMail4StateBarCodeType**(float module, float height, [StiCheckSum](StiCheckSum.md) checkSum) |  |

**StiRoyalMail4StateBarCodeType**()

---

**StiRoyalMail4StateBarCodeType**(**module**: float, **height**: float, **checkSum**: [StiCheckSum](StiCheckSum.md))

**Parameters**

- **module** (float)  
- **height** (float)  
- **checkSum** ([StiCheckSum](StiCheckSum.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CheckSum** | [StiCheckSum](StiCheckSum.md) |  |
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
| **RoyalMail4StateLineHeightForCut** | float |  |
| **RoyalMail4StateLineHeightLong** | float |  |
| **RoyalMail4StateLineHeightShort** | float |  |
| **RoyalMail4StateMainHeight** | float |  |
| **RoyalMail4StateSpaceBottom** | float |  |
| **RoyalMail4StateSpaceLeft** | float |  |
| **RoyalMail4StateSpaceRight** | float |  |
| **RoyalMail4StateSpaceTop** | float |  |
| **RoyalMail4StateSymbols** | string |  |
| **RoyalMail4StateTextHeight** | float |  |
| **RoyalMail4StateTextPosition** | float |  |
