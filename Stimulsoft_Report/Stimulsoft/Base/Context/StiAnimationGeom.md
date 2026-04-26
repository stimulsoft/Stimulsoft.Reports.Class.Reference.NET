---
title: "StiAnimationGeom Class"
---

## StiAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAnimationGeom**([StiAnimation](Animation/StiAnimation.md) animation, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction) |  |

**StiAnimationGeom**(**animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md))

**Parameters**

- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
| **Interaction** | [StiInteractionDataGeom](StiInteractionDataGeom.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

