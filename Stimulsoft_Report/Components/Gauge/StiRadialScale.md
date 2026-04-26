---
title: "StiRadialScale Class"
---

## StiRadialScale Class

**Namespace:** `Stimulsoft.Report.Components.Gauge`

### Inheritance

Inherits from: StiScaleBase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRadialScale**() |  |

**StiRadialScale**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Center** | PointF |  |
| **Radius** | float |  |
| **RadiusMode** | [StiRadiusMode](../../Gauge/StiRadiusMode.md) |  |
| **Skin** | [StiRadialScaleSkin](../../Gauge/StiRadialScaleSkin.md) |  |
| **StartAngle** | float |  |
| **SweepAngle** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **Clone** | object |  |
| **InteractiveClick** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiGaugeStyle): void

**Parameters**

- **style** (IStiGaugeStyle)  


---

#### Clone

**Clone**(): object

**Returns** object


---

#### InteractiveClick

**InteractiveClick**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

