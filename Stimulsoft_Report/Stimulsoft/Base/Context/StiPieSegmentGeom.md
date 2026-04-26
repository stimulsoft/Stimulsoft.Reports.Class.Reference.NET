---
title: "StiPieSegmentGeom Class"
---

## StiPieSegmentGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiSegmentGeom](StiSegmentGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPieSegmentGeom**(RectangleF rect, float startAngle, float sweepAngle, [StiAnimation](Animation/StiAnimation.md) animation) |  |
| **StiPieSegmentGeom**(RectangleF rect, float startAngle, float sweepAngle, float realStartAngle, float realSweepAngle, [StiAnimation](Animation/StiAnimation.md) animation) |  |

**StiPieSegmentGeom**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  

---

**StiPieSegmentGeom**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float, **realStartAngle**: float, **realSweepAngle**: float, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  
- **realStartAngle** (float)  
- **realSweepAngle** (float)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


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


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **EndAngle** | float |  |
