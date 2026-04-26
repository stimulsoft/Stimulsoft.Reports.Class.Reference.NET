---
title: "StiXTopChartAxis Class"
---

## StiXTopChartAxis Class

**Namespace:** `Stimulsoft.Dashboard.Components.Chart`

### Inheritance

Inherits from: StiXChartAxis  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiXTopChartAxis**() |  |
| **StiXTopChartAxis**(StiChartAxisLabels labels, [StiXChartAxisTitle](StiXChartAxisTitle.md) title, bool visible) |  |

**StiXTopChartAxis**()

---

**StiXTopChartAxis**(**labels**: StiChartAxisLabels, **title**: [StiXChartAxisTitle](StiXChartAxisTitle.md), **visible**: bool)

**Parameters**

- **labels** (StiChartAxisLabels)  
- **title** ([StiXChartAxisTitle](StiXChartAxisTitle.md))  
- **visible** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Range** | StiChartAxisRange |  |
| **StartFromZero** | [StiAutoBool](../../../Stimulsoft_Base/root/StiAutoBool.md) |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShouldSerializeRange** | bool |  |
| **ShouldSerializeStartFromZero** | bool |  |
| **ShouldSerializeVisible** | bool |  |

---

### Method Details

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### ShouldSerializeRange

**ShouldSerializeRange**(): bool

**Returns** bool


---

#### ShouldSerializeStartFromZero

**ShouldSerializeStartFromZero**(): bool

**Returns** bool


---

#### ShouldSerializeVisible

**ShouldSerializeVisible**(): bool

**Returns** bool

