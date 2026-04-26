---
title: "StiTreemapAreaCoreXF Class"
---

## StiTreemapAreaCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAreaCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTreemapAreaCoreXF**(IStiArea area) |  |

**StiTreemapAreaCoreXF**(**area**: IStiArea)

**Parameters**

- **area** (IStiArea)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **NormalizeDataForArea** | List<double> |  |
| **PrepareInfo** | void |  |
| **Render** | StiCellGeom |  |
| **Squarify** | List<RectangleF> |  |

---

### Method Details

#### NormalizeDataForArea

**NormalizeDataForArea**(**data**: List<double>, **area**: float): List<double>

**Parameters**

- **data** (List<double>)  
- **area** (float)  

**Returns** List<double>


---

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

#### Squarify

**Squarify**(**data**: List<double>, **currentrow**: List<double?>, **container**: RectangleF, **stack**: List<RectangleF>): List<RectangleF>

**Parameters**

- **data** (List<double>)  
- **currentrow** (List<double?>)  
- **container** (RectangleF)  
- **stack** (List<RectangleF>)  

**Returns** List<RectangleF>

