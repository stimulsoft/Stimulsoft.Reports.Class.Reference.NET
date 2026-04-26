---
title: "StiPanel Class"
---

## StiPanel Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiContainer  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPanel**() | Creates a new panel. |
| **StiPanel**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new panel. |

**StiPanel**()

Creates a new panel.

---

**StiPanel**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new panel.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the container.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GapAfterLastColumn** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColumnWidth** | double |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetColumnWidth

**GetColumnWidth**(): double

**Returns** double


---

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

