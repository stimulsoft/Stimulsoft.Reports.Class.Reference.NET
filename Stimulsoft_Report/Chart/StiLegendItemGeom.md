---
title: "StiLegendItemGeom Class"
---

## StiLegendItemGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLegendItemGeom**(IStiLegend legend, [StiLegendItemCoreXF](StiLegendItemCoreXF.md) item, RectangleF clientRectangle, int colorIndex, int legendItemsCount, int legendItemIndex) |  |

**StiLegendItemGeom**(**legend**: IStiLegend, **item**: [StiLegendItemCoreXF](StiLegendItemCoreXF.md), **clientRectangle**: RectangleF, **colorIndex**: int, **legendItemsCount**: int, **legendItemIndex**: int)

**Parameters**

- **legend** (IStiLegend)  
- **item** ([StiLegendItemCoreXF](StiLegendItemCoreXF.md))  
- **clientRectangle** (RectangleF)  
- **colorIndex** (int)  
- **legendItemsCount** (int)  
- **legendItemIndex** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws area geom object on spefied context. |
| **InvokeClick** | void |  |
| **InvokeMouseEnter** | void |  |
| **InvokeMouseLeave** | void |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws area geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### InvokeClick

**InvokeClick**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  


---

#### InvokeMouseEnter

**InvokeMouseEnter**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  


---

#### InvokeMouseLeave

**InvokeMouseLeave**(**options**: [StiInteractionOptions](StiInteractionOptions.md)): void

**Parameters**

- **options** ([StiInteractionOptions](StiInteractionOptions.md))  

