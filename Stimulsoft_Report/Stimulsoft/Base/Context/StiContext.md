---
title: "StiContext Class"
---

## StiContext Class

**Namespace:** `Stimulsoft.Base.Context`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiContext**([StiContextPainter](StiContextPainter.md) contextPainter, bool isGdi, bool isWpf, bool isPrinting, float zoom) |  |

**StiContext**(**contextPainter**: [StiContextPainter](StiContextPainter.md), **isGdi**: bool, **isWpf**: bool, **isPrinting**: bool, **zoom**: float)

**Parameters**

- **contextPainter** ([StiContextPainter](StiContextPainter.md))  
- **isGdi** (bool)  
- **isWpf** (bool)  
- **isPrinting** (bool)  
- **zoom** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Animations** | List<[StiAnimation](Animation/StiAnimation.md)> |  |
| **ContextPainter** | [StiContextPainter](StiContextPainter.md) |  |
| **Geoms** | List<[StiGeom](StiGeom.md)> |  |
| **Options** | [StiContextOptions](StiContextOptions.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateShadowGraphics** | [StiContext](StiContext.md) |  |
| **DrawAnimationBar** *(+1 overloads)* | void |  |
| **DrawAnimationCicledRectangle** | void |  |
| **DrawAnimationColumn** *(+1 overloads)* | void |  |
| **DrawAnimationCurve** | void |  |
| **DrawAnimationLines** | void |  |
| **DrawAnimationPathElement** *(+1 overloads)* | void |  |
| **DrawAnimationRectangle** | void |  |
| **DrawCachedShadow** *(+2 overloads)* | void |  |
| **DrawCicledRectangle** | void |  |
| **DrawCurve** | void |  |
| **DrawEllipse** *(+1 overloads)* | void |  |
| **DrawImage** | void |  |
| **DrawLine** | void |  |
| **DrawLines** | void |  |
| **DrawPath** | void |  |
| **DrawRectangle** *(+2 overloads)* | void |  |
| **DrawRotatedString** *(+1 overloads)* | [StiTextGeom](StiTextGeom.md) |  |
| **DrawShadow** | void |  |
| **DrawShadowCircle** | void |  |
| **DrawShadowRect** | void |  |
| **DrawString** *(+4 overloads)* | [StiTextGeom](StiTextGeom.md) |  |
| **FillCicledRectangle** | void |  |
| **FillDrawAnimationEllipse** *(+1 overloads)* | void |  |
| **FillDrawAnimationPath** *(+1 overloads)* | void |  |
| **FillEllipse** *(+2 overloads)* | void |  |
| **FillPath** | void |  |
| **FillRectangle** *(+2 overloads)* | void |  |
| **GetDefaultStringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **GetGenericStringFormat** | [StiStringFormatGeom](StiStringFormatGeom.md) |  |
| **GetPathBounds** | RectangleF |  |
| **MeasureRotatedString** *(+3 overloads)* | RectangleF |  |
| **MeasureString** *(+1 overloads)* | SizeF |  |
| **PopClip** | void |  |
| **PopSmoothingMode** | void |  |
| **PopTextRenderingHint** | void |  |
| **PopTransform** | void |  |
| **PushClip** | void |  |
| **PushClipPath** | void |  |
| **PushRotateTransform** | void |  |
| **PushSmoothingModeToAntiAlias** | void |  |
| **PushTextRenderingHintToAntiAlias** | void |  |
| **PushTranslateTransform** | void |  |
| **Render** | void |  |

---

### Method Details

#### CreateShadowGraphics

**CreateShadowGraphics**(): [StiContext](StiContext.md)

**Returns** [StiContext](StiContext.md)


---

#### DrawAnimationBar

**DrawAnimationBar**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **columnRect**: object, **cornerRadius**: StiCornerRadius, **value**: double?, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **columnRect** (object)  
- **cornerRadius** (StiCornerRadius)  
- **value** (double?)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

---

**DrawAnimationBar**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **columnRect**: object, **value**: double?, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **columnRect** (object)  
- **value** (double?)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


---

#### DrawAnimationCicledRectangle

**DrawAnimationCicledRectangle**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **rect**: RectangleF, **cornerRadius**: StiCornerRadius, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **toolTip**: string): void

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (RectangleF)  
- **cornerRadius** (StiCornerRadius)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **toolTip** (string)  


---

#### DrawAnimationColumn

**DrawAnimationColumn**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **cornerRadius**: StiCornerRadius, **value**: double?, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **cornerRadius** (StiCornerRadius)  
- **value** (double?)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

---

**DrawAnimationColumn**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **rect**: object, **value**: double?, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (object)  
- **value** (double?)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


---

#### DrawAnimationCurve

**DrawAnimationCurve**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints, **tension**: float, **animation**: [StiAnimation](Animation/StiAnimation.md)): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  
- **tension** (float)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


