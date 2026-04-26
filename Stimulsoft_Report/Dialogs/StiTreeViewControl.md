---
title: "StiTreeViewControl Class"
---

## StiTreeViewControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTreeViewControl**() | Creates a new StiTreeViewControl. |
| **StiTreeViewControl**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiTreeViewControl. |

**StiTreeViewControl**()

Creates a new StiTreeViewControl.

---

**StiTreeViewControl**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiTreeViewControl.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the control.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Gets default event for this report control. |
| **InvokeAfterSelect** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetDefaultEvent

**GetDefaultEvent**(): StiEvent

Gets default event for this report control.

**Returns** StiEvent — Default event.


---

#### InvokeAfterSelect

**InvokeAfterSelect**(**e**: TreeViewEventArgs): void

**Parameters**

- **e** (TreeViewEventArgs)  


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

