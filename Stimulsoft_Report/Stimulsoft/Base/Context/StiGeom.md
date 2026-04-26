---
title: "StiGeom Class"
---

## StiGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Implements: [IStiJsonReportObject](../../../../Stimulsoft_Base/root/IStiJsonReportObject.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | [StiGeomType](StiGeomType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveBrushToJsonObject** | string |  |
| **SaveColorToJsonObject** | string |  |
| **SaveGeomListToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)[] |  |
| **SavePointFArrayToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)[] |  |
| **SavePointFToJsonObject** `static` | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SaveRectToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SaveRectangleDToJsonObject** `static` | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SaveRectangleFToJsonObject** `static` | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SaveRectangleToJsonObject** `static` | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveBrushToJsonObject

**SaveBrushToJsonObject**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): string

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** string


---

#### SaveColorToJsonObject

**SaveColorToJsonObject**(**color**: Color, **mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): string

**Parameters**

- **color** (Color)  
- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** string


---

#### SaveGeomListToJsonObject

**SaveGeomListToJsonObject**(**geoms**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)[]

**Parameters**

- **geoms** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)[]


---

#### SavePointFArrayToJsonObject

**SavePointFArrayToJsonObject**(****: PointFpoints): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)[]

**Parameters**

- **** (PointFpoints)  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)[]


---

#### SavePointFToJsonObject `static`

**SavePointFToJsonObject**(**pos**: PointF): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **pos** (PointF)  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### SaveRectToJsonObject

**SaveRectToJsonObject**(**rect**: object): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **rect** (object)  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### SaveRectangleDToJsonObject `static`

**SaveRectangleDToJsonObject**(**rect**: [RectangleD](../../../../Stimulsoft_Base/Drawing/RectangleD.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **rect** ([RectangleD](../../../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### SaveRectangleFToJsonObject `static`

**SaveRectangleFToJsonObject**(**rect**: RectangleF): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **rect** (RectangleF)  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### SaveRectangleToJsonObject `static`

**SaveRectangleToJsonObject**(**rect**: Rectangle): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **rect** (Rectangle)  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

