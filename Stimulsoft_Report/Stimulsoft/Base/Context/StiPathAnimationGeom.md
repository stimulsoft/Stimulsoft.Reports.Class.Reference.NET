---
title: "StiPathAnimationGeom Class"
---

## StiPathAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **Geoms** | List<[StiSegmentGeom](StiSegmentGeom.md)> |  |
| **GetBoundsState** `static` | object |  |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Rect** | object |  |
| **Tag** | object |  |
| **WpfBackColor** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |

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

