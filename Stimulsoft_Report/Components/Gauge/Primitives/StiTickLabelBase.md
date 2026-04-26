---
title: "StiTickLabelBase Class"
---

## StiTickLabelBase Class

**Namespace:** `Stimulsoft.Report.Components.Gauge.Primitives`

### Inheritance

Inherits from: StiTickBase  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Font** | [Font](../../../../Stimulsoft_Drawing/root/Font.md) |  |
| **TextBrush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **TextFormat** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetTextForRender** *(+2 overloads)* | string |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### GetTextForRender

**GetTextForRender**(**value**: double, **format**: string): string

**Parameters**

- **value** (double)  
- **format** (string)  

**Returns** string

---

**GetTextForRender**(**value**: string): string

**Parameters**

- **value** (string)  

**Returns** string

---

**GetTextForRender**(**value**: string, **format**: string): string

**Parameters**

- **value** (string)  
- **format** (string)  

**Returns** string


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

