---
title: "StiGlareBrush Class"
---

## StiGlareBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [StiBrush](StiBrush.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGlareBrush**() | Creates a new instance of the StiGlareBrush class. |
| **StiGlareBrush**(Color startColor, Color endColor, double angle) | Creates a new instance of the StiGlareBrush class. |
| **StiGlareBrush**(Color startColor, Color endColor, double angle, float focus, float scale) | Creates a new instance of the StiGlareBrush class. |

**StiGlareBrush**()

Creates a new instance of the StiGlareBrush class.

---

**StiGlareBrush**(**startColor**: Color, **endColor**: Color, **angle**: double)

Creates a new instance of the StiGlareBrush class.

**Parameters**

- **startColor** (Color) — the starting color for the gradient.  
- **endColor** (Color) — The ending color for the gradient.  
- **angle** (double) — The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line.  

---

**StiGlareBrush**(**startColor**: Color, **endColor**: Color, **angle**: double, **focus**: float, **scale**: float)

Creates a new instance of the StiGlareBrush class.

**Parameters**

- **startColor** (Color) — the starting color for the gradient.  
- **endColor** (Color) — The ending color for the gradient.  
- **angle** (double) — The angle, measured in degrees clockwise from the x-axis, of the gradient's orientation line.  
- **focus** (float) — The value from 0 through 1 that specifies the center of the gradient (the point where the gradient is composed of only the ending color).  
- **scale** (float) — The value from 0 through 1 that specifies how fast the colors falloff from the focus.  


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

**Equals**(**other**: [StiGlareBrush](StiGlareBrush.md)): bool

**Parameters**

- **other** ([StiGlareBrush](StiGlareBrush.md))  

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

