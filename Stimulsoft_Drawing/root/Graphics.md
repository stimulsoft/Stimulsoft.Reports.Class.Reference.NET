---
title: "Graphics Class"
---

## Graphics Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GraphicsEngine** `static` | [GraphicsEngine](GraphicsEngine.md) |  |
| **SixLaborsFontsKerning** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Dispose** | void |  |
| **DrawArc** *(+1 overloads)* | void |  |
| **DrawCurve** *(+1 overloads)* | void |  |
| **DrawEllipse** *(+3 overloads)* | void |  |
| **DrawImage** *(+14 overloads)* | void |  |
| **DrawImageUnscaled** *(+3 overloads)* | void |  |
| **DrawImageUnscaledAndClipped** | void |  |
| **DrawLine** *(+3 overloads)* | void |  |
| **DrawLines** *(+1 overloads)* | void |  |
| **DrawPath** | void |  |
| **DrawPie** | void |  |
| **DrawPolygon** | void |  |
| **DrawRectangle** *(+2 overloads)* | void |  |
| **DrawString** *(+5 overloads)* | void |  |
| **EnumerateMetafile** | void |  |
| **FillEllipse** *(+3 overloads)* | void |  |
| **FillPath** | void |  |
| **FillPie** | void |  |
| **FillPolygon** | void |  |
| **FillRectangle** *(+3 overloads)* | void |  |
| **FillRegion** | void |  |
| **Flush** | void |  |
| **FromHdc** `static` | [Graphics](Graphics.md) |  |
| **FromHwnd** `static` | [Graphics](Graphics.md) |  |
| **FromImage** `static` | [Graphics](Graphics.md) |  |
| **GetHdc** | IntPtr |  |
| **MeasureCharacterRanges** | [Region](Region.md)[] |  |
| **MeasureString** *(+5 overloads)* | SizeF |  |
| **MultiplyTransform** | void |  |
| **ReleaseHdc** *(+1 overloads)* | void |  |
| **ResetClip** | void |  |
| **ResetTransform** | void |  |
| **Restore** | void |  |
| **RotateTransform** *(+1 overloads)* | void |  |
| **Save** | [GraphicsState](../Drawing2D/GraphicsState.md) |  |
| **ScaleTransform** *(+1 overloads)* | void |  |
| **SetClip** *(+5 overloads)* | void |  |
| **TransformPoints** | void |  |
| **TranslateTransform** *(+3 overloads)* | void |  |

---

### Method Details

#### Clear

**Clear**(**color**: Color): void

**Parameters**

- **color** (Color)  


---

#### Dispose

**Dispose**(): void


---

#### DrawArc

