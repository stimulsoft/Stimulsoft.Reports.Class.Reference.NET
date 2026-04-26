---
title: "StiLinesGeom3D Class"
---

## StiLinesGeom3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiGeom3D](StiGeom3D.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLinesGeom3D**(List<[StiPoint3D](StiPoint3D.md)> points, Color color, float lineWidth, [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) style, [StiRender3D](StiRender3D.md) render3D) |  |
| **StiLinesGeom3D**(Color color, float lineWidth, [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) style, [StiRender3D](StiRender3D.md) render3D, StiPoint3Dpoints ) |  |

**StiLinesGeom3D**(**points**: List<[StiPoint3D](StiPoint3D.md)>, **color**: Color, **lineWidth**: float, **style**: [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md), **render3D**: [StiRender3D](StiRender3D.md))

**Parameters**

- **points** (List<[StiPoint3D](StiPoint3D.md)>)  
- **color** (Color)  
- **lineWidth** (float)  
- **style** ([StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md))  
- **render3D** ([StiRender3D](StiRender3D.md))  

---

**StiLinesGeom3D**(**color**: Color, **lineWidth**: float, **style**: [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md), **render3D**: [StiRender3D](StiRender3D.md), ****: StiPoint3Dpoints)

**Parameters**

- **color** (Color)  
- **lineWidth** (float)  
- **style** ([StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md))  
- **render3D** ([StiRender3D](StiRender3D.md))  
- **** (StiPoint3Dpoints)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **LineWidth** | float |  |
| **PenStyle** | [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) |  |
| **Points** | List<[StiPoint3D](StiPoint3D.md)> |  |

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