---

#### DrawAnimationLines

**DrawAnimationLines**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints, **animation**: [StiAnimation](Animation/StiAnimation.md)): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


---

#### DrawAnimationPathElement

**DrawAnimationPathElement**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **path**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **path** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

---

**DrawAnimationPathElement**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **borderPen**: [StiPenGeom](StiPenGeom.md), **path**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **borderPen** ([StiPenGeom](StiPenGeom.md))  
- **path** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


---

#### DrawAnimationRectangle

**DrawAnimationRectangle**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **rect**: RectangleF, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **toolTip**: string): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (RectangleF)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **toolTip** (string)  


---

#### DrawCachedShadow

**DrawCachedShadow**(**rect**: RectangleF, **sides**: [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md), **isPrinting**: bool): void

**Parameters**

- **rect** (RectangleF)  
- **sides** ([StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md))  
- **isPrinting** (bool)  

---

**DrawCachedShadow**(**rect**: RectangleF, **sides**: [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md), **isPrinting**: bool, **clipRect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  
- **sides** ([StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md))  
- **isPrinting** (bool)  
- **clipRect** (RectangleF)  

---

**DrawCachedShadow**(**rect**: RectangleF, **sides**: [StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md), **isPrinting**: bool, **clipRect**: RectangleF, **cornerRadius**: StiCornerRadius): void

**Parameters**

- **rect** (RectangleF)  
- **sides** ([StiShadowSides](../../../../Stimulsoft_Base/Drawing/StiShadowSides.md))  
- **isPrinting** (bool)  
- **clipRect** (RectangleF)  
- **cornerRadius** (StiCornerRadius)  


---

#### DrawCicledRectangle

**DrawCicledRectangle**(**pen**: [StiPenGeom](StiPenGeom.md), **rect**: RectangleF, **cornerRadius**: StiCornerRadius): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (RectangleF)  
- **cornerRadius** (StiCornerRadius)  


---

#### DrawCurve

**DrawCurve**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints, **tension**: float): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  
- **tension** (float)  


---

#### DrawEllipse

**DrawEllipse**(**pen**: [StiPenGeom](StiPenGeom.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  

---

**DrawEllipse**(**pen**: [StiPenGeom](StiPenGeom.md), **rect**: RectangleF): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (RectangleF)  


---

#### DrawImage

**DrawImage**(****: byteimage, **rect**: RectangleF): void

**Parameters**

- **** (byteimage)  
- **rect** (RectangleF)  


---

#### DrawLine

**DrawLine**(**pen**: [StiPenGeom](StiPenGeom.md), **x1**: float, **y1**: float, **x2**: float, **y2**: float): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **x1** (float)  
- **y1** (float)  
- **x2** (float)  
- **y2** (float)  


---

#### DrawLines

**DrawLines**(**pen**: [StiPenGeom](StiPenGeom.md), ****: PointFpoints): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **** (PointFpoints)  


---

#### DrawPath

**DrawPath**(**pen**: [StiPenGeom](StiPenGeom.md), **path**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **tag**: object): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **path** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **tag** (object)  


---

#### DrawRectangle

**DrawRectangle**(**pen**: [StiPenGeom](StiPenGeom.md), **rect**: Rectangle): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (Rectangle)  

---

**DrawRectangle**(**pen**: [StiPenGeom](StiPenGeom.md), **rect**: RectangleF): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **rect** (RectangleF)  

---

**DrawRectangle**(**pen**: [StiPenGeom](StiPenGeom.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **pen** ([StiPenGeom](StiPenGeom.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### DrawRotatedString

**DrawRotatedString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: Rectangle, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **angle**: float, **antialiasing**: bool): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (Rectangle)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **angle** (float)  
- **antialiasing** (bool)  

**Returns** [StiTextGeom](StiTextGeom.md)

---

**DrawRotatedString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **angle**: float, **antialiasing**: bool): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **angle** (float)  
- **antialiasing** (bool)  

**Returns** [StiTextGeom](StiTextGeom.md)


---

#### DrawShadow

**DrawShadow**(**sg**: [StiContext](StiContext.md), **rect**: RectangleF, **radius**: float): void

**Parameters**

- **sg** ([StiContext](StiContext.md))  
- **rect** (RectangleF)  
- **radius** (float)  


---

#### DrawShadowCircle

**DrawShadowCircle**(**rect**: RectangleF, **radiusX**: double, **radiusY**: double, **shadowWidth**: int, **animation**: [StiAnimation](Animation/StiAnimation.md)): void

**Parameters**

- **rect** (RectangleF)  
- **radiusX** (double)  
- **radiusY** (double)  
- **shadowWidth** (int)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


---

#### DrawShadowRect

**DrawShadowRect**(**rect**: RectangleF, **shadowWidth**: int, **cornerRadius**: StiCornerRadius, **animation**: [StiAnimation](Animation/StiAnimation.md)): void

**Parameters**

- **rect** (RectangleF)  
- **shadowWidth** (int)  
- **cornerRadius** (StiCornerRadius)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  


---

#### DrawString

**DrawString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **antialiasing**: bool, **toolTip**: string, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **antialiasing** (bool)  
- **toolTip** (string)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

**Returns** [StiTextGeom](StiTextGeom.md)

---

**DrawString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: Rectangle, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md)): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (Rectangle)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  

**Returns** [StiTextGeom](StiTextGeom.md)

---

**DrawString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **elementIndex**: int): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **elementIndex** (int)  

**Returns** [StiTextGeom](StiTextGeom.md)

---

**DrawString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **maximalWidth**: int, **elementIndex**: int): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **maximalWidth** (int)  
- **elementIndex** (int)  

