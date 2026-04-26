---
title: "ClassDefFormat1 Class"
---

## ClassDefFormat1 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [ClassDefFormat](ClassDefFormat.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Format** | ushort |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetClass** | ushort |  |
| **GetDigestCoverage** | ushort[] |  |
| **Read** `static` | [ClassDefFormat1](ClassDefFormat1.md) |  |

---

### Method Details

#### GetClass

**GetClass**(**glyph**: ushort): ushort

**Parameters**

- **glyph** (ushort)  

**Returns** ushort


---

#### GetDigestCoverage

**GetDigestCoverage**(): ushort[]

**Returns** ushort[]


---

#### Read `static`

**Read**(**reader**: StiFontReader): [ClassDefFormat1](ClassDefFormat1.md)

**Parameters**

- **reader** (StiFontReader)  

**Returns** [ClassDefFormat1](ClassDefFormat1.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ClassValues** | ushort[] |  |
| **StartGlyphID** | ushort |  |
