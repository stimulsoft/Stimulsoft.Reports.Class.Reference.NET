---
title: "StiMapContextPainter Class"
---

## StiMapContextPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMapContextPainter**(StiMap map, RectangleF rect, float zoom) |  |

**StiMapContextPainter**(**map**: StiMap, **rect**: RectangleF, **zoom**: float)

**Parameters**

- **map** (StiMap)  
- **rect** (RectangleF)  
- **zoom** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Map** | StiMap |  |
| **Rect** | RectangleF |  |
| **Zoom** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ChangeFontSize** `static` | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **MeasureString** | SizeF |  |
| **Render** | void |  |

---

### Method Details

#### ChangeFontSize `static`

**ChangeFontSize**(**font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **zoom**: float): [Font](../../Stimulsoft_Drawing/root/Font.md)

**Parameters**

- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **zoom** (float)  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md)


---

#### MeasureString

**MeasureString**(**text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  

**Returns** SizeF


---

#### Render

**Render**(): void

