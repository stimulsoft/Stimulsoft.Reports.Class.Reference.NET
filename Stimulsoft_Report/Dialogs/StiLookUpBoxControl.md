---
title: "StiLookUpBoxControl Class"
---

## StiLookUpBoxControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`

### Inheritance

Inherits from: [StiComboBoxControl](StiComboBoxControl.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLookUpBoxControl**() | Creates a new StiComboBoxControl. |
| **StiLookUpBoxControl**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiComboBoxControl. |

**StiLookUpBoxControl**()

Creates a new StiComboBoxControl.

---

**StiLookUpBoxControl**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiComboBoxControl.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the control.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Return events collection of this component; |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ToString** | string |  |

---

### Method Details

#### GetEvents

**GetEvents**(): [StiEventsCollection](../Events/StiEventsCollection.md)

Return events collection of this component;

**Returns** [StiEventsCollection](../Events/StiEventsCollection.md)


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


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Key** | object |  |
| **Value** | string |  |
