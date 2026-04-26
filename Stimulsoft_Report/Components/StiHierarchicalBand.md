---
title: "StiHierarchicalBand Class"
---

## StiHierarchicalBand Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiDataBand  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHierarchicalBand**() | Creates an object of the type StiHierarchicalBand. |
| **StiHierarchicalBand**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates an object of the type StiHierarchicalBand. |

**StiHierarchicalBand**()

Creates an object of the type StiHierarchicalBand.

---

**StiHierarchicalBand**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates an object of the type StiHierarchicalBand.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle decribes size and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Footers** | string |  |
| **Headers** | string |  |
| **Indent** | double |  |
| **KeyDataColumn** | string |  |
| **MasterKeyDataColumn** | string |  |
| **ParentValue** | string |  |

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

