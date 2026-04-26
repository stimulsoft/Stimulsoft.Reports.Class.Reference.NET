---
title: "StiEllipseAnimationGeom Class"
---

## StiEllipseAnimationGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEllipseAnimationGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) borderPen, object rect, string toolTip, object tag, [StiAnimation](Animation/StiAnimation.md) animation, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction) |  |
| **StiEllipseAnimationGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) wpfBackColor, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiPenGeom](StiPenGeom.md) borderPen, object rect, string toolTip, object tag, [StiAnimation](Animation/StiAnimation.md) animation, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction) |  |

**StiEllipseAnimationGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md))

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

---

**StiEllipseAnimationGeom**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md))

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderPen** | [StiPenGeom](StiPenGeom.md) |  |
| **Rect** | object |  |
| **Tag** | object |  |
| **ToolTip** | string |  |
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

