---
title: "StiYRightChartAxis Class"
---

## StiYRightChartAxis Class

**Namespace:** `Stimulsoft.Dashboard.Components.Chart`

### Inheritance

Inherits from: StiYChartAxis  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiYRightChartAxis**() |  |
| **StiYRightChartAxis**(StiChartAxisLabels labels, [StiYChartAxisTitle](StiYChartAxisTitle.md) title, bool visible) |  |

**StiYRightChartAxis**()

---

**StiYRightChartAxis**(**labels**: StiChartAxisLabels, **title**: [StiYChartAxisTitle](StiYChartAxisTitle.md), **visible**: bool)

**Parameters**

- **labels** (StiChartAxisLabels)  
- **title** ([StiYChartAxisTitle](StiYChartAxisTitle.md))  
- **visible** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Labels** | StiChartAxisLabels |  |
| **Range** | StiChartAxisRange |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShouldSerializeLabels** | bool |  |
| **ShouldSerializeRange** | bool |  |
| **ShouldSerializeVisible** | bool |  |

---

### Method Details

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### ShouldSerializeLabels

**ShouldSerializeLabels**(): bool

**Returns** bool


---

#### ShouldSerializeRange

**ShouldSerializeRange**(): bool

**Returns** bool


---

#### ShouldSerializeVisible

**ShouldSerializeVisible**(): bool

**Returns** bool

