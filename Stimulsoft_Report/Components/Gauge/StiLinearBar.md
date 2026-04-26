---
title: "StiLinearBar Class"
---

## StiLinearBar Class

**Namespace:** `Stimulsoft.Report.Components.Gauge`

### Inheritance

Inherits from: [StiBarBase](Primitives/StiBarBase.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Skin** | [StiLinearBarSkin](../../Gauge/StiLinearBarSkin.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **CheckActualBrushForTopGeometry** | void |  |
| **LoadFromJsonObject** | void |  |
| **OnRangeColorChanged** | void |  |
| **Reset** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiGaugeStyle): void

**Parameters**

- **style** (IStiGaugeStyle)  


---

#### CheckActualBrushForTopGeometry

**CheckActualBrushForTopGeometry**(): void


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### OnRangeColorChanged

**OnRangeColorChanged**(): void


---

#### Reset

**Reset**(): void


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **defaultIndex** | int |  |
| **isStartGreaterEnd** | bool |  |
| **isThisStartGreaterEnd** | bool |  |
| **maxWidth** | float |  |
| **minWidth** | float |  |
| **mixedColorIndex** | int |  |
| **offset** | float |  |
| **rect** | RectangleF |  |
| **scale** | StiLinearScale |  |
| **standardBackground** | bool |  |
| **state** | bool |  |
