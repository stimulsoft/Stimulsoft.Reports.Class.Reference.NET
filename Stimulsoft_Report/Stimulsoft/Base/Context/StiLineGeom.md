---
title: "StiLineGeom Class"
---

## StiLineGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLineGeom**([StiPenGeom](StiPenGeom.md) pen, float x1, float y1, float x2, float y2) |  |

**StiLineGeom**(**pen**: [StiPenGeom](StiPenGeom.md), **x1**: float, **y1**: float, **x2**: float, **y2**: float)

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **x1** (float)  
- **y1** (float)  
- **x2** (float)  
- **y2** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **X1** | float |  |
| **X2** | float |  |
| **Y1** | float |  |
| **Y2** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

