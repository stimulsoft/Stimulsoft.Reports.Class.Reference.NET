---
title: "StiMapSvgHelper Class"
---

## StiMapSvgHelper Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawMap** `static` | void |  |
| **GetFillBrush** `static` | string |  |
| **Render** `static` | void |  |

---

### Method Details

#### DrawMap `static`

**DrawMap**(**xmlsWriter**: XmlTextWriter, **map**: StiMap, **x**: double, **y**: double, **width**: double, **height**: double, **animated**: bool, **dontConnectToData**: bool): void

**Parameters**

- **xmlsWriter** (XmlTextWriter)  
- **map** (StiMap)  
- **x** (double)  
- **y** (double)  
- **width** (double)  
- **height** (double)  
- **animated** (bool)  
- **dontConnectToData** (bool)  


---

#### GetFillBrush `static`

**GetFillBrush**(**brush**: [SolidBrush](../../Stimulsoft_Drawing/root/SolidBrush.md)): string

**Parameters**

- **brush** ([SolidBrush](../../Stimulsoft_Drawing/root/SolidBrush.md))  

**Returns** string


---

#### Render `static`

**Render**(**map**: StiMap, **xmlsWriter**: XmlTextWriter, **animated**: bool, **sScale**: double, **dontConnectToData**: bool): void

**Parameters**

- **map** (StiMap)  
- **xmlsWriter** (XmlTextWriter)  
- **animated** (bool)  
- **sScale** (double)  
- **dontConnectToData** (bool)  

