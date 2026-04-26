---
title: "StiLineSegmentGeom Class"
---

## StiLineSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLineSegmentGeom**(PointF start, PointF end) |  |
| **StiLineSegmentGeom**(PointF start, PointF end, [StiAnimation](Animation/StiAnimation.md) animation) |  |
| **StiLineSegmentGeom**(float x1, float y1, float x2, float y2) |  |

**StiLineSegmentGeom**(**start**: PointF, **end**: PointF)

**Parameters**

- **start** (PointF)  
- **end** (PointF)  

---

**StiLineSegmentGeom**(**start**: PointF, **end**: PointF, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **start** (PointF)  
- **end** (PointF)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  

---

**StiLineSegmentGeom**(**x1**: float, **y1**: float, **x2**: float, **y2**: float)

**Parameters**

- **x1** (float)  
- **y1** (float)  
- **x2** (float)  
- **y2** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
| **X1** | float |  |
| **X2** | float |  |
| **Y1** | float |  |
| **Y2** | float |  |

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

