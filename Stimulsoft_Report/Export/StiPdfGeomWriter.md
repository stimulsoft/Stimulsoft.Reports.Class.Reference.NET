---
title: "StiPdfGeomWriter Class"
---

## StiPdfGeomWriter Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Implements: [IStiExportGeomWriter](IStiExportGeomWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfGeomWriter**() |  |
| **StiPdfGeomWriter**(StreamWriter stream, [StiPdfExportService](StiPdfExportService.md) service, bool assembleData, bool allowThinLines, float cornerScaling) |  |

**StiPdfGeomWriter**()

---

**StiPdfGeomWriter**(**stream**: StreamWriter, **service**: [StiPdfExportService](StiPdfExportService.md), **assembleData**: bool, **allowThinLines**: bool, **cornerScaling**: float)

**Parameters**

- **stream** (StreamWriter)  
- **service** ([StiPdfExportService](StiPdfExportService.md))  
- **assembleData** (bool)  
- **allowThinLines** (bool)  
- **cornerScaling** (float)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BeginPath** | void |  |
| **CloseFigure** | void |  |
| **ConvertSplineToCubicBezier** | PointF[] |  |
| **DrawArc** *(+1 overloads)* | void |  |
| **DrawBezier** | void |  |
| **DrawBezierTo** | void |  |
| **DrawEllipse** | void |  |
| **DrawImage** | void |  |
| **DrawLine** | void |  |
| **DrawLineTo** | void |  |
| **DrawPie** | void |  |
| **DrawPolygon** | void |  |
| **DrawPolyline** *(+1 overloads)* | void |  |
| **DrawPolylineTo** | void |  |
| **DrawRectangle** | void |  |
| **DrawSpline** | void |  |
| **DrawString** | void |  |
| **DrawText** | void |  |
| **EndPath** | void |  |
| **FillEllipse** | void |  |
| **FillPath** | void |  |
| **FillPolygon** | void |  |
| **FillPolygons** | void |  |
| **FillRectangle** *(+1 overloads)* | void |  |
| **MeasureString** | SizeF |  |
| **MoveTo** | void |  |
| **RestoreState** | void |  |
| **RotateTransform** *(+1 overloads)* | void |  |
| **SaveState** | void |  |
| **ScaleTransform** | void |  |
| **SetBrush** | bool |  |
| **SetClip** | void |  |
| **SetClipPath** | void |  |
| **SetPen** | bool |  |
| **SetPixel** | void |  |
| **StrokePath** | void |  |
| **TranslateTransform** | void |  |

---

### Method Details

#### BeginPath

**BeginPath**(): void


---

#### CloseFigure

**CloseFigure**(): void


---

#### ConvertSplineToCubicBezier

**ConvertSplineToCubicBezier**(****: PointFpoints, **tension**: float): PointF[]

**Parameters**

- **** (PointFpoints)  
- **tension** (float)  

**Returns** PointF[]


---

#### DrawArc

**DrawArc**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  

---

**DrawArc**(**rect**: RectangleF, **p1**: PointF, **p2**: PointF, **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md)): void

**Parameters**

- **rect** (RectangleF)  
- **p1** (PointF)  
- **p2** (PointF)  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md))  


---

#### DrawBezier

**DrawBezier**(**p1**: PointF, **p2**: PointF, **p3**: PointF, **p4**: PointF, **pen**: object): void

**Parameters**

- **p1** (PointF)  
- **p2** (PointF)  
- **p3** (PointF)  
- **p4** (PointF)  
- **pen** (object)  


---

#### DrawBezierTo

**DrawBezierTo**(**p2**: PointF, **p3**: PointF, **p4**: PointF, **pen**: object): void

**Parameters**

- **p2** (PointF)  
- **p3** (PointF)  
- **p4** (PointF)  
- **pen** (object)  


---

#### DrawEllipse

**DrawEllipse**(**rect**: RectangleF, **pen**: object): void

**Parameters**

- **rect** (RectangleF)  
- **pen** (object)  


---

#### DrawImage

**DrawImage**(**img**: [Image](../../Stimulsoft_Drawing/root/Image.md), **rect**: RectangleF): void

**Parameters**

- **img** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **rect** (RectangleF)  


---

#### DrawLine

**DrawLine**(**pointFrom**: PointF, **pointTo**: PointF, **pen**: object): void

**Parameters**

- **pointFrom** (PointF)  
- **pointTo** (PointF)  
- **pen** (object)  


---

#### DrawLineTo

**DrawLineTo**(**pointTo**: PointF, **pen**: object): void

**Parameters**

- **pointTo** (PointF)  
- **pen** (object)  


---

#### DrawPie

**DrawPie**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### DrawPolygon

**DrawPolygon**(****: PointFpoints, **pen**: object): void

**Parameters**

- **** (PointFpoints)  
- **pen** (object)  


