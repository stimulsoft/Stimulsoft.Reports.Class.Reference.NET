---
title: "StiLinesGeom Class"
---

## StiLinesGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLinesGeom**([StiPenGeom](StiPenGeom.md) pen, PointFpoints ) |  |

**StiLinesGeom**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints)

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Points** | PointF[] |  |

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

