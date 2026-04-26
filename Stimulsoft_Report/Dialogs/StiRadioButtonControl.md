---
title: "StiRadioButtonControl Class"
---

## StiRadioButtonControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRadioButtonControl**() | Creates a new StiRadioButtonControl. |
| **StiRadioButtonControl**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiRadioButtonControl. |

**StiRadioButtonControl**()

Creates a new StiRadioButtonControl.

---

**StiRadioButtonControl**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiRadioButtonControl.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the control.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Gets default event for this report control. |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Return events collection of this component; |
| **InvokeCheckedChanged** | void |  |
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

#### InvokeCheckedChanged

**InvokeCheckedChanged**(**e**: EventArgs): void

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

