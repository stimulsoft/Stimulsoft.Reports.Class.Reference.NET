---
title: "StiIndicatorVisual Class"
---

## StiIndicatorVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Indicator`

This is a class to work with the indicator element visualization.

### Inheritance

Inherits from: [StiVisual](../StiVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIndicatorVisual**(StiIndicatorElement element, List<[StiIndicatorIteration](StiIndicatorIteration.md)> iterations) |  |

**StiIndicatorVisual**(**element**: StiIndicatorElement, **iterations**: List<[StiIndicatorIteration](StiIndicatorIteration.md)>)

**Parameters**

- **element** (StiIndicatorElement)  
- **iterations** (List<[StiIndicatorIteration](StiIndicatorIteration.md)>)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Element** | StiIndicatorElement |  |
| **Iterations** | List<[StiIndicatorIteration](StiIndicatorIteration.md)> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws a visual object on specified context and at specified location. |
| **GetElementSide** | float |  |
| **GetTargetValues** | List<decimal?> |  |
| **MeasureFontSize** | void |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): void

Draws a visual object on specified context and at specified location.

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  


---

#### GetElementSide

**GetElementSide**(**isVerticalOrientation**: bool, **size**: SizeF): float

**Parameters**

- **isVerticalOrientation** (bool)  
- **size** (SizeF)  

**Returns** float


---

#### GetTargetValues

**GetTargetValues**(): List<decimal?>

**Returns** List<decimal?>


---

#### MeasureFontSize

**MeasureFontSize**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **text**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md), **fontSize**: float?): void

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **text** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  
- **fontSize** (float?)  

