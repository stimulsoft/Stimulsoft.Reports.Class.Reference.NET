---
title: "StiWireframeSurfaceSeriesCoreXF3D Class"
---

## StiWireframeSurfaceSeriesCoreXF3D Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiWireframeSurfaceSeriesCoreXF3D
```

### Inheritance

Inherits from: [StiAreaSeriesCoreXF3D](StiAreaSeriesCoreXF3D.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiWireframeSurfaceSeriesCoreXF3D(IStiSeries series)` |  |

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
