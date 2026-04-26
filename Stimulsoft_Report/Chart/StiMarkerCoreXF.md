---
title: "StiMarkerCoreXF Class"
---

## StiMarkerCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMarkerCoreXF**(IStiMarker marker) |  |

**StiMarkerCoreXF**(**marker**: IStiMarker)

**Parameters**

- **marker** (IStiMarker)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **Draw** | void |  |
| **DrawMarkers** | void |  |
| **GetMarkerRect** `static` | RectangleF |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **marker**: IStiMarker, **position**: PointF, **zoom**: float, **showShadow**: bool, **isMouseOver**: bool, **isTooltipMode**: bool, **isAnimation**: bool, **toolTip**: string, **tag**: object, **interaction**: [StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **marker** (IStiMarker)  
- **position** (PointF)  
- **zoom** (float)  
- **showShadow** (bool)  
- **isMouseOver** (bool)  
- **isTooltipMode** (bool)  
- **isAnimation** (bool)  
- **toolTip** (string)  
- **tag** (object)  
- **interaction** ([StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md))  


---

#### DrawMarkers

**DrawMarkers**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), ****: PointFpoints, **showShadow**: bool): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **** (PointFpoints)  
- **showShadow** (bool)  


---

#### GetMarkerRect `static`

**GetMarkerRect**(**position**: PointF, **markerSize**: float, **zoom**: float): RectangleF

**Parameters**

- **position** (PointF)  
- **markerSize** (float)  
- **zoom** (float)  

**Returns** RectangleF

