---
title: "StiLinesAnimationGeom Class"
---

## StiLinesAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLinesAnimationGeom**([StiPenGeom](StiPenGeom.md) pen, PointFpoints , [StiAnimation](Animation/StiAnimation.md) animation) |  |

**StiLinesAnimationGeom**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Points** | PointF[] |  |

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

