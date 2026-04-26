---
title: "StiGradientBrush Class"
---

## StiGradientBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [StiBrush](StiBrush.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGradientBrush**() | Creates a new instance of the StiGradientBrush class. |
| **StiGradientBrush**(Color startColor, Color endColor, double angle) | Creates a new instance of the StiGradientBrush class. |

**StiGradientBrush**()

Creates a new instance of the StiGradientBrush class.

---

**StiGradientBrush**(**startColor**: Color, **endColor**: Color, **angle**: double)

Creates a new instance of the StiGradientBrush class.

**Parameters**

- **startColor** (Color) — the starting color for the gradient.  
- **endColor** (Color) — The ending color for the gradient.  
- **angle** (double) — The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Angle** | double |  |
| **EndColor** | Color |  |
| **StartColor** | Color |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** *(+1 overloads)* | bool |  |
| **GetHashCode** | int |  |
| **LoadValuesFromJson** | void |  |

---

### Method Details

#### Equals

**Equals**(**other**: [StiGradientBrush](StiGradientBrush.md)): bool

**Parameters**

- **other** ([StiGradientBrush](StiGradientBrush.md))  

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

