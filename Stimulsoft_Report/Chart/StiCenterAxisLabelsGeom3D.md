---
title: "StiCenterAxisLabelsGeom3D Class"
---

## StiCenterAxisLabelsGeom3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiSeriesLabelsGeom3D](StiSeriesLabelsGeom3D.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Font** | [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md) |  |
| **LabelBorderColor** | Color |  |
| **LabelColor** | Color |  |
| **SeriesBorderColor** | Color |  |
| **SeriesBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **SeriesLabelsBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawElements** | void |  |
| **DrawLabelArea** | void |  |
| **DrawLabelText** | void |  |
| **GetLabelRect** | SizeF |  |

---

### Method Details

#### DrawElements

**DrawElements**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  


---

#### DrawLabelArea

**DrawLabelArea**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  


---

#### DrawLabelText

**DrawLabelText**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  


---

#### GetLabelRect

**GetLabelRect**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): SizeF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  

**Returns** SizeF

