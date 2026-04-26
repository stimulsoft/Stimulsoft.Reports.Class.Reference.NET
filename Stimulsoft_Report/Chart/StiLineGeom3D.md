---
title: "StiLineGeom3D Class"
---

## StiLineGeom3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiGeom3D](StiGeom3D.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLineGeom3D**([StiPoint3D](StiPoint3D.md) startPoint, [StiPoint3D](StiPoint3D.md) endPoint, Color color, float lineWidth, [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) style, [StiRender3D](StiRender3D.md) render3D) |  |

**StiLineGeom3D**(**startPoint**: [StiPoint3D](StiPoint3D.md), **endPoint**: [StiPoint3D](StiPoint3D.md), **color**: Color, **lineWidth**: float, **style**: [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md), **render3D**: [StiRender3D](StiRender3D.md))

**Parameters**

- **startPoint** ([StiPoint3D](StiPoint3D.md))  
- **endPoint** ([StiPoint3D](StiPoint3D.md))  
- **color** (Color)  
- **lineWidth** (float)  
- **style** ([StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md))  
- **render3D** ([StiRender3D](StiRender3D.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **LineWidth** | float |  |
| **PenStyle** | [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawElements** | void |  |

---

### Method Details

#### DrawElements

**DrawElements**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  

