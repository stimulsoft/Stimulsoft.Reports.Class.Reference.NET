---
title: "StiRadarAxis Class"
---

## StiRadarAxis Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Implements: IStiRadarAxis  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRadarAxis**() |  |

**StiRadarAxis**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Area** | [IStiRadarArea](IStiRadarArea.md) |  |
| **Core** | StiRadarAxisCoreXF |  |
| **Range** | IStiAxisRange |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


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

