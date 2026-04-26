---
title: "StiPathGeom Class"
---

## StiPathGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPathGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) pen, List<[StiSegmentGeom](StiSegmentGeom.md)> geoms, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, object tag) |  |
| **StiPathGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) pen, List<[StiSegmentGeom](StiSegmentGeom.md)> geoms, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, string toolTip, object tag) |  |

**StiPathGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **geoms**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int, **tag**: object)

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **geoms** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  
- **tag** (object)  

---

**StiPathGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **geoms**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int, **toolTip**: string, **tag**: object)

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **geoms** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  
- **toolTip** (string)  
- **tag** (object)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ElementIndex** | int |  |
| **Geoms** | List<[StiSegmentGeom](StiSegmentGeom.md)> |  |
| **GetBoundsState** `static` | object |  |
| **Interaction** | [StiInteractionDataGeom](StiInteractionDataGeom.md) |  |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Rect** | object |  |
| **Tag** | object |  |
| **ToolTip** | string |  |

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

