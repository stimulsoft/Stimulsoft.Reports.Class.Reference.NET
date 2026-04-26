---
title: "StiStaticBand Class"
---

## StiStaticBand Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiBand  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiStaticBand**() | Creates a new static band. |
| **StiStaticBand**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new static band. |

**StiStaticBand**()

Creates a new static band.

---

**StiStaticBand**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new static band.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Break** | bool | Divides content of components in two parts. Returns result of dividing. If true, then component is successful divided. |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Break

**Break**(**dividedComponent**: StiComponent, **devideFactor**: double, **divLine**: double, **haveBreaked**: bool): bool

Divides content of components in two parts. Returns result of dividing. If true, then component is successful divided.

**Parameters**

- **dividedComponent** (StiComponent) — Component for store part of content.  
- **devideFactor** (double)  
- **divLine** (double)  
- **haveBreaked** (bool)  

**Returns** bool — If true, then component is successful divided.


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

