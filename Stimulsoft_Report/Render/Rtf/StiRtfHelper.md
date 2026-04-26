---
title: "StiRtfHelper Class"
---

## StiRtfHelper Class

**Namespace:** `Stimulsoft.Report.Render.Rtf`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Break** `static` | List<string> |  |
| **ConvertToHtml** `static` | string |  |
| **Draw** `static` | void |  |
| **Measure** `static` | SizeF |  |
| **Render** `static` | List<[StiRtfGeom](Geoms/StiRtfGeom.md)> | Render rtf to list of geoms |
| **Zoom** `static` | List<[StiRtfGeom](Geoms/StiRtfGeom.md)> |  |

---

### Method Details

#### Break `static`

**Break**(**rtf**: string, **rect**: RectangleF, **wordwrap**: bool): List<string>

**Parameters**

- **rtf** (string)  
- **rect** (RectangleF)  
- **wordwrap** (bool)  

**Returns** List<string>


---

#### ConvertToHtml `static`

**ConvertToHtml**(**rtfString**: string, **wordwrap**: bool): string

**Parameters**

- **rtfString** (string)  
- **wordwrap** (bool)  

**Returns** string


---

#### Draw `static`

**Draw**(**rtf**: string, **rect**: RectangleF, **g**: [Graphics](../../../Stimulsoft_Drawing/root/Graphics.md), **zoom**: float, **wordwrap**: bool): void

**Parameters**

- **rtf** (string)  
- **rect** (RectangleF)  
- **g** ([Graphics](../../../Stimulsoft_Drawing/root/Graphics.md))  
- **zoom** (float)  
- **wordwrap** (bool)  


---

#### Measure `static`

**Measure**(**rtf**: string, **maxWidth**: double, **zoom**: float, **wordwrap**: bool): SizeF

**Parameters**

- **rtf** (string)  
- **maxWidth** (double)  
- **zoom** (float)  
- **wordwrap** (bool)  

**Returns** SizeF


---

#### Render `static`

**Render**(**rtf**: string, **rect**: RectangleF, **wordwrap**: bool): List<[StiRtfGeom](Geoms/StiRtfGeom.md)>

Render rtf to list of geoms

**Parameters**

- **rtf** (string) — rtf-string  
- **rect** (RectangleF) — rectangle in Hundredths of Inch  
- **wordwrap** (bool)  

**Returns** List<[StiRtfGeom](Geoms/StiRtfGeom.md)>


---

#### Zoom `static`

**Zoom**(**geoms**: List<[StiRtfGeom](Geoms/StiRtfGeom.md)>, **zoom**: float): List<[StiRtfGeom](Geoms/StiRtfGeom.md)>

**Parameters**

- **geoms** (List<[StiRtfGeom](Geoms/StiRtfGeom.md)>)  
- **zoom** (float)  

**Returns** List<[StiRtfGeom](Geoms/StiRtfGeom.md)>

