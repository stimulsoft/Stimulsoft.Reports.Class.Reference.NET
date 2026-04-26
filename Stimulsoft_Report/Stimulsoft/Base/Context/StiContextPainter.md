---
title: "StiContextPainter Class"
---

## StiContextPainter Class

**Namespace:** `Stimulsoft.Base.Context`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | [StiContextPainter](StiContextPainter.md) |  |
| **CreateShadowGraphics** | [StiContext](StiContext.md) |  |
| **Dispose** | void |  |
| **GetDefaultStringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **GetGenericStringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **GetPathBounds** | RectangleF |  |
| **MeasureRotatedString** *(+3 overloads)* | RectangleF |  |
| **MeasureString** *(+1 overloads)* | SizeF |  |
| **Render** | void |  |

---

### Method Details

#### Clone

**Clone**(): [StiContextPainter](StiContextPainter.md)

**Returns** [StiContextPainter](StiContextPainter.md)


---

#### CreateShadowGraphics

**CreateShadowGraphics**(**isPrinting**: bool, **zoom**: float): [StiContext](StiContext.md)

**Parameters**

- **isPrinting** (bool)  
- **zoom** (float)  

**Returns** [StiContext](StiContext.md)


---

#### Dispose

**Dispose**(): void


---

#### GetDefaultStringFormat

**GetDefaultStringFormat**(): [StiStringFormatGeom](StiStringFormatGeom.md)

**Returns** [StiStringFormatGeom](StiStringFormatGeom.md)


---

#### GetGenericStringFormat

**GetGenericStringFormat**(): [StiStringFormatGeom](StiStringFormatGeom.md)

**Returns** [StiStringFormatGeom](StiStringFormatGeom.md)


---

#### GetPathBounds

**GetPathBounds**(**geoms**: List<[StiSegmentGeom](StiSegmentGeom.md)>): RectangleF

**Parameters**

- **geoms** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  

**Returns** RectangleF


---

#### MeasureRotatedString

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **angle**: float): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **angle** (float)  

**Returns** RectangleF

---

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **mode**: [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **mode** ([StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  

**Returns** RectangleF

---

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **point**: PointF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **mode**: [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float, **maximalWidth**: int): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **point** (PointF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **mode** ([StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  
- **maximalWidth** (int)  

**Returns** RectangleF

---

**MeasureRotatedString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **point**: PointF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **mode**: [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md), **angle**: float): RectangleF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **point** (PointF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **mode** ([StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **angle** (float)  

**Returns** RectangleF


---

#### MeasureString

**MeasureString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **width**: int, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **width** (int)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  

**Returns** SizeF


---

#### Render

**Render**(**rect**: RectangleF, **geoms**: List<[StiGeom](StiGeom.md)>): void

**Parameters**

- **rect** (RectangleF)  
- **geoms** (List<[StiGeom](StiGeom.md)>)  

