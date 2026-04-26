---
title: "StiGroupBoxControl Class"
---

## StiGroupBoxControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGroupBoxControl**() | Creates a new StiGroupBoxControl. |
| **StiGroupBoxControl**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiGroupBoxControl. |

**StiGroupBoxControl**()

Creates a new StiGroupBoxControl.

---

**StiGroupBoxControl**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiGroupBoxControl.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the control.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | GroupBox |  |
| **TextBinding** | string |  |

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

