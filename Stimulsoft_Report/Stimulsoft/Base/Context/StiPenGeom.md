---
title: "StiPenGeom Class"
---

## StiPenGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPenGeom**(Color brush) |  |
| **StiPenGeom**([LinearGradientBrush](../../../../Stimulsoft_Drawing/Drawing2D/LinearGradientBrush.md) brush) |  |
| **StiPenGeom**(Color brush, float thickness) |  |

**StiPenGeom**(**brush**: Color)

**Parameters**

- **brush** (Color)  

---

**StiPenGeom**(**brush**: [LinearGradientBrush](../../../../Stimulsoft_Drawing/Drawing2D/LinearGradientBrush.md))

**Parameters**

- **brush** ([LinearGradientBrush](../../../../Stimulsoft_Drawing/Drawing2D/LinearGradientBrush.md))  

---

**StiPenGeom**(**brush**: Color, **thickness**: float)

**Parameters**

- **brush** (Color)  
- **thickness** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiPenAlignment](StiPenAlignment.md) |  |
| **Brush** | Color |  |
| **Brush2** | [LinearGradientBrush](../../../../Stimulsoft_Drawing/Drawing2D/LinearGradientBrush.md) |  |
| **EndCap** | [StiPenLineCap](../../../../Stimulsoft_Base/Context/StiPenLineCap.md) |  |
| **PenStyle** | [StiPenStyle](../../../../Stimulsoft_Base/Drawing/StiPenStyle.md) |  |
| **StartCap** | [StiPenLineCap](../../../../Stimulsoft_Base/Context/StiPenLineCap.md) |  |
| **Thickness** | float |  |

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

