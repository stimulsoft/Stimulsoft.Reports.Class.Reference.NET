---
title: "StiShadowGeom Class"
---

## StiShadowGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiShadowGeom**([StiContext](StiContext.md) shadowContext, RectangleF rect, float radius) |  |

**StiShadowGeom**(**shadowContext**: [StiContext](StiContext.md), **rect**: RectangleF, **radius**: float)

**Parameters**

- **shadowContext** ([StiContext](StiContext.md))  
- **rect** (RectangleF)  
- **radius** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Radius** | float |  |
| **Rect** | RectangleF |  |
| **ShadowContext** | [StiContext](StiContext.md) |  |

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

