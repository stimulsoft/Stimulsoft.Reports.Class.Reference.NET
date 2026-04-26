---
title: "StiCode39BarCodeType Class"
---

## StiCode39BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCode39BarCodeType**() |  |
| **StiCode39BarCodeType**(float module, float height, float ratio, [StiCheckSum](StiCheckSum.md) checkSum) |  |

**StiCode39BarCodeType**()

---

**StiCode39BarCodeType**(**module**: float, **height**: float, **ratio**: float, **checkSum**: [StiCheckSum](StiCheckSum.md))

**Parameters**

- **module** (float)  
- **height** (float)  
- **ratio** (float)  
- **checkSum** ([StiCheckSum](StiCheckSum.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CheckSum** | [StiCheckSum](StiCheckSum.md) |  |

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
| **Code39LineHeightForCut** | float |  |
| **Code39LineHeightLong** | float |  |
| **Code39LineHeightShort** | float |  |
| **Code39MainHeight** | float |  |
| **Code39SpaceBottom** | float |  |
| **Code39SpaceLeft** | float |  |
| **Code39SpaceRight** | float |  |
| **Code39SpaceTop** | float |  |
| **Code39StartStopSymbolIndex** | int |  |
| **Code39Symbols** | string |  |
| **Code39TextHeight** | float |  |
| **Code39TextPosition** | float |  |
