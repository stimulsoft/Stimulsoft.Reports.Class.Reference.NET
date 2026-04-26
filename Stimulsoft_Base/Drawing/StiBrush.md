---
title: "StiBrush Class"
---

## StiBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Implements: ICloneable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Ident** | [StiBrushIdent](StiBrushIdent.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Dark** `static` | [StiBrush](StiBrush.md) |  |
| **Equals** | bool |  |
| **GetBrush** `static` *(+2 overloads)* | [Brush](../../Stimulsoft_Drawing/root/Brush.md) | Returns the gdi brush from the report brush. |
| **GetHashCode** | int |  |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **IsEmpty** `static` | bool | Returns true if this brush is empty - brush is null or StiEmptyBrush. |
| **IsTransparent** `static` | bool | Returns true if this brush is transparent - brush is null, empty or solid and color is transparent. |
| **Light** `static` | [StiBrush](StiBrush.md) |  |
| **LoadFromJson** `static` | [StiBrush](StiBrush.md) |  |
| **ToColor** `static` | Color | Transform a brush into a color. |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Dark `static`

**Dark**(**baseBrush**: [StiBrush](StiBrush.md), **value**: byte): [StiBrush](StiBrush.md)

**Parameters**

- **baseBrush** ([StiBrush](StiBrush.md))  
- **value** (byte)  

**Returns** [StiBrush](StiBrush.md)


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetBrush `static`

**GetBrush**(**brush**: [StiBrush](StiBrush.md), **rect**: Rectangle): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Returns the gdi brush from the report brush.

**Parameters**

- **brush** ([StiBrush](StiBrush.md)) — Report brush.  
- **rect** (Rectangle) — Rectangle for gradient.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — Gdi brush.

---

**GetBrush**(**brush**: [StiBrush](StiBrush.md), **rect**: RectangleF): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Returns the gdi brush from the report brush.

**Parameters**

- **brush** ([StiBrush](StiBrush.md)) — Report brush.  
- **rect** (RectangleF) — Rectangle for gradient.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — Gdi brush.

---

**GetBrush**(**brush**: [StiBrush](StiBrush.md), **rect**: [RectangleD](RectangleD.md)): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

Returns the standard brush from the report brush.

**Parameters**

- **brush** ([StiBrush](StiBrush.md)) — Report brush.  
- **rect** ([RectangleD](RectangleD.md)) — Rectangle for gradient.  

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md) — Gdi brush.


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### GetImage

**GetImage**(**width**: int, **height**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **width** (int)  
- **height** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### IsEmpty `static`

**IsEmpty**(**brush**: [StiBrush](StiBrush.md)): bool

Returns true if this brush is empty - brush is null or StiEmptyBrush.

**Parameters**

- **brush** ([StiBrush](StiBrush.md))  

**Returns** bool


---

#### IsTransparent `static`

**IsTransparent**(**brush**: [StiBrush](StiBrush.md)): bool

Returns true if this brush is transparent - brush is null, empty or solid and color is transparent.

**Parameters**

- **brush** ([StiBrush](StiBrush.md))  

**Returns** bool


---

#### Light `static`

**Light**(**baseBrush**: [StiBrush](StiBrush.md), **value**: byte): [StiBrush](StiBrush.md)

**Parameters**

- **baseBrush** ([StiBrush](StiBrush.md))  
- **value** (byte)  

**Returns** [StiBrush](StiBrush.md)


---

#### LoadFromJson `static`

**LoadFromJson**(**jObject**: [JObject](../Json/Linq/JObject.md)): [StiBrush](StiBrush.md)

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  

**Returns** [StiBrush](StiBrush.md)


---

#### ToColor `static`

**ToColor**(**brush**: [StiBrush](StiBrush.md)): Color

Transform a brush into a color.

**Parameters**

- **brush** ([StiBrush](StiBrush.md)) — Brush for converting.  

**Returns** Color — Converted color.

