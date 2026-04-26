---
title: "StiAxis3D Class"
---

## StiAxis3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Implements: IStiAxis3D  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxis3D**() |  |

**StiAxis3D**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Area** | [IStiAxisArea3D](IStiAxisArea3D.md) |  |
| **Core** | StiAxisCoreXF3D |  |
| **Info** | [StiAxisInfoXF3D](StiAxisInfoXF3D.md) |  |
| **Labels** | IStiAxisLabels3D |  |
| **LineColor** | Color |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShouldSerializeVisible** | bool |  |

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


---

#### ShouldSerializeVisible

**ShouldSerializeVisible**(): bool

**Returns** bool

