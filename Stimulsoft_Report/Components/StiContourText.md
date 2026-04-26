---
title: "StiContourText Class"
---

## StiContourText Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiText  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiContourText**() | Creates a new contour text. |
| **StiContourText**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new contour text. |
| **StiContourText**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect, string text) | Creates a new contour text. |

**StiContourText**()

Creates a new contour text.

---

**StiContourText**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new contour text.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — Rectangle describes size and position of the component.  

---

**StiContourText**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string)

Creates a new contour text.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — Rectangle describes size and position of the component.  
- **text** (string) — Text.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ContourColor** | Color |  |
| **Size** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

