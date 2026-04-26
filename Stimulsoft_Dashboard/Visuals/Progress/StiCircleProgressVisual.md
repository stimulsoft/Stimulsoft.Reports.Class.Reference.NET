---
title: "StiCircleProgressVisual Class"
---

## StiCircleProgressVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Progress`

This is a base class to work with the circle-progress element visualization.

### Inheritance

Inherits from: [StiPieProgressVisual](StiPieProgressVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCircleProgressVisual**(StiProgressElement element, List<[StiProgressIteration](StiProgressIteration.md)> iterations) |  |

**StiCircleProgressVisual**(**element**: StiProgressElement, **iterations**: List<[StiProgressIteration](StiProgressIteration.md)>)

**Parameters**

- **element** (StiProgressElement)  
- **iterations** (List<[StiProgressIteration](StiProgressIteration.md)>)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws a visual object on specified context and at specified location. |
| **GetPoint** | PointF |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **rectMain**: RectangleF): void

Draws a visual object on specified context and at specified location.

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **rectMain** (RectangleF)  


---

#### GetPoint

**GetPoint**(**centerPie**: PointF, **radius**: float, **angle**: float): PointF

**Parameters**

- **centerPie** (PointF)  
- **radius** (float)  
- **angle** (float)  

**Returns** PointF

