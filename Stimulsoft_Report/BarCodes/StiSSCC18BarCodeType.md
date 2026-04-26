---
title: "StiSSCC18BarCodeType Class"
---

## StiSSCC18BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

The class describes the Barcode type - Serial Shipping Container Code (SSCC-18).

### Inheritance

Inherits from: [StiCode128cBarCodeType](StiCode128cBarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSSCC18BarCodeType**() |  |
| **StiSSCC18BarCodeType**(float module, float height) |  |

**StiSSCC18BarCodeType**()

---

**StiSSCC18BarCodeType**(**module**: float, **height**: float)

**Parameters**

- **module** (float)  
- **height** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CompanyPrefix** | string |  |
| **ExtensionDigit** | string |  |
| **SerialNumber** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **GetCombinedCode** | string |  |
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

#### GetCombinedCode

**GetCombinedCode**(): string

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

