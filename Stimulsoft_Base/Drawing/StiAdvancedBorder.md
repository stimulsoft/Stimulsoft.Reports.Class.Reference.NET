---
title: "StiAdvancedBorder Class"
---

## StiAdvancedBorder Class

**Namespace:** `Stimulsoft.Base.Drawing`

Class describes a multi-border.

### Inheritance

Inherits from: StiBorder  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAdvancedBorder**() | Creates a new instance of the StiAdvancedBorder class. |

**StiAdvancedBorder**()

Creates a new instance of the StiAdvancedBorder class.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BottomSide** | [StiBorderSide](StiBorderSide.md) |  |
| **LeftSide** | [StiBorderSide](StiBorderSide.md) |  |
| **RightSide** | [StiBorderSide](StiBorderSide.md) |  |
| **TopSide** | [StiBorderSide](StiBorderSide.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Draw** | void | Draws this border on the indicated Graphics. |
| **Equals** *(+1 overloads)* | bool |  |
| **GetHashCode** | int |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Draw

**Draw**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **zoom**: float, **emptyColor**: Color, **drawBorderFormatting**: bool, **drawBorderSides**: bool): void

Draws this border on the indicated Graphics.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics on which a border can be drawn.  
- **rect** (RectangleF) — The rectangle that indicates an area of the border drawing.  
- **zoom** (float) — The scale of a border to draw.  
- **emptyColor** (Color) — The color of space between double lines (used only when border style equal Double).  
- **drawBorderFormatting** (bool)  
- **drawBorderSides** (bool)  


---

#### Equals

**Equals**(**other**: [StiAdvancedBorder](StiAdvancedBorder.md)): bool

**Parameters**

- **other** ([StiAdvancedBorder](StiAdvancedBorder.md))  

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