**Returns** [StiTextGeom](StiTextGeom.md)

---

**DrawString**(**text**: string, **font**: [StiFontGeom](StiFontGeom.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StiStringFormatGeom](StiStringFormatGeom.md), **antialiasing**: bool, **toolTip**: string): [StiTextGeom](StiTextGeom.md)

**Parameters**

- **text** (string)  
- **font** ([StiFontGeom](StiFontGeom.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StiStringFormatGeom](StiStringFormatGeom.md))  
- **antialiasing** (bool)  
- **toolTip** (string)  

**Returns** [StiTextGeom](StiTextGeom.md)


---

#### FillCicledRectangle

**FillCicledRectangle**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **cornerRadius**: StiCornerRadius, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **tooltip**: string, **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **cornerRadius** (StiCornerRadius)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **tooltip** (string)  
- **elementIndex** (int)  


---

#### FillDrawAnimationEllipse

**FillDrawAnimationEllipse**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **x**: float, **y**: float, **width**: float, **height**: float, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

---

**FillDrawAnimationEllipse**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **x**: float, **y**: float, **width**: float, **height**: float, **toolTip**: string, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **toolTip** (string)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


---

#### FillDrawAnimationPath

**FillDrawAnimationPath**(**wpfBackColor**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **path**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **wpfBackColor** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **path** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  

---

**FillDrawAnimationPath**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **pen**: [StiPenGeom](StiPenGeom.md), **path**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **tag**: object, **animation**: [StiAnimation](Animation/StiAnimation.md), **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md)): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pen** ([StiPenGeom](StiPenGeom.md))  
- **path** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **tag** (object)  
- **animation** ([StiAnimation](Animation/StiAnimation.md))  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  


---

#### FillEllipse

**FillEllipse**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **x**: float, **y**: float, **width**: float, **height**: float, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  

---

**FillEllipse**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **x**: float, **y**: float, **width**: float, **height**: float, **toolTip**: string, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **toolTip** (string)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  

---

**FillEllipse**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  


---

#### FillPath

**FillPath**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **path**: List<[StiSegmentGeom](StiSegmentGeom.md)>, **rect**: object, **tag**: object, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int, **toolTip**: string): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **path** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  
- **rect** (object)  
- **tag** (object)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  
- **toolTip** (string)  


---

#### FillRectangle

**FillRectangle**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **brushMouseOver**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: Rectangle, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **brushMouseOver** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (Rectangle)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  

---

**FillRectangle**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: Rectangle, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (Rectangle)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  

---

**FillRectangle**(**brush**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **x**: float, **y**: float, **width**: float, **height**: float, **interaction**: [StiInteractionDataGeom](StiInteractionDataGeom.md), **elementIndex**: int): void

**Parameters**

- **brush** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **interaction** ([StiInteractionDataGeom](StiInteractionDataGeom.md))  
- **elementIndex** (int)  


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

#### PopClip

**PopClip**(): void


---

#### PopSmoothingMode

**PopSmoothingMode**(): void


---

#### PopTextRenderingHint

**PopTextRenderingHint**(): void


---

#### PopTransform

**PopTransform**(): void


---

#### PushClip

**PushClip**(**clipRect**: RectangleF): void

**Parameters**

- **clipRect** (RectangleF)  


---

#### PushClipPath

**PushClipPath**(**listGeoms**: List<[StiSegmentGeom](StiSegmentGeom.md)>): void

**Parameters**

- **listGeoms** (List<[StiSegmentGeom](StiSegmentGeom.md)>)  


---

#### PushRotateTransform

**PushRotateTransform**(**angle**: float): void

**Parameters**

- **angle** (float)  


---

#### PushSmoothingModeToAntiAlias

**PushSmoothingModeToAntiAlias**(): void


---

#### PushTextRenderingHintToAntiAlias

**PushTextRenderingHintToAntiAlias**(): void


---

#### PushTranslateTransform

**PushTranslateTransform**(**x**: float, **y**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  


---

#### Render

**Render**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  

