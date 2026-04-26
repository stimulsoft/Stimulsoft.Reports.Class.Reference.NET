---
title: "StiCurveSegmentGeom Class"
---

## StiCurveSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCurveSegmentGeom**(PointFpoints , float tension) |  |
| **StiCurveSegmentGeom**(PointFpoints , float tension, [StiAnimation](Animation/StiAnimation.md) animation) |  |

**StiCurveSegmentGeom**(****: PointFpoints, **tension**: float)

**Parameters**

- **** (PointFpoints)  
- **tension** (float)  

---

**StiCurveSegmentGeom**(****: PointFpoints, **tension**: float, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **** (PointFpoints)  
- **tension** (float)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
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

