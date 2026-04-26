---
title: "StiITF14BarCodeType Class"
---

## StiITF14BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiITF14BarCodeType**() |  |
| **StiITF14BarCodeType**(float module, float height, float ratio, bool printVerticalBars) |  |

**StiITF14BarCodeType**()

---

**StiITF14BarCodeType**(**module**: float, **height**: float, **ratio**: float, **printVerticalBars**: bool)

**Parameters**

- **module** (float)  
- **height** (float)  
- **ratio** (float)  
- **printVerticalBars** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PrintVerticalBars** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **DrawBaseLines** | void |  |
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

#### DrawBaseLines

**DrawBaseLines**(**context**: object, **foreBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)): void

**Parameters**

- **context** (object)  
- **foreBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  


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

