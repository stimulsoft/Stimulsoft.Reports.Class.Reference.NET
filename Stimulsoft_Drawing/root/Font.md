---
title: "Font Class"
---

## Font Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **Font**([Font](Font.md) prototype, float size) |  |
| **Font**([Font](Font.md) prototype, System.Drawing.FontStyle newStyle) |  |
| **Font**([FontFamily](FontFamily.md) family, float emSize) |  |
| **Font**(string familyName, float emSize) |  |
| **Font**([FontFamily](FontFamily.md) family, float emSize, System.Drawing.GraphicsUnit unit) |  |
| **Font**(string familyName, float emSize, System.Drawing.GraphicsUnit unit) |  |
| **Font**([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style) |  |
| **Font**(string familyName, float emSize, System.Drawing.FontStyle style) |  |
| **Font**([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit) |  |
| **Font**(string familyName, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit) |  |
| **Font**([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet) |  |
| **Font**(string familyName, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet) |  |
| **Font**(string familyName, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont) |  |
| **Font**([FontFamily](FontFamily.md) family, float emSize, System.Drawing.FontStyle style, System.Drawing.GraphicsUnit unit, byte gdiCharSet, bool gdiVerticalFont) |  |

**Font**(**prototype**: [Font](Font.md), **size**: float)

**Parameters**

- **prototype** ([Font](Font.md))  
- **size** (float)  

---

**Font**(**prototype**: [Font](Font.md), **newStyle**: System.Drawing.FontStyle)

**Parameters**

- **prototype** ([Font](Font.md))  
- **newStyle** (System.Drawing.FontStyle)  

---

**Font**(**family**: [FontFamily](FontFamily.md), **emSize**: float)

**Parameters**

- **family** ([FontFamily](FontFamily.md))  
- **emSize** (float)  

---

**Font**(**familyName**: string, **emSize**: float)

**Parameters**

- **familyName** (string)  
- **emSize** (float)  

---

**Font**(**family**: [FontFamily](FontFamily.md), **emSize**: float, **unit**: System.Drawing.GraphicsUnit)

**Parameters**

- **family** ([FontFamily](FontFamily.md))  
- **emSize** (float)  
- **unit** (System.Drawing.GraphicsUnit)  

---

**Font**(**familyName**: string, **emSize**: float, **unit**: System.Drawing.GraphicsUnit)

**Parameters**

- **familyName** (string)  
- **emSize** (float)  
- **unit** (System.Drawing.GraphicsUnit)  

---

**Font**(**family**: [FontFamily](FontFamily.md), **emSize**: float, **style**: System.Drawing.FontStyle)

**Parameters**

- **family** ([FontFamily](FontFamily.md))  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  

---

**Font**(**familyName**: string, **emSize**: float, **style**: System.Drawing.FontStyle)

**Parameters**

- **familyName** (string)  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  

---

**Font**(**family**: [FontFamily](FontFamily.md), **emSize**: float, **style**: System.Drawing.FontStyle, **unit**: System.Drawing.GraphicsUnit)

**Parameters**

- **family** ([FontFamily](FontFamily.md))  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  
- **unit** (System.Drawing.GraphicsUnit)  

---

**Font**(**familyName**: string, **emSize**: float, **style**: System.Drawing.FontStyle, **unit**: System.Drawing.GraphicsUnit)

**Parameters**

- **familyName** (string)  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  
- **unit** (System.Drawing.GraphicsUnit)  

---

**Font**(**family**: [FontFamily](FontFamily.md), **emSize**: float, **style**: System.Drawing.FontStyle, **unit**: System.Drawing.GraphicsUnit, **gdiCharSet**: byte)

**Parameters**

- **family** ([FontFamily](FontFamily.md))  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  
- **unit** (System.Drawing.GraphicsUnit)  
- **gdiCharSet** (byte)  

---

**Font**(**familyName**: string, **emSize**: float, **style**: System.Drawing.FontStyle, **unit**: System.Drawing.GraphicsUnit, **gdiCharSet**: byte)

**Parameters**

- **familyName** (string)  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  
- **unit** (System.Drawing.GraphicsUnit)  
- **gdiCharSet** (byte)  

---

**Font**(**familyName**: string, **emSize**: float, **style**: System.Drawing.FontStyle, **unit**: System.Drawing.GraphicsUnit, **gdiCharSet**: byte, **gdiVerticalFont**: bool)

**Parameters**

- **familyName** (string)  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  
- **unit** (System.Drawing.GraphicsUnit)  
- **gdiCharSet** (byte)  
- **gdiVerticalFont** (bool)  

---

**Font**(**family**: [FontFamily](FontFamily.md), **emSize**: float, **style**: System.Drawing.FontStyle, **unit**: System.Drawing.GraphicsUnit, **gdiCharSet**: byte, **gdiVerticalFont**: bool)

**Parameters**

- **family** ([FontFamily](FontFamily.md))  
- **emSize** (float)  
- **style** (System.Drawing.FontStyle)  
- **unit** (System.Drawing.GraphicsUnit)  
- **gdiCharSet** (byte)  
- **gdiVerticalFont** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **Dispose** | void |  |
| **FromLogFont** `static` | [Font](Font.md) |  |
| **GetHeight** | float |  |
| **ToHfont** | IntPtr |  |
| **ToString** | String |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### Dispose

**Dispose**(): void


---

#### FromLogFont `static`

**FromLogFont**(**elfLogFont**: object): [Font](Font.md)

**Parameters**

- **elfLogFont** (object)  

**Returns** [Font](Font.md)


---

#### GetHeight

**GetHeight**(): float

**Returns** float


---

#### ToHfont

**ToHfont**(): IntPtr

**Returns** IntPtr


---

#### ToString

**ToString**(): String

**Returns** String

