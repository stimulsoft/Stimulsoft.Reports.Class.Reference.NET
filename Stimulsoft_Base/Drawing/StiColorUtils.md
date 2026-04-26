---
title: "StiColorUtils Class"
---

## StiColorUtils Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ChangeAlpha** `static` | Color |  |
| **ChangeDarkness** `static` *(+1 overloads)* | Color |  |
| **ChangeLightness** `static` *(+1 overloads)* | Color |  |
| **Dark** `static` *(+1 overloads)* | Color |  |
| **GetColorRop** `static` | int |  |
| **GetSysColor** `static` | Color | Retrieves the current color of the specified display element. |
| **IsItTooDark** `static` | bool |  |
| **IsItTooLight** `static` | bool |  |
| **Light** `static` *(+1 overloads)* | Color |  |
| **MixingColors** `static` | Color |  |

---

### Method Details

#### ChangeAlpha `static`

**ChangeAlpha**(**alpha**: float, **color**: Color): Color

**Parameters**

- **alpha** (float)  
- **color** (Color)  

**Returns** Color


---

#### ChangeDarkness `static`

**ChangeDarkness**(**color**: Color, **correctionFactor**: byte): Color

**Parameters**

- **color** (Color)  
- **correctionFactor** (byte)  

**Returns** Color

---

**ChangeDarkness**(**color**: Color, **percDarker**: float): Color

**Parameters**

- **color** (Color)  
- **percDarker** (float)  

**Returns** Color


---

#### ChangeLightness `static`

**ChangeLightness**(**color**: Color, **correctionFactor**: byte): Color

**Parameters**

- **color** (Color)  
- **correctionFactor** (byte)  

**Returns** Color

---

**ChangeLightness**(**color**: Color, **correctionFactor**: float): Color

**Parameters**

- **color** (Color)  
- **correctionFactor** (float)  

**Returns** Color


---

#### Dark `static`

**Dark**(**baseColor**: string, **value**: byte): Color

**Parameters**

- **baseColor** (string)  
- **value** (byte)  

**Returns** Color

---

**Dark**(**baseColor**: Color, **value**: byte): Color

**Parameters**

- **baseColor** (Color)  
- **value** (byte)  

**Returns** Color


---

#### GetColorRop `static`

**GetColorRop**(**color**: Color, **darkROP**: int, **lightROP**: int): int

**Parameters**

- **color** (Color)  
- **darkROP** (int)  
- **lightROP** (int)  

**Returns** int


---

#### GetSysColor `static`

**GetSysColor**(**colorType**: Win32.ColorType): Color

Retrieves the current color of the specified display element.

**Parameters**

- **colorType** (Win32.ColorType) — Specifies the display element whose color is to be retrieved.  

**Returns** Color — Color value of the given element.


---

#### IsItTooDark `static`

**IsItTooDark**(**color**: Color): bool

**Parameters**

- **color** (Color)  

**Returns** bool


---

#### IsItTooLight `static`

**IsItTooLight**(**color**: Color): bool

**Parameters**

- **color** (Color)  

**Returns** bool


---

#### Light `static`

**Light**(**baseColor**: string, **value**: byte): Color

**Parameters**

- **baseColor** (string)  
- **value** (byte)  

**Returns** Color

---

**Light**(**baseColor**: Color, **value**: byte): Color

**Parameters**

- **baseColor** (Color)  
- **value** (byte)  

**Returns** Color


---

#### MixingColors `static`

**MixingColors**(**color1**: Color, **color2**: Color, **alpha**: int): Color

**Parameters**

- **color1** (Color)  
- **color2** (Color)  
- **alpha** (int)  

**Returns** Color

