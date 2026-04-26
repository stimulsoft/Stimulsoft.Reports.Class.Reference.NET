---
title: "StiTextGeom Class"
---

## StiTextGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiAnimationGeom](StiAnimationGeom.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Angle** | float |  |
| **Antialiasing** | bool |  |
| **Brush** | [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ElementIndex** | int |  |
| **Font** | [StiFontGeom](StiFontGeom.md) |  |
| **IsRotatedText** | bool |  |
| **IsRounded** | bool |  |
| **Location** | object |  |
| **MaximalWidth** | int? |  |
| **RotationMode** | StiRotationMode? |  |
| **StringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **Text** | string |  |
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

