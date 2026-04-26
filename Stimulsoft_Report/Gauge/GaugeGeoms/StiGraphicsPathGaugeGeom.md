---
title: "StiGraphicsPathGaugeGeom Class"
---

## StiGraphicsPathGaugeGeom Class

**Namespace:** `Stimulsoft.Report.Gauge.GaugeGeoms`

### Inheritance

Inherits from: [StiGaugeGeom](StiGaugeGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGraphicsPathGaugeGeom**(RectangleF rect, PointF startPoint, [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) background, [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) borderBrush, float borderWidth) |  |

**StiGraphicsPathGaugeGeom**(**rect**: RectangleF, **startPoint**: PointF, **background**: [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderBrush**: [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderWidth**: float)

**Parameters**

- **rect** (RectangleF)  
- **startPoint** (PointF)  
- **background** ([StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderBrush** ([StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderWidth** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Background** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderBrush** | [StiBrush](../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BorderWidth** | float |  |
| **Geoms** | List<[StiGaugeGeom](StiGaugeGeom.md)> |  |
| **IsNeedle** | bool |  |
| **Rect** | RectangleF |  |
| **StartPoint** | PointF |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddGraphicsPathArcGaugeGeom** | void |  |
| **AddGraphicsPathCloseFigureGaugeGeom** | void |  |
| **AddGraphicsPathLineGaugeGeom** | void |  |
| **AddGraphicsPathLinesGaugeGeom** | void |  |

---

### Method Details

#### AddGraphicsPathArcGaugeGeom

**AddGraphicsPathArcGaugeGeom**(**x**: float, **y**: float, **width**: float, **height**: float, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### AddGraphicsPathCloseFigureGaugeGeom

**AddGraphicsPathCloseFigureGaugeGeom**(): void


---

#### AddGraphicsPathLineGaugeGeom

**AddGraphicsPathLineGaugeGeom**(**p1**: PointF, **p2**: PointF): void

**Parameters**

- **p1** (PointF)  
- **p2** (PointF)  


---

#### AddGraphicsPathLinesGaugeGeom

**AddGraphicsPathLinesGaugeGeom**(****: PointFpoints): void

**Parameters**

- **** (PointFpoints)  

