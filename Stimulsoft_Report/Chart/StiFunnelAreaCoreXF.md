---
title: "StiFunnelAreaCoreXF Class"
---

## StiFunnelAreaCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAreaCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFunnelAreaCoreXF**(IStiArea area) |  |

**StiFunnelAreaCoreXF**(**area**: IStiArea)

**Parameters**

- **area** (IStiArea)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **PrepareInfo** | void |  |
| **Render** | StiCellGeom |  |
| **RenderSeries** | void |  |

---

### Method Details

#### PrepareInfo

**PrepareInfo**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### Render

**Render**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), **seriesCollection**: List<IStiSeries>): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **seriesCollection** (List<IStiSeries>)  

