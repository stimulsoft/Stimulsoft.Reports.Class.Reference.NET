---
title: "StiHatchBrush Class"
---

## StiHatchBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [StiBrush](StiBrush.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHatchBrush**() | Creates a new instance of the StiHatchBrush class. |
| **StiHatchBrush**(HatchStyle style, Color foreColor, Color backColor) | Creates a new instance of the StiHatchBrush class. |

**StiHatchBrush**()

Creates a new instance of the StiHatchBrush class.

---

**StiHatchBrush**(**style**: HatchStyle, **foreColor**: Color, **backColor**: Color)

Creates a new instance of the StiHatchBrush class.

**Parameters**

- **style** (HatchStyle) — Hatch style of this StiHatchBrush object.  
- **foreColor** (Color) — The color of hatch lines drawn by this StiHatchBrush object.  
- **backColor** (Color) — The color of spaces between the hatch lines drawn by this StiHatchBrush object.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BackColor** | Color |  |
| **ForeColor** | Color |  |
| **Style** | HatchStyle |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** *(+1 overloads)* | bool |  |
| **GetHashCode** | int |  |
| **LoadValuesFromJson** | void |  |

---

### Method Details

#### Equals

**Equals**(**other**: [StiHatchBrush](StiHatchBrush.md)): bool

**Parameters**

- **other** ([StiHatchBrush](StiHatchBrush.md))  

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

#### LoadValuesFromJson

**LoadValuesFromJson**(**jObject**: [JObject](../Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../Json/Linq/JObject.md))  

