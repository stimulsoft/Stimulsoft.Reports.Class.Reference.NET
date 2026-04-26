---
title: "StiCode11BarCodeType Class"
---

## StiCode11BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCode11BarCodeType**() |  |
| **StiCode11BarCodeType**(float module, float height, [StiCode11CheckSum](StiCode11CheckSum.md) checksum) |  |

**StiCode11BarCodeType**()

---

**StiCode11BarCodeType**(**module**: float, **height**: float, **checksum**: [StiCode11CheckSum](StiCode11CheckSum.md))

**Parameters**

- **module** (float)  
- **height** (float)  
- **checksum** ([StiCode11CheckSum](StiCode11CheckSum.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Checksum** | [StiCode11CheckSum](StiCode11CheckSum.md) |  |

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
| **Code11LineHeightForCut** | float |  |
| **Code11LineHeightLong** | float |  |
| **Code11LineHeightShort** | float |  |
| **Code11MainHeight** | float |  |
| **Code11SpaceBottom** | float |  |
| **Code11SpaceLeft** | float |  |
| **Code11SpaceRight** | float |  |
| **Code11SpaceTop** | float |  |
| **Code11StartStopSymbolIndex** | int |  |
| **Code11Symbols** | string |  |
| **Code11TextHeight** | float |  |
| **Code11TextPosition** | float |  |
| **defaultCode11Module** | float |  |
