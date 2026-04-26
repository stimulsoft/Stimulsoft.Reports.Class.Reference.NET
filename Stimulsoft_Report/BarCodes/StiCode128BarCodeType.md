---
title: "StiCode128BarCodeType Class"
---

## StiCode128BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCode128BarCodeType**(float module, float height) |  |

**StiCode128BarCodeType**(**module**: float, **height**: float)

**Parameters**

- **module** (float)  
- **height** (float)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CodeToBar** | string |  |
| **EncodeAuto** `static` | string |  |
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

#### EncodeAuto `static`

**EncodeAuto**(**inputText**: string, **encodeAsEan**: bool): string

**Parameters**

- **inputText** (string)  
- **encodeAsEan** (bool)  

**Returns** string


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
| **Code128LineHeightForCut** | float |  |
| **Code128LineHeightLong** | float |  |
| **Code128LineHeightShort** | float |  |
| **Code128MainHeight** | float |  |
| **Code128SpaceBottom** | float |  |
| **Code128SpaceLeft** | float |  |
| **Code128SpaceRight** | float |  |
| **Code128SpaceTop** | float |  |
| **Code128TextHeight** | float |  |
| **Code128TextPosition** | float |  |
| **DefaultCodeSetAB** | CodeSet |  |
