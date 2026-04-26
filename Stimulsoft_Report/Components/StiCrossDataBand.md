---
title: "StiCrossDataBand Class"
---

## StiCrossDataBand Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiDataBand  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCrossDataBand**() | Creates a new component of the type StiCrossDataBand. |
| **StiCrossDataBand**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new component of the type StiCrossDataBand with specified location. |

**StiCrossDataBand**()

Creates a new component of the type StiCrossDataBand.

---

**StiCrossDataBand**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new component of the type StiCrossDataBand with specified location.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **First** | void | Sets the position at the beginning. |
| **Last** | void | Move on the last row. |
| **LoadFromJsonObject** | void |  |
| **Next** | void | Move on the next row. |
| **Prior** | void | Move on the previous row. |
| **RestoreState** | void | Restores the earlier saved object state. |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### First

**First**(): void

Sets the position at the beginning.


---

#### Last

**Last**(): void

Move on the last row.


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### Next

**Next**(): void

Move on the next row.


---

#### Prior

**Prior**(): void

Move on the previous row.


---

#### RestoreState

**RestoreState**(**stateName**: string): void

Restores the earlier saved object state.

**Parameters**

- **stateName** (string) — A name of the state being restored.  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

