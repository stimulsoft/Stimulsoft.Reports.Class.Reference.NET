---
title: "StiSolidBrush Class"
---

## StiSolidBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [StiBrush](StiBrush.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSolidBrush**() | Creates a new instance of the StiSolidBrush class. |
| **StiSolidBrush**(Color color) | Creates a new instance of the StiSolidBrush class. |
| **StiSolidBrush**(string color) | Creates a new instance of the StiSolidBrush class. |

**StiSolidBrush**()

Creates a new instance of the StiSolidBrush class.

---

**StiSolidBrush**(**color**: Color)

Creates a new instance of the StiSolidBrush class.

**Parameters**

- **color** (Color) — The color of this StiSolidBrush object.  

---

**StiSolidBrush**(**color**: string)

Creates a new instance of the StiSolidBrush class.

**Parameters**

- **color** (string) — A string representation of the color for that StiSolidBrush object.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** *(+1 overloads)* | bool |  |
| **GetHashCode** | int |  |
| **LoadValuesFromJson** | void |  |

---

### Method Details

#### Equals

**Equals**(**other**: [StiSolidBrush](StiSolidBrush.md)): bool

**Parameters**

- **other** ([StiSolidBrush](StiSolidBrush.md))  

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

