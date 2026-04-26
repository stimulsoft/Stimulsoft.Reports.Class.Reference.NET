---
title: "StiLinePrimitive Class"
---

## StiLinePrimitive Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiPrimitive](StiPrimitive.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLinePrimitive**() | Creates a new StiLinePrimitive. |
| **StiLinePrimitive**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiLinePrimitive. |

**StiLinePrimitive**()

Creates a new StiLinePrimitive.

---

**StiLinePrimitive**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiLinePrimitive.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **Size** | float |  |
| **Style** | [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) |  |

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