**DrawArc**(**pen**: [Pen](Pen.md), **rect**: RectangleF, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  

---

**DrawArc**(**pen**: [Pen](Pen.md), **x**: float, **y**: float, **width**: float, **height**: float, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### DrawCurve

**DrawCurve**(**pen**: [Pen](Pen.md), ****: PointFpoints): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **** (PointFpoints)  

---

**DrawCurve**(**pen**: [Pen](Pen.md), ****: PointFpoints, **tension**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **** (PointFpoints)  
- **tension** (float)  


---

#### DrawEllipse

**DrawEllipse**(**pen**: [Pen](Pen.md), **rect**: Rectangle): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **rect** (Rectangle)  

---

**DrawEllipse**(**pen**: [Pen](Pen.md), **rect**: RectangleF): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **rect** (RectangleF)  

---

**DrawEllipse**(**pen**: [Pen](Pen.md), **x**: int, **y**: int, **width**: int, **height**: int): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  

---

**DrawEllipse**(**pen**: [Pen](Pen.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### DrawImage

**DrawImage**(**image**: [Image](Image.md), **rect**: Rectangle): void

**Parameters**

- **image** ([Image](Image.md))  
- **rect** (Rectangle)  

---

**DrawImage**(**image**: [Image](Image.md), **rect**: RectangleF): void

**Parameters**

- **image** ([Image](Image.md))  
- **rect** (RectangleF)  

---

**DrawImage**(**image**: [Image](Image.md), ****: PointFdestPoints, **srcRect**: RectangleF, **srcUnit**: GraphicsUnit, **imageAttr**: [ImageAttributes](../Imaging/ImageAttributes.md)): void

**Parameters**

- **image** ([Image](Image.md))  
- **** (PointFdestPoints)  
- **srcRect** (RectangleF)  
- **srcUnit** (GraphicsUnit)  
- **imageAttr** ([ImageAttributes](../Imaging/ImageAttributes.md))  

---

**DrawImage**(**image**: [Image](Image.md), **point**: Point): void

**Parameters**

- **image** ([Image](Image.md))  
- **point** (Point)  

---

**DrawImage**(**image**: [Image](Image.md), **x**: float, **y**: float): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (float)  
- **y** (float)  

---

**DrawImage**(**image**: [Image](Image.md), **x**: int, **y**: int): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (int)  
- **y** (int)  

---

**DrawImage**(**image**: [Image](Image.md), **destRect**: Rectangle, **srcRect**: Rectangle, **srcUnit**: GraphicsUnit): void

**Parameters**

- **image** ([Image](Image.md))  
- **destRect** (Rectangle)  
- **srcRect** (Rectangle)  
- **srcUnit** (GraphicsUnit)  

---

**DrawImage**(**image**: [Image](Image.md), **destRect**: RectangleF, **srcRect**: RectangleF, **srcUnit**: GraphicsUnit): void

**Parameters**

- **image** ([Image](Image.md))  
- **destRect** (RectangleF)  
- **srcRect** (RectangleF)  
- **srcUnit** (GraphicsUnit)  

---

**DrawImage**(**image**: [Image](Image.md), **x**: float, **y**: float, **srcRect**: Rectangle, **srcUnit**: GraphicsUnit): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (float)  
- **y** (float)  
- **srcRect** (Rectangle)  
- **srcUnit** (GraphicsUnit)  

---

**DrawImage**(**image**: [Image](Image.md), **destRect**: Rectangle, **srcX**: int, **srcY**: int, **srcWidth**: int, **srcHeight**: int, **srcUnit**: GraphicsUnit): void

**Parameters**

- **image** ([Image](Image.md))  
- **destRect** (Rectangle)  
- **srcX** (int)  
- **srcY** (int)  
- **srcWidth** (int)  
- **srcHeight** (int)  
- **srcUnit** (GraphicsUnit)  

---

**DrawImage**(**image**: [Image](Image.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  

---

**DrawImage**(**image**: [Image](Image.md), **x**: int, **y**: int, **width**: int, **height**: int): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  

---

**DrawImage**(**image**: [Image](Image.md), **destRect**: Rectangle, **srcX**: float, **srcY**: float, **srcWidth**: float, **srcHeight**: float, **srcUnit**: GraphicsUnit, **imageAttr**: [ImageAttributes](../Imaging/ImageAttributes.md)): void

**Parameters**

- **image** ([Image](Image.md))  
- **destRect** (Rectangle)  
- **srcX** (float)  
- **srcY** (float)  
- **srcWidth** (float)  
- **srcHeight** (float)  
- **srcUnit** (GraphicsUnit)  
- **imageAttr** ([ImageAttributes](../Imaging/ImageAttributes.md))  

---

**DrawImage**(**image**: [Image](Image.md), **destRect**: Rectangle, **srcX**: int, **srcY**: int, **srcWidth**: int, **srcHeight**: int, **srcUnit**: GraphicsUnit, **imageAttr**: [ImageAttributes](../Imaging/ImageAttributes.md)): void

**Parameters**

- **image** ([Image](Image.md))  
- **destRect** (Rectangle)  
- **srcX** (int)  
- **srcY** (int)  
- **srcWidth** (int)  
- **srcHeight** (int)  
- **srcUnit** (GraphicsUnit)  
- **imageAttr** ([ImageAttributes](../Imaging/ImageAttributes.md))  

---

**DrawImage**(**image**: [Image](Image.md), **destRect**: Rectangle, **srcX**: int, **srcY**: int, **srcWidth**: int, **srcHeight**: int, **srcUnit**: GraphicsUnit, **imageAttrs**: [ImageAttributes](../Imaging/ImageAttributes.md), **callback**: object, **callbackData**: IntPtr): void

**Parameters**

- **image** ([Image](Image.md))  
- **destRect** (Rectangle)  
- **srcX** (int)  
- **srcY** (int)  
- **srcWidth** (int)  
- **srcHeight** (int)  
- **srcUnit** (GraphicsUnit)  
- **imageAttrs** ([ImageAttributes](../Imaging/ImageAttributes.md))  
- **callback** (object)  
- **callbackData** (IntPtr)  


---

#### DrawImageUnscaled

**DrawImageUnscaled**(**image**: [Image](Image.md), **rect**: Rectangle): void

**Parameters**

- **image** ([Image](Image.md))  
- **rect** (Rectangle)  

---

**DrawImageUnscaled**(**image**: [Image](Image.md), **point**: Point): void

**Parameters**

- **image** ([Image](Image.md))  
- **point** (Point)  

---

**DrawImageUnscaled**(**image**: [Image](Image.md), **x**: int, **y**: int): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (int)  
- **y** (int)  

---

**DrawImageUnscaled**(**image**: [Image](Image.md), **x**: int, **y**: int, **width**: int, **height**: int): void

**Parameters**

- **image** ([Image](Image.md))  
- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  


---

#### DrawImageUnscaledAndClipped

**DrawImageUnscaledAndClipped**(**image**: [Image](Image.md), **rect**: Rectangle): void

**Parameters**

- **image** ([Image](Image.md))  
- **rect** (Rectangle)  


---

#### DrawLine

**DrawLine**(**pen**: [Pen](Pen.md), **pt1**: Point, **pt2**: Point): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **pt1** (Point)  
- **pt2** (Point)  

---

**DrawLine**(**pen**: [Pen](Pen.md), **pt1**: PointF, **pt2**: PointF): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **pt1** (PointF)  
- **pt2** (PointF)  

---

**DrawLine**(**pen**: [Pen](Pen.md), **x1**: int, **y1**: int, **x2**: int, **y2**: int): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x1** (int)  
- **y1** (int)  
- **x2** (int)  
- **y2** (int)  

---

**DrawLine**(**pen**: [Pen](Pen.md), **x1**: float, **y1**: float, **x2**: float, **y2**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x1** (float)  
- **y1** (float)  
- **x2** (float)  
- **y2** (float)  


---

#### DrawLines

**DrawLines**(**pen**: [Pen](Pen.md), ****: Pointpoints): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **** (Pointpoints)  

---

**DrawLines**(**pen**: [Pen](Pen.md), ****: PointFpoints): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **** (PointFpoints)  


---

#### DrawPath

**DrawPath**(**pen**: [Pen](Pen.md), **path**: [GraphicsPath](../Drawing2D/GraphicsPath.md)): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **path** ([GraphicsPath](../Drawing2D/GraphicsPath.md))  


---

#### DrawPie

**DrawPie**(**pen**: [Pen](Pen.md), **rect**: RectangleF, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### DrawPolygon

**DrawPolygon**(**pen**: [Pen](Pen.md), ****: PointFpoints): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **** (PointFpoints)  


---

#### DrawRectangle

**DrawRectangle**(**pen**: [Pen](Pen.md), **rect**: Rectangle): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **rect** (Rectangle)  

---

**DrawRectangle**(**pen**: [Pen](Pen.md), **x**: int, **y**: int, **width**: int, **height**: int): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  

---

**DrawRectangle**(**pen**: [Pen](Pen.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **pen** ([Pen](Pen.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### DrawString

**DrawString**(**s**: string, **font**: [Font](Font.md), **brush**: [Brush](Brush.md), **layoutRectangle**: RectangleF): void

**Parameters**

- **s** (string)  
- **font** ([Font](Font.md))  
- **brush** ([Brush](Brush.md))  
- **layoutRectangle** (RectangleF)  

---

**DrawString**(**s**: string, **font**: [Font](Font.md), **brush**: [Brush](Brush.md), **point**: PointF): void

**Parameters**

- **s** (string)  
- **font** ([Font](Font.md))  
- **brush** ([Brush](Brush.md))  
- **point** (PointF)  

---

**DrawString**(**s**: string, **font**: [Font](Font.md), **brush**: [Brush](Brush.md), **point**: PointF, **format**: [StringFormat](StringFormat.md)): void

**Parameters**

- **s** (string)  
- **font** ([Font](Font.md))  
- **brush** ([Brush](Brush.md))  
- **point** (PointF)  
- **format** ([StringFormat](StringFormat.md))  

---

**DrawString**(**s**: string, **font**: [Font](Font.md), **brush**: [Brush](Brush.md), **x**: float, **y**: float): void

**Parameters**

- **s** (string)  
- **font** ([Font](Font.md))  
- **brush** ([Brush](Brush.md))  
- **x** (float)  
- **y** (float)  

---

**DrawString**(**s**: string, **font**: [Font](Font.md), **brush**: [Brush](Brush.md), **x**: float, **y**: float, **format**: [StringFormat](StringFormat.md)): void

**Parameters**

- **s** (string)  
- **font** ([Font](Font.md))  
- **brush** ([Brush](Brush.md))  
- **x** (float)  
- **y** (float)  
- **format** ([StringFormat](StringFormat.md))  

---

**DrawString**(**s**: string, **font**: [Font](Font.md), **brush**: [Brush](Brush.md), **layoutRectangle**: RectangleF, **format**: [StringFormat](StringFormat.md)): void

**Parameters**

- **s** (string)  
- **font** ([Font](Font.md))  
- **brush** ([Brush](Brush.md))  
- **layoutRectangle** (RectangleF)  
- **format** ([StringFormat](StringFormat.md))  


---

#### EnumerateMetafile

**EnumerateMetafile**(**metafile**: [Metafile](../Imaging/Metafile.md), **m_destPoint**: Point, **m_delegate**: EnumerateMetafileProc): void

**Parameters**

- **metafile** ([Metafile](../Imaging/Metafile.md))  
- **m_destPoint** (Point)  
- **m_delegate** (EnumerateMetafileProc)  


---

#### FillEllipse

**FillEllipse**(**brush**: [Brush](Brush.md), **rect**: Rectangle): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **rect** (Rectangle)  

---

**FillEllipse**(**brush**: [Brush](Brush.md), **rect**: RectangleF): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **rect** (RectangleF)  

---

**FillEllipse**(**brush**: [Brush](Brush.md), **x**: int, **y**: int, **width**: int, **height**: int): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  

---

**FillEllipse**(**brush**: [Brush](Brush.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### FillPath

**FillPath**(**brush**: [Brush](Brush.md), **path**: [GraphicsPath](../Drawing2D/GraphicsPath.md)): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **path** ([GraphicsPath](../Drawing2D/GraphicsPath.md))  


---

#### FillPie

**FillPie**(**brush**: [Brush](Brush.md), **x**: float, **y**: float, **width**: float, **height**: float, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### FillPolygon

**FillPolygon**(**brush**: [Brush](Brush.md), ****: PointFpoints): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **** (PointFpoints)  


---

#### FillRectangle

**FillRectangle**(**brush**: [Brush](Brush.md), **rect**: RectangleF): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **rect** (RectangleF)  

---

**FillRectangle**(**brush**: [Brush](Brush.md), **rect**: Rectangle): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **rect** (Rectangle)  

---

**FillRectangle**(**brush**: [Brush](Brush.md), **x**: int, **y**: int, **width**: int, **height**: int): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  

---

**FillRectangle**(**brush**: [Brush](Brush.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### FillRegion

**FillRegion**(**brush**: [Brush](Brush.md), **region**: [Region](Region.md)): void

**Parameters**

- **brush** ([Brush](Brush.md))  
- **region** ([Region](Region.md))  


---

#### Flush

**Flush**(): void


---

#### FromHdc `static`

**FromHdc**(**hdc**: IntPtr): [Graphics](Graphics.md)

**Parameters**

- **hdc** (IntPtr)  

**Returns** [Graphics](Graphics.md)


---

#### FromHwnd `static`

**FromHwnd**(**handle**: IntPtr): [Graphics](Graphics.md)

**Parameters**

- **handle** (IntPtr)  

**Returns** [Graphics](Graphics.md)


---

#### FromImage `static`

**FromImage**(**image**: [Image](Image.md)): [Graphics](Graphics.md)

**Parameters**

- **image** ([Image](Image.md))  

**Returns** [Graphics](Graphics.md)


---

#### GetHdc

**GetHdc**(): IntPtr

**Returns** IntPtr


---

#### MeasureCharacterRanges

**MeasureCharacterRanges**(**text**: string, **font**: [Font](Font.md), **layoutRectangle**: RectangleF, **format**: [StringFormat](StringFormat.md)): [Region](Region.md)[]

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  
- **layoutRectangle** (RectangleF)  
- **format** ([StringFormat](StringFormat.md))  

**Returns** [Region](Region.md)[]


---

#### MeasureString

**MeasureString**(**text**: string, **font**: [Font](Font.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [Font](Font.md), **layoutArea**: SizeF): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  
- **layoutArea** (SizeF)  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [Font](Font.md), **width**: int): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  
- **width** (int)  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [Font](Font.md), **layoutArea**: SizeF, **stringFormat**: [StringFormat](StringFormat.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  
- **layoutArea** (SizeF)  
- **stringFormat** ([StringFormat](StringFormat.md))  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [Font](Font.md), **width**: int, **stringFormat**: [StringFormat](StringFormat.md)): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  
- **width** (int)  
- **stringFormat** ([StringFormat](StringFormat.md))  

**Returns** SizeF

---

**MeasureString**(**text**: string, **font**: [Font](Font.md), **layoutArea**: SizeF, **stringFormat**: [StringFormat](StringFormat.md), **charactersFitted**: int, **linesFilled**: int): SizeF

**Parameters**

- **text** (string)  
- **font** ([Font](Font.md))  
- **layoutArea** (SizeF)  
- **stringFormat** ([StringFormat](StringFormat.md))  
- **charactersFitted** (int)  
- **linesFilled** (int)  

**Returns** SizeF


---

#### MultiplyTransform

**MultiplyTransform**(**matrix**: [Matrix](../Drawing2D/Matrix.md)): void

**Parameters**

- **matrix** ([Matrix](../Drawing2D/Matrix.md))  


---

#### ReleaseHdc

**ReleaseHdc**(): void

---

**ReleaseHdc**(**ptrGraphics**: IntPtr): void

**Parameters**

- **ptrGraphics** (IntPtr)  


---

#### ResetClip

**ResetClip**(): void


---

#### ResetTransform

**ResetTransform**(): void


---

#### Restore

**Restore**(**state**: [GraphicsState](../Drawing2D/GraphicsState.md)): void

**Parameters**

- **state** ([GraphicsState](../Drawing2D/GraphicsState.md))  


---

#### RotateTransform

**RotateTransform**(**angle**: float): void

**Parameters**

- **angle** (float)  

---

**RotateTransform**(**angle**: float, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **angle** (float)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


---

#### Save

**Save**(): [GraphicsState](../Drawing2D/GraphicsState.md)

**Returns** [GraphicsState](../Drawing2D/GraphicsState.md)


---

#### ScaleTransform

**ScaleTransform**(**scaleX**: float, **scaleY**: float): void

**Parameters**

- **scaleX** (float)  
- **scaleY** (float)  

---

**ScaleTransform**(**scaleX**: float, **scaleY**: float, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **scaleX** (float)  
- **scaleY** (float)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


---

#### SetClip

**SetClip**(**region**: [Region](Region.md), **intersect**: System.Drawing.Drawing2D.CombineMode): void

**Parameters**

- **region** ([Region](Region.md))  
- **intersect** (System.Drawing.Drawing2D.CombineMode)  

---

**SetClip**(**rect**: Rectangle, **intersect**: System.Drawing.Drawing2D.CombineMode): void

**Parameters**

- **rect** (Rectangle)  
- **intersect** (System.Drawing.Drawing2D.CombineMode)  

---

**SetClip**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  

---

**SetClip**(**rect**: RectangleF, **intersect**: System.Drawing.Drawing2D.CombineMode): void

**Parameters**

- **rect** (RectangleF)  
- **intersect** (System.Drawing.Drawing2D.CombineMode)  

---

**SetClip**(**path**: [GraphicsPath](../Drawing2D/GraphicsPath.md)): void

**Parameters**

- **path** ([GraphicsPath](../Drawing2D/GraphicsPath.md))  

---

**SetClip**(**path**: [GraphicsPath](../Drawing2D/GraphicsPath.md), **intersect**: System.Drawing.Drawing2D.CombineMode): void

**Parameters**

- **path** ([GraphicsPath](../Drawing2D/GraphicsPath.md))  
- **intersect** (System.Drawing.Drawing2D.CombineMode)  


---

#### TransformPoints

**TransformPoints**(**page**: System.Drawing.Drawing2D.CoordinateSpace, **device**: System.Drawing.Drawing2D.CoordinateSpace, ****: PointFpoints): void

**Parameters**

- **page** (System.Drawing.Drawing2D.CoordinateSpace)  
- **device** (System.Drawing.Drawing2D.CoordinateSpace)  
- **** (PointFpoints)  


---

#### TranslateTransform

**TranslateTransform**(**x**: int, **y**: int): void

**Parameters**

- **x** (int)  
- **y** (int)  

---

**TranslateTransform**(**x**: int, **y**: int, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **x** (int)  
- **y** (int)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  

---

**TranslateTransform**(**x**: float, **y**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  

---

**TranslateTransform**(**x**: float, **y**: float, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **x** (float)  
- **y** (float)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DefaultImageSharpDpi** | float |  |
| **DefaultTabSize** | int |  |
| **ReplaceTabWithSpaces** | bool |  |
