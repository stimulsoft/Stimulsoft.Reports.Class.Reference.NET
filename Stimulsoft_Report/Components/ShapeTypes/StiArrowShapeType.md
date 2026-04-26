---
title: "StiArrowShapeType Class"
---

## StiArrowShapeType Class

**Namespace:** `Stimulsoft.Report.Components.ShapeTypes`

### Inheritance

Inherits from: StiShapeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiArrowShapeType**() | Creates a new arrow. |
| **StiArrowShapeType**([StiShapeDirection](StiShapeDirection.md) direction, float arrowWidth, float arrowHeight) | Creates a new arrow with specified arguments. |

**StiArrowShapeType**()

Creates a new arrow.

---

**StiArrowShapeType**(**direction**: [StiShapeDirection](StiShapeDirection.md), **arrowWidth**: float, **arrowHeight**: float)

Creates a new arrow with specified arguments.

**Parameters**

- **direction** ([StiShapeDirection](StiShapeDirection.md)) — Arrow direction.  
- **arrowWidth** (float) — Arrow width factor.  
- **arrowHeight** (float) — Arrow height factor.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Direction** | [StiShapeDirection](StiShapeDirection.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

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

