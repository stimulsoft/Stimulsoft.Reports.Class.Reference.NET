---
title: "StiAlignValue Class"
---

## StiAlignValue Class

**Namespace:** `Stimulsoft.Base`

Helps to aligning values.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AlignToGrid** `static` | double | Aligning value on grid. |
| **AlignToMaxGrid** `static` *(+1 overloads)* | double | Aligning value on grid to greater. |
| **AlignToMinGrid** `static` | double | Aligning value on grid to less. |

---

### Method Details

#### AlignToGrid `static`

**AlignToGrid**(**value**: double, **gridSize**: double, **aligningToGrid**: bool): double

Aligning value on grid.

**Parameters**

- **value** (double) — Value to align.  
- **gridSize** (double) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** double — Aligned value.


---

#### AlignToMaxGrid `static`

**AlignToMaxGrid**(**value**: double, **gridSize**: double, **aligningToGrid**: bool): double

Aligning value on grid to greater.

**Parameters**

- **value** (double) — Value to align.  
- **gridSize** (double) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** double — Aligned value.

---

**AlignToMaxGrid**(**value**: decimal, **gridSize**: decimal, **aligningToGrid**: bool): decimal

Aligning value on grid to greater.

**Parameters**

- **value** (decimal) — Value to align.  
- **gridSize** (decimal) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** decimal — Aligned value.


---

#### AlignToMinGrid `static`

**AlignToMinGrid**(**value**: double, **gridSize**: double, **aligningToGrid**: bool): double

Aligning value on grid to less.

**Parameters**

- **value** (double) — Value to align.  
- **gridSize** (double) — Grid size.  
- **aligningToGrid** (bool) — Align or no.  

**Returns** double — Aligned value.

