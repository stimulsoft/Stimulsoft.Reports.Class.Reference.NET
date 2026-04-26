---
title: "StiGdiContextPainter Class"
---

## StiGdiContextPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiContextPainter](../Stimulsoft/Base/Context/StiContextPainter.md)  
Implements: [IStiAnimationContextPainter](Context/Animation/IStiAnimationContextPainter.md)<[StiGeom](../Stimulsoft/Base/Context/StiGeom.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGdiContextPainter**([Graphics](../../Stimulsoft_Drawing/root/Graphics.md) graphics) |  |

**StiGdiContextPainter**(**graphics**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md))

**Parameters**

- **graphics** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AnimationEngine** | [StiAnimationEngine](Context/Animation/StiAnimationEngine.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | [StiContextPainter](../Stimulsoft/Base/Context/StiContextPainter.md) |  |
| **CreateShadowGraphics** | [StiContext](../Stimulsoft/Base/Context/StiContext.md) |  |
| **Dispose** | void |  |
| **GetDefaultStringFormat** | [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md) |  |
| **GetGenericStringFormat** | [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md) |  |
| **GetPathBounds** | RectangleF |  |
| **MeasureRotatedString** *(+3 overloads)* | RectangleF |  |
| **MeasureString** *(+1 overloads)* | SizeF |  |
| **Render** | void |  |

---

### Method Details

#### Clone

**Clone**(): [StiContextPainter](../Stimulsoft/Base/Context/StiContextPainter.md)

**Returns** [StiContextPainter](../Stimulsoft/Base/Context/StiContextPainter.md)


---

#### CreateShadowGraphics

**CreateShadowGraphics**(**isPrinting**: bool, **zoom**: float): [StiContext](../Stimulsoft/Base/Context/StiContext.md)

**Parameters**

- **isPrinting** (bool)  
- **zoom** (float)  

**Returns** [StiContext](../Stimulsoft/Base/Context/StiContext.md)


---

#### Dispose

**Dispose**(): void


---

#### GetDefaultStringFormat

**GetDefaultStringFormat**(): [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md)

**Returns** [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md)


---

#### GetGenericStringFormat

**GetGenericStringFormat**(): [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md)

**Returns** [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md)


---

#### GetPathBounds

**GetPathBounds**(**geoms**: List<[StiSegmentGeom](../Stimulsoft/Base/Context/StiSegmentGeom.md)>): RectangleF

**Parameters**

- **geoms** (List<[StiSegmentGeom](../Stimulsoft/Base/Context/StiSegmentGeom.md)>)  

**Returns** RectangleF


---

#### MeasureRotatedString

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md), **angle**: float): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md))  
- **angle** (float)  

**Returns** RectangleF

---

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md), **mode**: [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md))  
- **mode** ([StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  

**Returns** RectangleF

---

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **point**: PointF, **sf**: [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md), **mode**: [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float, **maximalWidth**: int): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **point** (PointF)  
- **sf** ([StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md))  
- **mode** ([StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  
- **maximalWidth** (int)  

**Returns** RectangleF

---

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **point**: PointF, **sf**: [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md), **mode**: [StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **point** (PointF)  
- **sf** ([StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md))  
- **mode** ([StiRotationMode](../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  

**Returns** RectangleF


---

#### MeasureString

**MeasureString**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md), **width**: int, **sf**: [StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](../Stimulsoft/Base/Context/StiFontGeom.md))  
- **width** (int)  
- **sf** ([StiStringFormatGeom](../Stimulsoft/Base/Context/StiStringFormatGeom.md))  

**Returns** SizeF


---

#### Render

**Render**(**rect**: RectangleF, **geoms**: List<[StiGeom](../Stimulsoft/Base/Context/StiGeom.md)>): void

**Parameters**

- **rect** (RectangleF)  
- **geoms** (List<[StiGeom](../Stimulsoft/Base/Context/StiGeom.md)>)  

