---
title: "StiDoughnutAreaIndicatorValue Class"
---

## StiDoughnutAreaIndicatorValue Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Implements: IStiDoughnutAreaIndicatorValue  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDoughnutAreaIndicatorValue**() |  |
| **StiDoughnutAreaIndicatorValue**(string value, Color color) |  |

**StiDoughnutAreaIndicatorValue**()

---

**StiDoughnutAreaIndicatorValue**(**value**: string, **color**: Color)

**Parameters**

- **value** (string)  
- **color** (Color)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **ParentComponent** | StiComponent |  |
| **Value** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **GetColor** | Color |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### GetColor

**GetColor**(): Color

**Returns** Color


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

