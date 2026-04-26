---
title: "StiEllipseGeom Class"
---

## StiEllipseGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEllipseGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) borderPen, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex) |  |
| **StiEllipseGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) borderPen, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, string toolTip) |  |

**StiEllipseGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int)

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  

---

**StiEllipseGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int, **toolTip**: string)

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  
- **toolTip** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderPen** | [StiPenGeom](StiPenGeom.md) |  |
| **ElementIndex** | int |  |
| **Interaction** | [StiInteractionDataGeom](StiInteractionDataGeom.md) |  |
| **Rect** | object |  |
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

