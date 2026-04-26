---
title: "StiCurveGeom Class"
---

## StiCurveGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCurveGeom**([StiPenGeom](StiPenGeom.md) pen, PointFpoints , float tension) |  |

**StiCurveGeom**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints, **tension**: float)

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  
- **tension** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pen** | [StiPenGeom](StiPenGeom.md) |  |
| **Points** | PointF[] |  |
| **Tension** | float |  |

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

