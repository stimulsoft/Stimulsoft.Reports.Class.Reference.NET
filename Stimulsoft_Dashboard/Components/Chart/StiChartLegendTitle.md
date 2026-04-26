---
title: "StiChartLegendTitle Class"
---

## StiChartLegendTitle Class

**Namespace:** `Stimulsoft.Dashboard.Components.Chart`

### Inheritance

Implements: [IStiExpressionParentComponent](../../../Stimulsoft_Report/Components/IStiExpressionParentComponent.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiChartLegendTitle**() |  |
| **StiChartLegendTitle**([Font](../../../Stimulsoft_Drawing/root/Font.md) font, string text, Color color) |  |

**StiChartLegendTitle**()

---

**StiChartLegendTitle**(**font**: [Font](../../../Stimulsoft_Drawing/root/Font.md), **text**: string, **color**: Color)

**Parameters**

- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  
- **text** (string)  
- **color** (Color)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **Font** | [Font](../../../Stimulsoft_Drawing/root/Font.md) |  |
| **ParentComponent** | StiComponent |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


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

