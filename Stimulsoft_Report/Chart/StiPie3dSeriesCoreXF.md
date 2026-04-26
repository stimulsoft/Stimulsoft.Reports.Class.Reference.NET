---
title: "StiPie3dSeriesCoreXF Class"
---

## StiPie3dSeriesCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiPieSeriesCoreXF](StiPieSeriesCoreXF.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPie3dSeriesCoreXF**(IStiSeries series) |  |

**StiPie3dSeriesCoreXF**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetSliceDisplacement** | SizeF |  |
| **InitializeEmptyPieSlices** | void |  |
| **InitializePieSlices** | void |  |
| **RenderSeries** | void |  |

---

### Method Details

#### GetSliceDisplacement

**GetSliceDisplacement**(**angle**: float, **xDisplacement**: float, **yDisplacement**: float): SizeF

**Parameters**

- **angle** (float)  
- **xDisplacement** (float)  
- **yDisplacement** (float)  

**Returns** SizeF


---

#### InitializeEmptyPieSlices

**InitializeEmptyPieSlices**(**area**: IStiArea, **mainRect**: RectangleF, ****: IStiSeriesseriesArray, **zoom**: float): void

**Parameters**

- **area** (IStiArea)  
- **mainRect** (RectangleF)  
- **** (IStiSeriesseriesArray)  
- **zoom** (float)  


---

#### InitializePieSlices

**InitializePieSlices**(**area**: IStiArea, **mainRect**: RectangleF, ****: IStiSeriesseriesArray, **zoom**: float): void

**Parameters**

- **area** (IStiArea)  
- **mainRect** (RectangleF)  
- **** (IStiSeriesseriesArray)  
- **zoom** (float)  


---

#### RenderSeries

**RenderSeries**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **geom**: [StiAreaGeom](StiAreaGeom.md), ****: IStiSeriesseriesArray): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **** (IStiSeriesseriesArray)  

