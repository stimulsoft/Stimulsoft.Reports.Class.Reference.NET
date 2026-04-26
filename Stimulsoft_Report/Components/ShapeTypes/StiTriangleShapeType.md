---
title: "StiTriangleShapeType Class"
---

## StiTriangleShapeType Class

**Namespace:** `Stimulsoft.Report.Components.ShapeTypes`

### Inheritance

Inherits from: StiShapeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTriangleShapeType**() | Creates a new triangle. |
| **StiTriangleShapeType**([StiShapeDirection](StiShapeDirection.md) direction) | Creates a new triangle with the specified direction. |

**StiTriangleShapeType**()

Creates a new triangle.

---

**StiTriangleShapeType**(**direction**: [StiShapeDirection](StiShapeDirection.md))

Creates a new triangle with the specified direction.

**Parameters**

- **direction** ([StiShapeDirection](StiShapeDirection.md)) — Triangle direction.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Direction** | [StiShapeDirection](StiShapeDirection.md) |  |

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

