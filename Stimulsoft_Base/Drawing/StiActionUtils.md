---
title: "StiActionUtils Class"
---

## StiActionUtils Class

**Namespace:** `Stimulsoft.Base.Drawing`

Describes a class that contains methods which serve for operation with a rectangle and cursor.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **PointInEdge** `static` | bool | Checks is this point gets into the specified corner. |
| **PointInRect** `static` *(+1 overloads)* | bool | Checks does the point fit into the position. |

---

### Method Details

#### PointInEdge `static`

**PointInEdge**(**x**: double, **y**: double, **point**: [PointD](PointD.md), **size**: double): bool

Checks is this point gets into the specified corner.

**Parameters**

- **x** (double) — X point.  
- **y** (double) — Y point.  
- **point** ([PointD](PointD.md)) — Angle coordinates.  
- **size** (double) — Tolerable limit size.  

**Returns** bool — True, if is this point gets into the specified corner, and false, if not.


---

#### PointInRect `static`

**PointInRect**(**x**: float, **y**: float, **rect**: RectangleF): bool

Checks does the point fit into the position.

**Parameters**

- **x** (float) — X point.  
- **y** (float) — Y point.  
- **rect** (RectangleF)  

**Returns** bool — true, if the point fits to the position, and false, if not.

---

**PointInRect**(**x**: double, **y**: double, **rect**: [RectangleD](RectangleD.md)): bool

Checks does the point fit into the position.

**Parameters**

- **x** (double) — X point.  
- **y** (double) — Y point.  
- **rect** ([RectangleD](RectangleD.md))  

**Returns** bool — true, if the point fits to the position, and false, if not.

