---
title: "StiGeom3D Class"
---

## StiGeom3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGeom3D**([StiRender3D](StiRender3D.md) render) |  |

**StiGeom3D**(**render**: [StiRender3D](StiRender3D.md))

**Parameters**

- **render** ([StiRender3D](StiRender3D.md))  


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

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### DrawBorder

**DrawBorder**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  


---

#### DrawElements

**DrawElements**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  


---

#### DrawFaceBorder

**DrawFaceBorder**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md), ****: doubleface, **color**: Color): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  
- **** (doubleface)  
- **color** (Color)  


---

#### DrawFaces

**DrawFaces**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  


---

#### GetBorderColor

**GetBorderColor**(): Color?

**Returns** Color?


---

#### GetFacePolygonPoints

**GetFacePolygonPoints**(****: doubleface, **vertices**: [StiMatrix](../Export/StiMatrix.md)): List<PointF>

**Parameters**

- **** (doubleface)  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  

**Returns** List<PointF>


---

#### GetPoint

**GetPoint**(**vertices**: [StiMatrix](../Export/StiMatrix.md), **vertIndex**: int): PointF

**Parameters**

- **vertices** ([StiMatrix](../Export/StiMatrix.md))  
- **vertIndex** (int)  

**Returns** PointF

---

**GetPoint**(**x**: float, **y**: float): PointF

**Parameters**

- **x** (float)  
- **y** (float)  

**Returns** PointF


---

#### GlobalTransform

**GlobalTransform**(): void


---

#### MeasureCientRect

**MeasureCientRect**(): RectangleF

**Returns** RectangleF


---

#### RotateX

**RotateX**(**angle**: double): void

**Parameters**

- **angle** (double)  


---

#### RotateY

**RotateY**(**angle**: double): void

**Parameters**

- **angle** (double)  


---

#### RotateZ

**RotateZ**(**angle**: double): void

**Parameters**

- **angle** (double)  


---

#### Scale

**Scale**(**scaleTo**: double): void

**Parameters**

- **scaleTo** (double)  


---

#### ScreenProjection

**ScreenProjection**(): [StiMatrix](../Export/StiMatrix.md)

**Returns** [StiMatrix](../Export/StiMatrix.md)


---

#### Translate

**Translate**(**vector**: [StiVector3](StiVector3.md)): void

**Parameters**

- **vector** ([StiVector3](StiVector3.md))  

