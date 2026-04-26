---
title: "StiSimpleBorder Class"
---

## StiSimpleBorder Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSimpleBorder**() | Creates a new instance of the StiSimpleBorder class. |
| **StiSimpleBorder**([StiBorderSides](StiBorderSides.md) side, Color color, double size, [StiPenStyle](StiPenStyle.md) style) | Creates a new instance of the StiSimpleBorder class. |

**StiSimpleBorder**()

Creates a new instance of the StiSimpleBorder class.

---

**StiSimpleBorder**(**side**: [StiBorderSides](StiBorderSides.md), **color**: Color, **size**: double, **style**: [StiPenStyle](StiPenStyle.md))

Creates a new instance of the StiSimpleBorder class.

**Parameters**

- **side** ([StiBorderSides](StiBorderSides.md)) — Border sides.  
- **color** (Color) — Border color.  
- **size** (double) — Border size.  
- **style** ([StiPenStyle](StiPenStyle.md)) — Border style.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **Side** | [StiBorderSides](StiBorderSides.md) |  |
| **Size** | double |  |
| **Style** | [StiPenStyle](StiPenStyle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Draw** *(+4 overloads)* | void | Draws this border on the indicated Graphics. |
| **Equals** | bool | Tests to see whether the specified object is a StiSimpleBorder with the same dimensions as this StiSimpleBorder. |
| **GetBorder** | StiBorder |  |
| **GetHashCode** | int | Returns a hash code for this StiPaddings structure. |
| **GetSizeOffset** | float |  |
| **LoadFromJson** | void |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Draw

**Draw**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](RectangleD.md), **zoom**: double): void

Draws this border on the indicated Graphics.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics on which a border can be drawn.  
- **rect** ([RectangleD](RectangleD.md)) — The rectangle that indicates an area of the border drawing.  
- **zoom** (double) — The scale of a border to draw.  

---

**Draw**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](RectangleD.md), **zoom**: double, **emptyColor**: Color): void

Draws this border on the indicated Graphics.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics on which a border can be drawn.  
- **rect** ([RectangleD](RectangleD.md)) — The rectangle that indicates an area of the border drawing.  
- **zoom** (double) — The scale of a border to draw.  
- **emptyColor** (Color) — The color of space between double lines (used only when border style equal Double).  

---

**Draw**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **zoom**: float): void

Draws this border on the indicated Graphics.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics on which a border can be drawn.  
- **rect** (RectangleF) — The rectangle that indicates an area of the border drawing.  
- **zoom** (float) — The scale of a border to draw.  

---

**Draw**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **zoom**: float, **emptyColor**: Color): void

Draws this border on the indicated Graphics.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics on which a border can be drawn.  
- **rect** (RectangleF) — The rectangle that indicates an area of the border drawing.  
- **zoom** (float) — The scale of a border to draw.  
- **emptyColor** (Color) — The color of space between double lines (used only when border style equal Double).  

---

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

**Equals**(**obj**: object): bool

Tests to see whether the specified object is a StiSimpleBorder with the same dimensions as this StiSimpleBorder.

**Parameters**

- **obj** (object) — The Object to test.  

**Returns** bool — This method returns true if obj is a StiSimpleBorder and has the same width and height as this StiSimpleBorder; otherwise, false.


---

#### GetBorder

**GetBorder**(): StiBorder

**Returns** StiBorder


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this StiPaddings structure.

**Returns** int — An integer value that specifies a hash value for this StiPaddings structure.


---

#### GetSizeOffset

**GetSizeOffset**(): float

**Returns** float


---

#### LoadFromJson

**LoadFromJson**(**jObject**: [JObject](../Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  

