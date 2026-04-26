---
title: "StiMaxicodeBarCodeType Class"
---

## StiMaxicodeBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMaxicodeBarCodeType**() |  |
| **StiMaxicodeBarCodeType**([StiMaxicodeMode](StiMaxicodeMode.md) mode, int structuredAppendPosition, int structuredAppendTotal, bool processTilde) |  |
| **StiMaxicodeBarCodeType**([StiMaxicodeMode](StiMaxicodeMode.md) mode, int structuredAppendPosition, int structuredAppendTotal, bool processTilde, bool trimExcessData) |  |

**StiMaxicodeBarCodeType**()

---

**StiMaxicodeBarCodeType**(**mode**: [StiMaxicodeMode](StiMaxicodeMode.md), **structuredAppendPosition**: int, **structuredAppendTotal**: int, **processTilde**: bool)

**Parameters**

- **mode** ([StiMaxicodeMode](StiMaxicodeMode.md))  
- **structuredAppendPosition** (int)  
- **structuredAppendTotal** (int)  
- **processTilde** (bool)  

---

**StiMaxicodeBarCodeType**(**mode**: [StiMaxicodeMode](StiMaxicodeMode.md), **structuredAppendPosition**: int, **structuredAppendTotal**: int, **processTilde**: bool, **trimExcessData**: bool)

**Parameters**

- **mode** ([StiMaxicodeMode](StiMaxicodeMode.md))  
- **structuredAppendPosition** (int)  
- **structuredAppendTotal** (int)  
- **processTilde** (bool)  
- **trimExcessData** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Mode** | [StiMaxicodeMode](StiMaxicodeMode.md) |  |
| **ProcessTilde** | bool |  |
| **StructuredAppendPosition** | int |  |
| **StructuredAppendTotal** | int |  |
| **TrimExcessData** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **GetEciEncoding** | int |  |
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

#### GetEciEncoding

**GetEciEncoding**(): int

**Returns** int


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
| **ErrorMessage** | string |  |
| **Matrix** | byte[] |  |
