---
title: "StiDrawing Class"
---

## StiDrawing Class

**Namespace:** `Stimulsoft.Base.Drawing`

Class contains statistical methods for drawing.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawLine** `static` *(+1 overloads)* | void |  |
| **DrawPath** `static` | void | Draws a graphical path specified by a GraphicsPath structure. |
| **DrawRectangle** `static` *(+5 overloads)* | void | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| **DrawRoundedRactangle** `static` | void | Draws a rounded rectangle specified by a RectangleF structure. |
| **DrawSelectedPoint** `static` | void | Draws a selected point specified by a coordinate pair. |
| **DrawSelectedRectangle** `static` | void | Draws a selected rectangle specified by a Rectangle structure. |
| **DrawString** `static` *(+5 overloads)* | void | Draws a string with a specified parameters. |
| **FillEllipse** `static` *(+3 overloads)* | void | Fills the interior of an ellipse specified by a RectangleD structure. |
| **FillPath** `static` *(+1 overloads)* | void | Fills the interior of a graphical path specified by a GraphicsPath structure. |
| **FillRectangle** `static` *(+9 overloads)* | void | Fills the interior of a rectangle specified by a pair of coordinates, a width, and a height. |
| **FillRoundedRactangle** `static` | void | Fills the interior of a rectangle specified by a RectangleF structure. |

---

### Method Details

#### DrawLine `static`

**DrawLine**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **x1**: double, **y1**: double, **x2**: double, **y2**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md))  
- **x1** (double)  
- **y1** (double)  
- **x2** (double)  
- **y2** (double)  

---

**DrawLine**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **x1**: double, **y1**: double, **x2**: double, **y2**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **color** (Color)  
- **x1** (double)  
- **y1** (double)  
- **x2** (double)  
- **y2** (double)  


---

#### DrawPath `static`

**DrawPath**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **path**: [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md), **width**: float): void

Draws a graphical path specified by a GraphicsPath structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — color to draw RectangleF.  
- **path** ([GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)) — A GraphicsPath structure that represents the path to draw.  
- **width** (float)  


---

#### DrawRectangle `static`

**DrawRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **x**: double, **y**: double, **width**: double, **height**: double): void

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to draw Rectangle.  
- **x** (double) — The x-coordinate of the upper-left corner of the rectangle to draw.  
- **y** (double) — The y-coordinate of the upper-left corner of the rectangle to draw.  
- **width** (double) — The width of the rectangle to draw.  
- **height** (double) — The height of the rectangle to draw.  

---

**DrawRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: [RectangleD](RectangleD.md)): void

Draws a rectangle specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to draw Rectangle.  
- **rect** ([RectangleD](RectangleD.md)) — A Rectangle structure that represents the rectangle to draw.  

---

**DrawRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: RectangleF): void

Draws a rectangle specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to draw RectangleF.  
- **rect** (RectangleF) — A Rectangle structure that represents the rectangle to draw.  

---

**DrawRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: Rectangle): void

Draws a rectangle specified by a Rectangle structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to draw Rectangle.  
- **rect** (Rectangle) — A Rectangle structure that represents the rectangle to draw.  

---

**DrawRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **x**: double, **y**: double, **width**: double, **height**: double): void

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md)) — A Pen object that determines the color, width, and style of the rectangle.  
- **x** (double) — The x-coordinate of the upper-left corner of the rectangle to draw.  
- **y** (double) — The y-coordinate of the upper-left corner of the rectangle to draw.  
- **width** (double) — The width of the rectangle to draw.  
- **height** (double) — The height of the rectangle to draw.  

---

**DrawRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **rect**: [RectangleD](RectangleD.md)): void

Draws a rectangle specified by a Rectangle structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md)) — A Pen object that determines the color, width, and style of the rectangle.  
- **rect** ([RectangleD](RectangleD.md)) — A Rectangle structure that represents the rectangle to draw.  


---

#### DrawRoundedRactangle `static`

**DrawRoundedRactangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **color**: Color, **scale**: double, **antiAlias**: bool): void

Draws a rounded rectangle specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics to draw on.  
- **rect** (RectangleF) — RectangleF structure that represents the rectangle to draw.  
- **color** (Color) — Color to draw.  
- **scale** (double) — Scale factor for the rounded corners.  
- **antiAlias** (bool) — Indicates whether to use anti-aliasing.  


---

#### DrawSelectedPoint `static`

**DrawSelectedPoint**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **size**: float, **brush**: [Brush](../../Stimulsoft_Drawing/root/Brush.md), **x**: double, **y**: double): void

