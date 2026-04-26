---
title: "StiAlignHelper Struct"
---

## StiAlignHelper Struct

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlignToGrid** `static` *(+2 overloads)* | double | Align a value to grid. |

---

### Method Details

#### AlignToGrid `static`

**AlignToGrid**(**value**: double, **gridSize**: double, **aligningToGrid**: bool): double

Align a value to grid.

**Parameters**

- **value** (double)  
- **gridSize** (double) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** double — Aligned rectangle.

---

**AlignToGrid**(**rect**: Rectangle, **gridSize**: int, **aligningToGrid**: bool): Rectangle

Align a rectangle to grid.

**Parameters**

- **rect** (Rectangle)  
- **gridSize** (int) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** Rectangle — Aligned rectangle.

---

**AlignToGrid**(**rect**: [RectangleD](RectangleD.md), **gridSize**: double, **aligningToGrid**: bool): [RectangleD](RectangleD.md)

Align the rectangle to grid.

**Parameters**

- **rect** ([RectangleD](RectangleD.md))  
- **gridSize** (double) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** [RectangleD](RectangleD.md) — Aligned rectangle.

