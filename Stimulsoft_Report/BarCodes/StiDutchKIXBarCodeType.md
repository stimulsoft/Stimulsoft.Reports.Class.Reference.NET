---
title: "StiDutchKIXBarCodeType Class"
---

## StiDutchKIXBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

The class describes the Barcode type - Royal TPG Post KIX 4-State Barcode.

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDutchKIXBarCodeType**() |  |
| **StiDutchKIXBarCodeType**(float module, float height) |  |

**StiDutchKIXBarCodeType**()

---

**StiDutchKIXBarCodeType**(**module**: float, **height**: float)

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
| **DutchKIXLineHeightForCut** | float |  |
| **DutchKIXLineHeightLong** | float |  |
| **DutchKIXLineHeightShort** | float |  |
| **DutchKIXMainHeight** | float |  |
| **DutchKIXSpaceBottom** | float |  |
| **DutchKIXSpaceLeft** | float |  |
| **DutchKIXSpaceRight** | float |  |
| **DutchKIXSpaceTop** | float |  |
| **DutchKIXSymbols** | string |  |
| **DutchKIXTextHeight** | float |  |
| **DutchKIXTextPosition** | float |  |
