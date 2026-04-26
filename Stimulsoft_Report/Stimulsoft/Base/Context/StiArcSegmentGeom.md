---
title: "StiArcSegmentGeom Class"
---

## StiArcSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiArcSegmentGeom**(RectangleF rect, float startAngle, float sweepAngle) |  |
| **StiArcSegmentGeom**(RectangleF rect, float startAngle, float sweepAngle, float realStartAngle, float realSweepAngle) |  |

**StiArcSegmentGeom**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float)

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  

---

**StiArcSegmentGeom**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float, **realStartAngle**: float, **realSweepAngle**: float)

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  
- **realStartAngle** (float)  
- **realSweepAngle** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animation** | [StiAnimation](Animation/StiAnimation.md) |  |
| **CrossElipseDraw** | bool |  |
| **RealStartAngle** | float? |  |
| **RealSweepAngle** | float? |  |
| **Rect** | RectangleF |  |
| **StartAngle** | float |  |
| **SweepAngle** | float |  |

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

