---
title: "GraphicsPath Class"
---

## GraphicsPath Class

**Namespace:** `Stimulsoft.Drawing.Drawing2D`

### Inheritance

Implements: ICloneable, IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **GraphicsPath**() |  |
| **GraphicsPath**(FillMode fillMode) |  |

**GraphicsPath**()

---

**GraphicsPath**(**fillMode**: FillMode)

**Parameters**

- **fillMode** (FillMode)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddArc** *(+1 overloads)* | void |  |
| **AddBezier** *(+1 overloads)* | void |  |
| **AddBeziers** | void |  |
| **AddCurve** | void |  |
| **AddEllipse** *(+1 overloads)* | void |  |
| **AddLine** *(+2 overloads)* | void |  |
| **AddLines** *(+1 overloads)* | void |  |
| **AddPath** | void |  |
| **AddPie** *(+2 overloads)* | void |  |
| **AddPolygon** *(+1 overloads)* | void |  |
| **AddRectangle** | void |  |
| **AddString** *(+2 overloads)* | void |  |
| **Clone** | object |  |
| **CloseAllFigures** | void |  |
| **CloseFigure** | void |  |
| **Dispose** | void |  |
| **Flatten** | void |  |
| **GetBounds** | RectangleF |  |
| **GetLastPoint** | PointF |  |
| **IsVisible** *(+1 overloads)* | bool |  |
| **Reset** | void |  |
| **StartFigure** | void |  |
| **Transform** | void |  |

---

### Method Details

#### AddArc

**AddArc**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  

---

**AddArc**(**x**: float, **y**: float, **width**: float, **height**: float, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### AddBezier

**AddBezier**(**pt1**: PointF, **pt2**: PointF, **pt3**: PointF, **pt4**: PointF): void

**Parameters**

- **pt1** (PointF)  
- **pt2** (PointF)  
- **pt3** (PointF)  
- **pt4** (PointF)  

---

**AddBezier**(**x1**: float, **y1**: float, **x2**: float, **y2**: float, **x3**: float, **y3**: float, **x4**: float, **y4**: float): void

**Parameters**

- **x1** (float)  
- **y1** (float)  
- **x2** (float)  
- **y2** (float)  
- **x3** (float)  
- **y3** (float)  
- **x4** (float)  
- **y4** (float)  


---

#### AddBeziers

**AddBeziers**(****: PointFpoints): void

**Parameters**

- **** (PointFpoints)  


---

#### AddCurve

**AddCurve**(****: PointFpoints, **tension**: float): void

**Parameters**

- **** (PointFpoints)  
- **tension** (float)  


---

#### AddEllipse

**AddEllipse**(**x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  

---

**AddEllipse**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### AddLine

**AddLine**(**pt1**: PointF, **pt2**: PointF): void

**Parameters**

- **pt1** (PointF)  
- **pt2** (PointF)  

---

**AddLine**(**x1**: int, **y1**: int, **x2**: int, **y2**: int): void

**Parameters**

- **x1** (int)  
- **y1** (int)  
- **x2** (int)  
- **y2** (int)  

---

**AddLine**(**x1**: float, **y1**: float, **x2**: float, **y2**: float): void

**Parameters**

- **x1** (float)  
- **y1** (float)  
- **x2** (float)  
- **y2** (float)  


---

#### AddLines

**AddLines**(****: Pointpoints): void

**Parameters**

- **** (Pointpoints)  

---

**AddLines**(****: PointFpoints): void

**Parameters**

- **** (PointFpoints)  


---

#### AddPath

**AddPath**(**addingPath**: [GraphicsPath](GraphicsPath.md), **connect**: bool): void

**Parameters**

- **addingPath** ([GraphicsPath](GraphicsPath.md))  
- **connect** (bool)  


---

#### AddPie

**AddPie**(**rect**: Rectangle, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **rect** (Rectangle)  
- **startAngle** (float)  
- **sweepAngle** (float)  

---

**AddPie**(**rect**: RectangleF, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **rect** (RectangleF)  
- **startAngle** (float)  
- **sweepAngle** (float)  

---

**AddPie**(**x**: float, **y**: float, **width**: float, **height**: float, **startAngle**: float, **sweepAngle**: float): void

**Parameters**

- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  
- **startAngle** (float)  
- **sweepAngle** (float)  


---

#### AddPolygon

**AddPolygon**(****: Pointpoints): void

**Parameters**

- **** (Pointpoints)  

---

**AddPolygon**(****: PointFpoints): void

**Parameters**

- **** (PointFpoints)  


---

#### AddRectangle

**AddRectangle**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### AddString

**AddString**(**s**: string, **family**: [FontFamily](../root/FontFamily.md), **style**: int, **emSize**: float, **origin**: PointF, **format**: [StringFormat](../root/StringFormat.md)): void

**Parameters**

- **s** (string)  
- **family** ([FontFamily](../root/FontFamily.md))  
- **style** (int)  
- **emSize** (float)  
- **origin** (PointF)  
- **format** ([StringFormat](../root/StringFormat.md))  

---

**AddString**(**s**: string, **family**: [FontFamily](../root/FontFamily.md), **style**: int, **emSize**: float, **layoutRectangle**: Rectangle, **format**: [StringFormat](../root/StringFormat.md)): void

**Parameters**

- **s** (string)  
- **family** ([FontFamily](../root/FontFamily.md))  
- **style** (int)  
- **emSize** (float)  
- **layoutRectangle** (Rectangle)  
- **format** ([StringFormat](../root/StringFormat.md))  

---

**AddString**(**s**: string, **family**: [FontFamily](../root/FontFamily.md), **style**: int, **emSize**: float, **layoutRectangle**: RectangleF, **format**: [StringFormat](../root/StringFormat.md)): void

**Parameters**

- **s** (string)  
- **family** ([FontFamily](../root/FontFamily.md))  
- **style** (int)  
- **emSize** (float)  
- **layoutRectangle** (RectangleF)  
- **format** ([StringFormat](../root/StringFormat.md))  


---

#### Clone

**Clone**(): object

**Returns** object


---

#### CloseAllFigures

**CloseAllFigures**(): void


---

#### CloseFigure

**CloseFigure**(): void


---

#### Dispose

**Dispose**(): void


---

#### Flatten

**Flatten**(): void


---

#### GetBounds

**GetBounds**(): RectangleF

**Returns** RectangleF


---

#### GetLastPoint

**GetLastPoint**(): PointF

**Returns** PointF


---

#### IsVisible

**IsVisible**(**point**: PointF): bool

**Parameters**

- **point** (PointF)  

**Returns** bool

---

**IsVisible**(**x**: float, **y**: float): bool

**Parameters**

- **x** (float)  
- **y** (float)  

**Returns** bool


---

#### Reset

**Reset**(): void


---

#### StartFigure

**StartFigure**(): void


---

#### Transform

**Transform**(**matrix**: [Matrix](Matrix.md)): void

**Parameters**

- **matrix** ([Matrix](Matrix.md))  

