---
title: "StiTickMarkBase Class"
---

## StiTickMarkBase Class

**Namespace:** `Stimulsoft.Report.Components.Gauge.Primitives`

### Inheritance

Inherits from: StiTickBase  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BorderBrush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderWidth** | float |  |
| **Brush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CustomSkin** | [StiGaugeElementSkin](../../../Gauge/StiGaugeElementSkin.md) |  |
| **RelativeHeight** | float |  |
| **RelativeWidth** | float |  |
| **Skin** | [StiTickMarkSkin](../../../Gauge/StiTickMarkSkin.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetActualSkin** | [StiGaugeElementSkin](../../../Gauge/StiGaugeElementSkin.md) |  |
| **GetRelativeHeight** | float |  |
| **GetRelativeWidth** | float |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### GetActualSkin

**GetActualSkin**(): [StiGaugeElementSkin](../../../Gauge/StiGaugeElementSkin.md)

**Returns** [StiGaugeElementSkin](../../../Gauge/StiGaugeElementSkin.md)


---

#### GetRelativeHeight

**GetRelativeHeight**(**value**: float?): float

**Parameters**

- **value** (float?)  

**Returns** float


---

#### GetRelativeWidth

**GetRelativeWidth**(**value**: float?): float

**Parameters**

- **value** (float?)  

**Returns** float


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

