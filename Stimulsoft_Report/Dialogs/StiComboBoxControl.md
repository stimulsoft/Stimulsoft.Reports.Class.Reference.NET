---
title: "StiComboBoxControl Class"
---

## StiComboBoxControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiComboBoxControl**() | Creates a new StiComboBoxControl. |
| **StiComboBoxControl**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiComboBoxControl. |

**StiComboBoxControl**()

Creates a new StiComboBoxControl.

---

**StiComboBoxControl**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiComboBoxControl.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the control.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | ComboBox |  |
| **ItemsBinding** | string |  |
| **SelectedItemBinding** | string |  |
| **SelectedValueBinding** | string |  |
| **TextBinding** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Gets default event for this report control. |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Return events collection of this component; |
| **InvokeSelectedIndexChanged** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetDefaultEvent

**GetDefaultEvent**(): StiEvent

Gets default event for this report control.

**Returns** StiEvent — Default event.


---

#### GetEvents

**GetEvents**(): [StiEventsCollection](../Events/StiEventsCollection.md)

Return events collection of this component;

**Returns** [StiEventsCollection](../Events/StiEventsCollection.md)


---

#### InvokeSelectedIndexChanged

**InvokeSelectedIndexChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


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

