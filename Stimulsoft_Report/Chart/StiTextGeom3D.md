---
title: "StiTextGeom3D Class"
---

## StiTextGeom3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: [StiGeom3D](StiGeom3D.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTextGeom3D**(string text, [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md) font, Color color, [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md) mode, float angle, [StiPoint3D](StiPoint3D.md) point3D, [StiRender3D](StiRender3D.md) render3D) |  |

**StiTextGeom3D**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **color**: Color, **mode**: [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float, **point3D**: [StiPoint3D](StiPoint3D.md), **render3D**: [StiRender3D](StiRender3D.md))

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **color** (Color)  
- **mode** ([StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  
- **point3D** ([StiPoint3D](StiPoint3D.md))  
- **render3D** ([StiRender3D](StiRender3D.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Angle** | float |  |
| **Color** | Color |  |
| **Font** | [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md) |  |
| **Mode** | [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md) |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawElements** | void |  |
| **GetLabelRect** | SizeF |  |

---

### Method Details

#### DrawElements

**DrawElements**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **vertices**: [StiMatrix](../Export/StiMatrix.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **vertices** ([StiMatrix](../Export/StiMatrix.md))  


---

#### GetLabelRect

**GetLabelRect**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): SizeF

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  

**Returns** SizeF

