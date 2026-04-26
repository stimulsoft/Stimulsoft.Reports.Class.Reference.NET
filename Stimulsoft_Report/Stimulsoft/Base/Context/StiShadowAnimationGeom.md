---
title: "StiShadowAnimationGeom Class"
---

## StiShadowAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiShadowAnimationGeom**(RectangleF rect, int shadowWidth, StiCornerRadius cornerRadius, [StiAnimation](Animation/StiAnimation.md) animation) |  |
| **StiShadowAnimationGeom**(RectangleF rect, double radiusX, double radiusY, int shadowWidth, [StiAnimation](Animation/StiAnimation.md) animation) |  |

**StiShadowAnimationGeom**(**rect**: RectangleF, **shadowWidth**: int, **cornerRadius**: StiCornerRadius, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **rect** (RectangleF)  
- **shadowWidth** (int)  
- **cornerRadius** (StiCornerRadius)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  

---

**StiShadowAnimationGeom**(**rect**: RectangleF, **radiusX**: double, **radiusY**: double, **shadowWidth**: int, **animation**: [StiAnimation](Animation/StiAnimation.md))

**Parameters**

- **rect** (RectangleF)  
- **radiusX** (double)  
- **radiusY** (double)  
- **shadowWidth** (int)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CornerRadius** | StiCornerRadius |  |
| **RadiusX** | double |  |
| **RadiusY** | double |  |
| **Rect** | RectangleF |  |
| **ShadowWidth** | int |  |

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

