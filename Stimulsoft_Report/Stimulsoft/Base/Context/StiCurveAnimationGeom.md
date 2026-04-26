---
title: "StiCurveAnimationGeom Class"
---

## StiCurveAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCurveAnimationGeom**([StiPenGeom](StiPenGeom.md) pen, PointFpoints , float tension, [StiAnimation](Animation/StiAnimation.md) animation) |  |

**StiCurveAnimationGeom**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints, **tension**: float, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  
- **tension** (float)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Points** | PointF[] |  |
| **Tension** | float |  |

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

