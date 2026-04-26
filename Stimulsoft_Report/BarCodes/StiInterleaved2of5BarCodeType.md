---
title: "StiInterleaved2of5BarCodeType Class"
---

## StiInterleaved2of5BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiInterleaved2of5BarCodeType**() |  |
| **StiInterleaved2of5BarCodeType**(float module, float height, float ratio) |  |

**StiInterleaved2of5BarCodeType**()

---

**StiInterleaved2of5BarCodeType**(**module**: float, **height**: float, **ratio**: float)

**Parameters**

- **module** (float)  
- **height** (float)  
- **ratio** (float)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

Draws the bar code with the specified parameters.

**Parameters**

- **context** (object) — Context for drawing.  
- **barCode** (StiBarCode) — Component that invokes drawing.  
- **rect** (RectangleF) — The rectangle that shows coordinates for drawing.  
- **zoom** (float) — Zoom of drawing.  


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

