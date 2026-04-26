---
title: "StiPharmacodeBarCodeType Class"
---

## StiPharmacodeBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPharmacodeBarCodeType**() |  |
| **StiPharmacodeBarCodeType**(float module, float height) |  |

**StiPharmacodeBarCodeType**()

---

**StiPharmacodeBarCodeType**(**module**: float, **height**: float)

**Parameters**

- **module** (float)  
- **height** (float)  


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
| **PharmacodeLineHeightForCut** | float |  |
| **PharmacodeLineHeightLong** | float |  |
| **PharmacodeLineHeightShort** | float |  |
| **PharmacodeMainHeight** | float |  |
| **PharmacodeSpaceBottom** | float |  |
| **PharmacodeSpaceLeft** | float |  |
| **PharmacodeSpaceRight** | float |  |
| **PharmacodeSpaceTop** | float |  |
| **PharmacodeSymbols** | string |  |
| **PharmacodeTextHeight** | float |  |
| **PharmacodeTextPosition** | float |  |
| **defaultPharmacodeModule** | float |  |
