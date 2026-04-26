---
title: "StiBarBase Class"
---

## StiBarBase Class

**Namespace:** `Stimulsoft.Report.Components.Gauge.Primitives`

### Inheritance

Inherits from: StiIndicatorBase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBarBase**() |  |

**StiBarBase**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BarType** | [StiBarRangeListType](../../../Gauge/StiBarRangeListType.md) |  |
| **EmptyBorderBrush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **EmptyBorderWidth** | float |  |
| **EmptyBrush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **EndWidth** | float |  |
| **Offset** | float |  |
| **RangeList** | StiBarRangeListCollection |  |
| **StartWidth** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckActualBrushForTopGeometry** | void |  |
| **Clone** | object |  |
| **LoadFromJsonObject** | void |  |
| **OnRangeColorChanged** | void |  |
| **OnValueChanged** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### CheckActualBrushForTopGeometry

**CheckActualBrushForTopGeometry**(): void


---

#### Clone

**Clone**(): object

**Returns** object


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### OnRangeColorChanged

**OnRangeColorChanged**(): void


---

#### OnValueChanged

**OnValueChanged**(): void


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

