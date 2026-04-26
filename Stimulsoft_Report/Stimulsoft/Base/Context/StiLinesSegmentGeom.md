---
title: "StiLinesSegmentGeom Class"
---

## StiLinesSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLinesSegmentGeom**(PointFpoints ) |  |
| **StiLinesSegmentGeom**(PointFpoints , [StiAnimation](Animation/StiAnimation.md) animation) |  |

**StiLinesSegmentGeom**(****: PointFpoints)

**Parameters**

- **** (PointFpoints)  

---

**StiLinesSegmentGeom**(****: PointFpoints, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **** (PointFpoints)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
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

