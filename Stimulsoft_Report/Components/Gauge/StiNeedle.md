---
title: "StiNeedle Class"
---

## StiNeedle Class

**Namespace:** `Stimulsoft.Report.Components.Gauge`

### Inheritance

Inherits from: StiIndicatorBase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiNeedle**() |  |

**StiNeedle**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AutoCalculateCenterPoint** | bool |  |
| **CapBorderBrush** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CapBorderWidth** | float |  |
| **CapBrush** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CenterPoint** | PointF |  |
| **CustomSkin** | [StiGaugeElementSkin](../../Gauge/StiGaugeElementSkin.md) |  |
| **EndWidth** | float |  |
| **Font** | [Font](../../../Stimulsoft_Drawing/root/Font.md) |  |
| **Format** | string |  |
| **OffsetNeedle** | float |  |
| **RelativeHeight** | float |  |
| **RelativeWidth** | float |  |
| **ShowValue** | bool |  |
| **Skin** | [StiNeedleSkin](../../Gauge/StiNeedleSkin.md) |  |
| **StartWidth** | float |  |
| **TextBrush** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiGaugeStyle): void

**Parameters**

- **style** (IStiGaugeStyle)  


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

