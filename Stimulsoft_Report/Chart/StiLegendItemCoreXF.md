---
title: "StiLegendItemCoreXF Class"
---

## StiLegendItemCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLegendItemCoreXF**(string text, IStiSeries series, int index, int colorIndex) |  |

**StiLegendItemCoreXF**(**text**: string, **series**: IStiSeries, **index**: int, **colorIndex**: int)

**Parameters**

- **text** (string)  
- **series** (IStiSeries)  
- **index** (int)  
- **colorIndex** (int)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColorIndex** | int |  |
| **Index** | int |  |
| **Series** | IStiSeries |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetText** | string |  |
| **MeasureString** | SizeF |  |

---

### Method Details

#### GetText

**GetText**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **overrideWidth**: float): string

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **overrideWidth** (float)  

**Returns** string


---

#### MeasureString

**MeasureString**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **overrideWidth**: float): SizeF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **overrideWidth** (float)  

**Returns** SizeF

