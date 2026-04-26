---
title: "StiCachedShadowGeom Class"
---

## StiCachedShadowGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCachedShadowGeom**(RectangleF rect, [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) sides, bool isPrinting) |  |
| **StiCachedShadowGeom**(RectangleF rect, [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) sides, bool isPrinting, RectangleF clipRect) |  |
| **StiCachedShadowGeom**(RectangleF rect, [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) sides, bool isPrinting, RectangleF clipRect, StiCornerRadius cornerRadius) |  |

**StiCachedShadowGeom**(**rect**: RectangleF, **sides**: [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md), **isPrinting**: bool)

**Parameters**

- **rect** (RectangleF)  
- **sides** ([StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md))  
- **isPrinting** (bool)  

---

**StiCachedShadowGeom**(**rect**: RectangleF, **sides**: [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md), **isPrinting**: bool, **clipRect**: RectangleF)

**Parameters**

- **rect** (RectangleF)  
- **sides** ([StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md))  
- **isPrinting** (bool)  
- **clipRect** (RectangleF)  

---

**StiCachedShadowGeom**(**rect**: RectangleF, **sides**: [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md), **isPrinting**: bool, **clipRect**: RectangleF, **cornerRadius**: StiCornerRadius)

**Parameters**

- **rect** (RectangleF)  
- **sides** ([StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md))  
- **isPrinting** (bool)  
- **clipRect** (RectangleF)  
- **cornerRadius** (StiCornerRadius)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClipRect** | RectangleF |  |
| **CornerRadius** | StiCornerRadius |  |
| **IsPrinting** | bool |  |
| **Rect** | RectangleF |  |
| **Sides** | [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md) |  |

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

