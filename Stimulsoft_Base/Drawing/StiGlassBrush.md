---
title: "StiGlassBrush Class"
---

## StiGlassBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [StiBrush](StiBrush.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGlassBrush**() | Creates a new instance of the StiGlassBrush class. |
| **StiGlassBrush**(Color color, bool drawHatch, float blend) | Creates a new instance of the StiGlassBrush class. |

**StiGlassBrush**()

Creates a new instance of the StiGlassBrush class.

---

**StiGlassBrush**(**color**: Color, **drawHatch**: bool, **blend**: float)

Creates a new instance of the StiGlassBrush class.

**Parameters**

- **color** (Color) — A color of this StiGlassBrush object.  
- **drawHatch** (bool)  
- **blend** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **DrawHatch** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **Equals** *(+1 overloads)* | bool |  |
| **GetBottomBrush** | [Brush](../../Stimulsoft_Drawing/root/Brush.md) |  |
| **GetBottomColor** | Color |  |
| **GetBottomColorLight** | Color |  |
| **GetBottomRectangle** | RectangleF |  |
| **GetHashCode** | int |  |
| **GetTopBrush** | [Brush](../../Stimulsoft_Drawing/root/Brush.md) |  |
| **GetTopColor** | Color |  |
| **GetTopColorLight** | Color |  |
| **GetTopRectangle** | RectangleF |  |
| **LoadValuesFromJson** | void |  |

---

### Method Details

#### Draw

**Draw**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  


---

#### Equals

**Equals**(**other**: [StiGlassBrush](StiGlassBrush.md)): bool

**Parameters**

- **other** ([StiGlassBrush](StiGlassBrush.md))  

**Returns** bool

---

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetBottomBrush

**GetBottomBrush**(): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md)


---

#### GetBottomColor

**GetBottomColor**(): Color

**Returns** Color


---

#### GetBottomColorLight

**GetBottomColorLight**(): Color

**Returns** Color


---

#### GetBottomRectangle

**GetBottomRectangle**(**rect**: RectangleF): RectangleF

**Parameters**

- **rect** (RectangleF)  

**Returns** RectangleF


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### GetTopBrush

**GetTopBrush**(): [Brush](../../Stimulsoft_Drawing/root/Brush.md)

**Returns** [Brush](../../Stimulsoft_Drawing/root/Brush.md)


---

#### GetTopColor

**GetTopColor**(): Color

**Returns** Color


---

#### GetTopColorLight

**GetTopColorLight**(): Color

**Returns** Color


---

#### GetTopRectangle

**GetTopRectangle**(**rect**: RectangleF): RectangleF

**Parameters**

- **rect** (RectangleF)  

**Returns** RectangleF


---

#### LoadValuesFromJson

**LoadValuesFromJson**(**jObject**: [JObject](../Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  

