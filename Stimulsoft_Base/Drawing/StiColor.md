---
title: "StiColor Class"
---

## StiColor Class

**Namespace:** `Stimulsoft.Base.Drawing`

This class helps in converting a string to a color.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` *(+1 overloads)* | Color | Translates a HTML color representation to a GDI+ System.Drawing.Color structure. |
| **ToHex** `static` | string |  |

---

### Method Details

#### Get `static`

**Get**(**text**: string): Color

Translates a HTML color representation to a GDI+ System.Drawing.Color structure.

**Parameters**

- **text** (string)  

**Returns** Color

---

**Get**(****: stringcolors): Color[]

Translates an array with HTML colors representation to a GDI+ System.Drawing.Color structure.

**Parameters**

- **** (stringcolors)  

**Returns** Color[]


---

#### ToHex `static`

**ToHex**(**c**: Color): string

**Parameters**

- **c** (Color)  

**Returns** string

