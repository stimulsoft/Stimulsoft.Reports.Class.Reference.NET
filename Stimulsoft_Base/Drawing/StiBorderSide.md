---
title: "StiBorderSide Class"
---

## StiBorderSide Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBorderSide**() | Creates a new instance of the StiBorderSide class. |
| **StiBorderSide**(Color color, double size, [StiPenStyle](StiPenStyle.md) style) | Creates a new instance of the StiBorderSide class. |

**StiBorderSide**()

Creates a new instance of the StiBorderSide class.

---

**StiBorderSide**(**color**: Color, **size**: double, **style**: [StiPenStyle](StiPenStyle.md))

Creates a new instance of the StiBorderSide class.

**Parameters**

- **color** (Color) — Border color.  
- **size** (double) — Border size.  
- **style** ([StiPenStyle](StiPenStyle.md)) — Border style.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **Size** | double |  |
| **Style** | [StiPenStyle](StiPenStyle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** *(+1 overloads)* | bool |  |
| **GetHashCode** | int |  |
| **GetSizeOffset** | float |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Equals

**Equals**(**other**: [StiBorderSide](StiBorderSide.md)): bool

**Parameters**

- **other** ([StiBorderSide](StiBorderSide.md))  

**Returns** bool

---

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### GetSizeOffset

**GetSizeOffset**(): float

**Returns** float

