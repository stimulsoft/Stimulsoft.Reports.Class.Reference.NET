---
title: "StiBorderGeom Class"
---

## StiBorderGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBorderGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) backgroundMouseOver, [StiPenGeom](StiPenGeom.md) borderPen, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex) |  |
| **StiBorderGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) backgroundMouseOver, [StiPenGeom](StiPenGeom.md) borderPen, object rect, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, int elementIndex, float angle, [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md) rotationMode) |  |
| **StiBorderGeom**([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) backgroundMouseOver, [StiPenGeom](StiPenGeom.md) borderPen, object rect, StiCornerRadius cornerRadius, [StiInteractionDataGeom](StiInteractionDataGeom.md) interaction, string tooltip, int elementIndex) |  |

**StiBorderGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **backgroundMouseOver**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int)

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **backgroundMouseOver** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  

---

**StiBorderGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **backgroundMouseOver**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int, **angle**: float, **rotationMode**: [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md))

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **backgroundMouseOver** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  
- **angle** (float)  
- **rotationMode** ([StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md))  

---

**StiBorderGeom**(**background**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **backgroundMouseOver**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **cornerRadius**: StiCornerRadius, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **tooltip**: string, **elementIndex**: int)

**Parameters**

- **background** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **backgroundMouseOver** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **cornerRadius** (StiCornerRadius)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **tooltip** (string)  
- **elementIndex** (int)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Angle** | float |  |
| **Background** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BackgroundMouseOver** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderPen** | [StiPenGeom](StiPenGeom.md) |  |
| **CornerRadius** | StiCornerRadius |  |
| **ElementIndex** | int |  |
| **Interaction** | [StiInteractionDataGeom](StiInteractionDataGeom.md) |  |
| **Rect** | object |  |
| **RotationMode** | [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md) |  |
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

