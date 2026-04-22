---
title: "StiGeom3D Class"
---

## StiGeom3D Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiGeom3D
```

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiGeom3D([StiRender3D](StiRender3D.md) render)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColorsFaces** | Color[] |  |
| **DrawEdges** | bool |  |
| **DrawVertexes** | bool |  |
| **Faces** | List<double[]> |  |
| **Render** | [StiRender3D](StiRender3D.md) |  |
| **RenderPoints** | List<PointF> |  |
| **Type** | [StiGeomType](../Stimulsoft/Base/Context/StiGeomType.md) |  |
| **Vertexes** | [StiMatrix](../Export/StiMatrix.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **DrawBorder** | void |  |
| **DrawElements** | void |  |
| **DrawFaceBorder** | void |  |
| **DrawFaces** | void |  |
| **GetBorderColor** | Color? |  |
| **GetFacePolygonPoints** | List<PointF> |  |
| **GetPoint** *(+1 overloads)* | PointF |  |
| **GlobalTransform** | void |  |
| **MeasureCientRect** | RectangleF |  |
| **RotateX** | void |  |
| **RotateY** | void |  |
| **RotateZ** | void |  |
| **Scale** | void |  |
| **ScreenProjection** | [StiMatrix](../Export/StiMatrix.md) |  |
| **Translate** | void |  |