---

#### DrawPolyline

**DrawPolyline**(****: PointFpoints, **pen**: object): void

**Parameters**

- **** (PointFpoints)  
- **pen** (object)  

---

**DrawPolyline**(****: PointFpoints, **pen**: object, **close**: bool, **drawTo**: bool): void

**Parameters**

- **** (PointFpoints)  
- **pen** (object)  
- **close** (bool)  
- **drawTo** (bool)  


---

#### DrawPolylineTo

**DrawPolylineTo**(****: PointFpoints, **pen**: object): void

**Parameters**

- **** (PointFpoints)  
- **pen** (object)  


---

#### DrawRectangle

**DrawRectangle**(**rect**: RectangleF, **pen**: object, **corners**: StiCornerRadius): void

**Parameters**

- **rect** (RectangleF)  
- **pen** (object)  
- **corners** (StiCornerRadius)  


---

#### DrawSpline

**DrawSpline**(****: PointFpoints, **tension**: float, **pen**: object): void

**Parameters**

- **** (PointFpoints)  
- **tension** (float)  
- **pen** (object)  


---

#### DrawString

**DrawString**(**st**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md), **allowHtmlTags**: bool): void

**Parameters**

- **st** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md))  
- **allowHtmlTags** (bool)  


---

#### DrawText

**DrawText**(**basePoint**: PointF, **text**: string, ****: intcharsOffset, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **textColor**: Color, **angle**: float, **textAlign**: [EmfTextAlignmentMode](EmfTextAlignmentMode.md)): void

**Parameters**

- **basePoint** (PointF)  
- **text** (string)  
- **** (intcharsOffset)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **textColor** (Color)  
- **angle** (float)  
- **textAlign** ([EmfTextAlignmentMode](EmfTextAlignmentMode.md))  


---

#### EndPath

**EndPath**(): void


---

#### FillEllipse

**FillEllipse**(**rect**: RectangleF, **brush**: object): void

**Parameters**

- **rect** (RectangleF)  
- **brush** (object)  


---

#### FillPath

**FillPath**(**brush**: object): void

**Parameters**

- **brush** (object)  


---

#### FillPolygon

**FillPolygon**(****: PointFpoints, **brush**: object): void

**Parameters**

- **** (PointFpoints)  
- **brush** (object)  


---

#### FillPolygons

**FillPolygons**(**points**: List<List<PointF>>, **brush**: object): void

**Parameters**

- **points** (List<List<PointF>>)  
- **brush** (object)  


---

#### FillRectangle

**FillRectangle**(**rect**: RectangleF, **color**: Color, **corners**: StiCornerRadius): void

**Parameters**

- **rect** (RectangleF)  
- **color** (Color)  
- **corners** (StiCornerRadius)  

---

**FillRectangle**(**rect**: RectangleF, **brush**: object, **corners**: StiCornerRadius): void

**Parameters**

- **rect** (RectangleF)  
- **brush** (object)  
- **corners** (StiCornerRadius)  


---

#### MeasureString

**MeasureString**(**st**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): SizeF

**Parameters**

- **st** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  

**Returns** SizeF


---

#### MoveTo

**MoveTo**(**point**: PointF): void

**Parameters**

- **point** (PointF)  


---

#### RestoreState

**RestoreState**(): void


---

#### RotateTransform

**RotateTransform**(**angle**: float): void

**Parameters**

- **angle** (float)  

---

**RotateTransform**(**angle**: float, **x**: float, **y**: float): void

**Parameters**

- **angle** (float)  
- **x** (float)  
- **y** (float)  


---

#### SaveState

**SaveState**(): void


---

#### ScaleTransform

**ScaleTransform**(**scaleX**: float, **scaleY**: float): void

**Parameters**

- **scaleX** (float)  
- **scaleY** (float)  


---

#### SetBrush

**SetBrush**(**brush**: object, **rect**: RectangleF, **isTransparent**: bool, **saveState**: bool): bool

**Parameters**

- **brush** (object)  
- **rect** (RectangleF)  
- **isTransparent** (bool)  
- **saveState** (bool)  

**Returns** bool


---

#### SetClip

**SetClip**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### SetClipPath

**SetClipPath**(): void


---

#### SetPen

**SetPen**(**objPen**: object, **saveState**: bool, **forceThin**: bool): bool

**Parameters**

- **objPen** (object)  
- **saveState** (bool)  
- **forceThin** (bool)  

**Returns** bool


---

#### SetPixel

**SetPixel**(**point**: PointF, **color**: Color): void

**Parameters**

- **point** (PointF)  
- **color** (Color)  


---

#### StrokePath

**StrokePath**(**pen**: object): void

**Parameters**

- **pen** (object)  


---

#### TranslateTransform

**TranslateTransform**(**x**: float, **y**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  

