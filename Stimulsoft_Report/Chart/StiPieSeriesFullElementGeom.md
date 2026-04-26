---
title: "StiPieSeriesFullElementGeom Class"
---

## StiPieSeriesFullElementGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeriesElementGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPieSeriesFullElementGeom**([StiAreaGeom](StiAreaGeom.md) areaGeom, double value, int index, IStiPieSeries series, RectangleF clientRectangle, [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) brush, Color borderColor) |  |

**StiPieSeriesFullElementGeom**(**areaGeom**: [StiAreaGeom](StiAreaGeom.md), **value**: double, **index**: int, **series**: IStiPieSeries, **clientRectangle**: RectangleF, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderColor**: Color)

**Parameters**

- **areaGeom** ([StiAreaGeom](StiAreaGeom.md))  
- **value** (double)  
- **index** (int)  
- **series** (IStiPieSeries)  
- **clientRectangle** (RectangleF)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderColor** (Color)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Draw** | void | Draws area geom object on spefied context. |

---

### Method Details

#### Contains

**Contains**(**x**: float, **y**: float): bool

**Parameters**

- **x** (float)  
- **y** (float)  

**Returns** bool


---

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws area geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  