Draws a selected point specified by a coordinate pair.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **size** (float) — The size of selected point.  
- **brush** ([Brush](../../Stimulsoft_Drawing/root/Brush.md)) — Brush to draw selected point.  
- **x** (double) — x-coordinate of selected point.  
- **y** (double) — y-coordinate of selected point  


---

#### DrawSelectedRectangle `static`

**DrawSelectedRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **size**: int, **brush**: [Brush](../../Stimulsoft_Drawing/root/Brush.md), **rect**: [RectangleD](RectangleD.md)): void

Draws a selected rectangle specified by a Rectangle structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **size** (int) — The size of selected point.  
- **brush** ([Brush](../../Stimulsoft_Drawing/root/Brush.md)) — Brush to draw selected point.  
- **rect** ([RectangleD](RectangleD.md)) — RectangleD structure that represents the rectangle to draw selections.  


---

#### DrawString `static`

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **color**: Color, **rect**: Rectangle, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

Draws a string with a specified parameters.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **text** (string) — The text for drawing.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — The font which uses to draw text.  
- **color** (Color) — The color to draw selected point.  
- **rect** (Rectangle) — The RectangleD structure that represents the rectangle to draw selections.  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — The string format which uses to draw text.  

---

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **brush**: [StiBrush](StiBrush.md), **rect**: [RectangleD](RectangleD.md), **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

Draws a string with a specified parameters.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **text** (string) — The text for drawing.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — The font which uses to draw text.  
- **brush** ([StiBrush](StiBrush.md)) — The Brush to draw text.  
- **rect** ([RectangleD](RectangleD.md)) — The RectangleD structure that represents the rectangle to draw selections.  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — The string format which uses to draw text.  

---

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **color**: Color, **rect**: [RectangleD](RectangleD.md), **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

Draws a string with a specified parameters.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **text** (string) — The text for drawing.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — The font which uses to draw text.  
- **color** (Color) — The color to draw text.  
- **rect** ([RectangleD](RectangleD.md)) — The RectangleD structure that represents the rectangle to draw selections.  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — The string format which uses to draw text.  

---

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **color**: Color, **rect**: RectangleF, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

Draws a string with a specified parameters.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **text** (string) — The text for drawing.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — The font which uses to draw text.  
- **color** (Color) — The color to draw text.  
- **rect** (RectangleF) — The RectangleF structure that represents the rectangle to draw selections.  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — The string format which uses to draw text.  

---

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **brush**: [StiBrush](StiBrush.md), **rect**: Rectangle, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

Draws a string with a specified parameters.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **text** (string) — The text for drawing.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — The font which uses to draw text.  
- **brush** ([StiBrush](StiBrush.md)) — The Brush to draw text.  
- **rect** (Rectangle) — The RectangleD structure that represents the rectangle to draw selections.  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — The string format which uses to draw text.  

---

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **brush**: [StiBrush](StiBrush.md), **rect**: RectangleF, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

Draws a string with a specified parameters.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **text** (string) — The text for drawing.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — The font which uses to draw text.  
- **brush** ([StiBrush](StiBrush.md)) — The Brush to draw text.  
- **rect** (RectangleF) — The RectangleD structure that represents the rectangle to draw selections.  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — The string format which uses to draw text.  


---

#### FillEllipse `static`

**FillEllipse**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: [RectangleD](RectangleD.md)): void

Fills the interior of an ellipse specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to fill.  
- **rect** ([RectangleD](RectangleD.md)) — RectangleD structure that represents the ellipse to fill.  

---

**FillEllipse**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: RectangleF): void

Fills the interior of an ellipse specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to fill.  
- **rect** (RectangleF) — RectangleF structure that represents the ellipse to fill.  

---

**FillEllipse**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [Brush](../../Stimulsoft_Drawing/root/Brush.md), **rect**: RectangleF): void

Fills the interior of an ellipse specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([Brush](../../Stimulsoft_Drawing/root/Brush.md)) — Brush object that determines the characteristics of the fill.  
- **rect** (RectangleF) — RectangleD structure that represents the ellipse to fill.  

---

**FillEllipse**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [StiBrush](StiBrush.md), **rect**: RectangleF): void

Fills the interior of an ellipse specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([StiBrush](StiBrush.md)) — StiBrush object that determines the characteristics of the fill.  
- **rect** (RectangleF) — RectangleD structure that represents the ellipse to fill.  


---

#### FillPath `static`

**FillPath**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **path**: [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)): void

