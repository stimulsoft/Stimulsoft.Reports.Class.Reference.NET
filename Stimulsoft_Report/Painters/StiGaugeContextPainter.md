---
title: "StiGaugeContextPainter Class"
---

## StiGaugeContextPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGaugeContextPainter**(StiGauge gauge, RectangleF rect, float zoom) |  |

**StiGaugeContextPainter**(**gauge**: StiGauge, **rect**: RectangleF, **zoom**: float)

**Parameters**

- **gauge** (StiGauge)  
- **rect** (RectangleF)  
- **zoom** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animations** | List<[StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)> |  |
| **Gauge** | StiGauge |  |
| **Geoms** | List<[StiGaugeGeom](../Gauge/GaugeGeoms/StiGaugeGeom.md)> |  |
| **Rect** | RectangleF |  |
| **ScaleSystem** | double |  |
| **Zoom** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddEllipseGaugeGeom** | void |  |
| **AddGraphicsPathGaugeGeom** | void |  |
| **AddPieGaugeGeom** | void |  |
| **AddPopTranformGaugeGeom** | void |  |
| **AddPushMatrixGaugeGeom** | void |  |
| **AddRectangleGaugeGeom** | void |  |
| **AddRoundedRectangleGaugeGeom** | void |  |
| **AddTextGaugeGeom** | void |  |
| **ChangeFontSize** `static` | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **MeasureString** | SizeF |  |
| **Render** | void |  |

---

### Method Details

#### AddEllipseGaugeGeom

**AddEllipseGaugeGeom**(**rect**: RectangleF, **background**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderWidth**: float): void

**Parameters**

- **rect** (RectangleF)  
- **background** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderWidth** (float)  


---

#### AddGraphicsPathGaugeGeom

**AddGraphicsPathGaugeGeom**(**geom**: [StiGraphicsPathGaugeGeom](../Gauge/GaugeGeoms/StiGraphicsPathGaugeGeom.md)): void

**Parameters**

- **geom** ([StiGraphicsPathGaugeGeom](../Gauge/GaugeGeoms/StiGraphicsPathGaugeGeom.md))  


---

#### AddPieGaugeGeom

**AddPieGaugeGeom**(**rect**: RectangleF, **background**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderWidth**: float, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **rect** (RectangleF)  
- **background** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderWidth** (float)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### AddPopTranformGaugeGeom

**AddPopTranformGaugeGeom**(): void


---

#### AddPushMatrixGaugeGeom

**AddPushMatrixGaugeGeom**(**angle**: float, **centerPoint**: PointF): void

**Parameters**

- **angle** (float)  
- **centerPoint** (PointF)  


---

#### AddRectangleGaugeGeom

**AddRectangleGaugeGeom**(**rect**: RectangleF, **background**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderWidth**: float): void

**Parameters**

- **rect** (RectangleF)  
- **background** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderWidth** (float)  


---

#### AddRoundedRectangleGaugeGeom

**AddRoundedRectangleGaugeGeom**(**rect**: RectangleF, **background**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **borderWidth**: float, **leftTop**: int, **rightTop**: int, **rightBottom**: int, **leftBottom**: int): void

**Parameters**

- **rect** (RectangleF)  
- **background** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderWidth** (float)  
- **leftTop** (int)  
- **rightTop** (int)  
- **rightBottom** (int)  
- **leftBottom** (int)  


---

#### AddTextGaugeGeom

**AddTextGaugeGeom**(**text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **foreground**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

**Parameters**

- **text** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **foreground** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md))  


---

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

