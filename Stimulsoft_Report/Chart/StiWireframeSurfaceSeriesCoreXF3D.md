---
title: "StiWireframeSurfaceSeriesCoreXF3D Class"
---

## StiWireframeSurfaceSeriesCoreXF3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiAreaSeriesCoreXF3D](StiAreaSeriesCoreXF3D.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWireframeSurfaceSeriesCoreXF3D**(IStiSeries series) |  |

**StiWireframeSurfaceSeriesCoreXF3D**(**series**: IStiSeries)

**Parameters**

- **series** (IStiSeries)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **AreLinesCoincident** `static` | bool | Determines if two 3D lines are coincident (lie on the same infinite line) |
| **CreateClosedLineFromPoints** `static` | List<[StiPoint3D](StiPoint3D.md)> | Creates a closed line from a set of points without self-intersections |
| **CreateClosedLineNearestNeighbor** `static` | List<[StiPoint3D](StiPoint3D.md)> |  |
| **FindLineIntersectionWithHorizontalPlane** `static` | StiPoint3D? | Finds the intersection point of a segment with a horizontal plane (parallel to XZ) |
| **GetSeriesBorderColor** | object |  |
| **RenderSeries3D** | void |  |
| **SplitTriangleByPlanes** `static` | List<List<[StiPoint3D](StiPoint3D.md)>> |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle, **color**: Color): void

**Parameters**

- **style** (IStiChartStyle)  
- **color** (Color)  


---

#### AreLinesCoincident `static`

**AreLinesCoincident**(**line1Point1**: [StiPoint3D](StiPoint3D.md), **line1Point2**: [StiPoint3D](StiPoint3D.md), **line2Point1**: [StiPoint3D](StiPoint3D.md), **line2Point2**: [StiPoint3D](StiPoint3D.md), **tolerance**: double): bool

Determines if two 3D lines are coincident (lie on the same infinite line)

**Parameters**

- **line1Point1** ([StiPoint3D](StiPoint3D.md))  
- **line1Point2** ([StiPoint3D](StiPoint3D.md))  
- **line2Point1** ([StiPoint3D](StiPoint3D.md))  
- **line2Point2** ([StiPoint3D](StiPoint3D.md))  
- **tolerance** (double)  

**Returns** bool


---

#### CreateClosedLineFromPoints `static`

**CreateClosedLineFromPoints**(**points**: List<[StiPoint3D](StiPoint3D.md)>): List<[StiPoint3D](StiPoint3D.md)>

Creates a closed line from a set of points without self-intersections

**Parameters**

- **points** (List<[StiPoint3D](StiPoint3D.md)>) — List of points to connect  

**Returns** List<[StiPoint3D](StiPoint3D.md)> — Ordered list of points with closing point


---

#### CreateClosedLineNearestNeighbor `static`

**CreateClosedLineNearestNeighbor**(**points**: List<[StiPoint3D](StiPoint3D.md)>): List<[StiPoint3D](StiPoint3D.md)>

**Parameters**

- **points** (List<[StiPoint3D](StiPoint3D.md)>)  

**Returns** List<[StiPoint3D](StiPoint3D.md)>


---

#### FindLineIntersectionWithHorizontalPlane `static`

**FindLineIntersectionWithHorizontalPlane**(**pointLine1**: [StiPoint3D](StiPoint3D.md), **pointLine2**: [StiPoint3D](StiPoint3D.md), **planeY**: double): StiPoint3D?

Finds the intersection point of a segment with a horizontal plane (parallel to XZ)

**Parameters**

- **pointLine1** ([StiPoint3D](StiPoint3D.md))  
- **pointLine2** ([StiPoint3D](StiPoint3D.md))  
- **planeY** (double)  

**Returns** StiPoint3D?


---

#### GetSeriesBorderColor

**GetSeriesBorderColor**(**colorIndex**: int, **colorCount**: int): object

**Parameters**

- **colorIndex** (int)  
- **colorCount** (int)  

**Returns** object


---

#### RenderSeries3D

**RenderSeries3D**(**render3D**: [StiRender3D](StiRender3D.md), **context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: [StiRectangle3D](StiRectangle3D.md), **geom**: [StiAreaGeom](StiAreaGeom.md), **seriesIndex**: int, ****: IStiSeriesseriesArray): void

**Parameters**

- **render3D** ([StiRender3D](StiRender3D.md))  
- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** ([StiRectangle3D](StiRectangle3D.md))  
- **geom** ([StiAreaGeom](StiAreaGeom.md))  
- **seriesIndex** (int)  
- **** (IStiSeriesseriesArray)  


---

#### SplitTriangleByPlanes `static`

**SplitTriangleByPlanes**(**trianglePoints**: List<[StiPoint3D](StiPoint3D.md)>, ****: floatstripPositions): List<List<[StiPoint3D](StiPoint3D.md)>>

**Parameters**

- **trianglePoints** (List<[StiPoint3D](StiPoint3D.md)>)  
- **** (floatstripPositions)  

**Returns** List<List<[StiPoint3D](StiPoint3D.md)>>

