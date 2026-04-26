---
title: "StiRectangleUtils Class"
---

## StiRectangleUtils Class

**Namespace:** `Stimulsoft.Base.Drawing`

Helps works with Rectangle.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlignSizeInRect** `static` *(+1 overloads)* | [RectangleD](RectangleD.md) |  |
| **Convert** `static` | RectangleF | Converts Rectangle to RectangleF. |
| **FitToRectangle** `static` | Rectangle | Fits rectangles rect1 in rect2. |
| **Normalize** `static` | Rectangle | Normalizes (converts all negative importances). |

---

### Method Details

#### AlignSizeInRect `static`

**AlignSizeInRect**(**rect**: [RectangleD](RectangleD.md), **size**: [SizeD](SizeD.md), **alignment**: ContentAlignment): [RectangleD](RectangleD.md)

**Parameters**

- **rect** ([RectangleD](RectangleD.md))  
- **size** ([SizeD](SizeD.md))  
- **alignment** (ContentAlignment)  

**Returns** [RectangleD](RectangleD.md)

---

**AlignSizeInRect**(**rect**: [RectangleD](RectangleD.md), **size**: [SizeD](SizeD.md), **horAlignment**: [StiHorAlignment](StiHorAlignment.md), **vertAlignment**: [StiVertAlignment](StiVertAlignment.md)): [RectangleD](RectangleD.md)

**Parameters**

- **rect** ([RectangleD](RectangleD.md))  
- **size** ([SizeD](SizeD.md))  
- **horAlignment** ([StiHorAlignment](StiHorAlignment.md))  
- **vertAlignment** ([StiVertAlignment](StiVertAlignment.md))  

**Returns** [RectangleD](RectangleD.md)


---

#### Convert `static`

**Convert**(**rect**: Rectangle): RectangleF

Converts Rectangle to RectangleF.

**Parameters**

- **rect** (Rectangle)  

**Returns** RectangleF


---

#### FitToRectangle `static`

**FitToRectangle**(**rect1**: Rectangle, **rect2**: Rectangle): Rectangle

Fits rectangles rect1 in rect2.

**Parameters**

- **rect1** (Rectangle) — Rectangle rect1.  
- **rect2** (Rectangle) — Rectangle rect2.  

**Returns** Rectangle — Resulted Rectangle.


---

#### Normalize `static`

**Normalize**(**rect**: Rectangle): Rectangle

Normalizes (converts all negative importances).

**Parameters**

- **rect** (Rectangle) — Rectangle to normalize.  

**Returns** Rectangle — Normalized rectangle.