Fills the interior of a graphical path specified by a GraphicsPath structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — A color object that determines the characteristics of the fill.  
- **path** ([GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)) — GraphicsPath structure that represents the path to fill.  

---

**FillPath**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [StiBrush](StiBrush.md), **path**: [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)): void

Fills the interior of a graphical path specified by a GraphicsPath structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([StiBrush](StiBrush.md)) — A brush object that determines the characteristics of the fill.  
- **path** ([GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)) — GraphicsPath structure that represents the path to fill.  


---

#### FillRectangle `static`

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **x**: double, **y**: double, **width**: double, **height**: double): void

Fills the interior of a rectangle specified by a pair of coordinates, a width, and a height.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to fill.  
- **x** (double) — x-coordinate of the upper-left corner of the rectangle to fill.  
- **y** (double) — y-coordinate of the upper-left corner of the rectangle to fill.  
- **width** (double) — Width of the rectangle to fill.  
- **height** (double) — Height of the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: [RectangleD](RectangleD.md)): void

Fills the interior of a rectangle specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to fill.  
- **rect** ([RectangleD](RectangleD.md)) — RectangleD structure that represents the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: RectangleF): void

Fills the interior of a rectangle specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color to fill.  
- **rect** (RectangleF) — RectangleD structure that represents the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [StiBrush](StiBrush.md), **x**: double, **y**: double, **width**: double, **height**: double): void

Fills the interior of a rectangle specified by a pair of coordinates, a width, and a height.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([StiBrush](StiBrush.md)) — StiBrush object that determines the characteristics of the fill.  
- **x** (double) — x-coordinate of the upper-left corner of the rectangle to fill.  
- **y** (double) — y-coordinate of the upper-left corner of the rectangle to fill.  
- **width** (double) — Width of the rectangle to fill.  
- **height** (double) — Height of the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [StiBrush](StiBrush.md), **rect**: [RectangleD](RectangleD.md)): void

Fills the interior of a rectangle specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([StiBrush](StiBrush.md)) — StiBrush object that determines the characteristics of the fill.  
- **rect** ([RectangleD](RectangleD.md)) — RectangleD structure that represents the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [StiBrush](StiBrush.md), **rect**: RectangleF): void

Fills the interior of a rectangle specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([StiBrush](StiBrush.md)) — StiBrush object that determines the characteristics of the fill.  
- **rect** (RectangleF) — RectangleD structure that represents the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [Brush](../../Stimulsoft_Drawing/root/Brush.md), **x**: double, **y**: double, **width**: double, **height**: double): void

Fills the interior of a rectangle specified by a pair of coordinates, a width, and a height.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([Brush](../../Stimulsoft_Drawing/root/Brush.md)) — Brush object that determines the characteristics of the fill.  
- **x** (double) — x-coordinate of the upper-left corner of the rectangle to fill.  
- **y** (double) — y-coordinate of the upper-left corner of the rectangle to fill.  
- **width** (double) — Width of the rectangle to fill.  
- **height** (double) — Height of the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [Brush](../../Stimulsoft_Drawing/root/Brush.md), **rect**: [RectangleD](RectangleD.md)): void

Fills the interior of a rectangle specified by a RectangleD structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([Brush](../../Stimulsoft_Drawing/root/Brush.md)) — Brush object that determines the characteristics of the fill.  
- **rect** ([RectangleD](RectangleD.md)) — RectangleD structure that represents the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **brush**: [Brush](../../Stimulsoft_Drawing/root/Brush.md), **rect**: RectangleF): void

Fills the interior of a rectangle specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **brush** ([Brush](../../Stimulsoft_Drawing/root/Brush.md)) — Brush object that determines the characteristics of the fill.  
- **rect** (RectangleF) — RectangleD structure that represents the rectangle to fill.  

---

**FillRectangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **color**: Color, **rect**: Rectangle): void

Fills the interior of a rectangle specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **color** (Color) — Color object that determines the characteristics of the fill.  
- **rect** (Rectangle) — Rectangle structure that represents the rectangle to fill.  


---

#### FillRoundedRactangle `static`

**FillRoundedRactangle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **color**: Color, **scale**: double, **antiAlias**: bool): void

Fills the interior of a rectangle specified by a RectangleF structure.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics to draw on.  
- **rect** (RectangleF) — RectangleF structure that represents the rectangle to fill.  
- **color** (Color) — Color to fill.  
- **scale** (double) — Scale factor for the rounded corners.  
- **antiAlias** (bool) — Indicates whether to use anti-aliasing.  

