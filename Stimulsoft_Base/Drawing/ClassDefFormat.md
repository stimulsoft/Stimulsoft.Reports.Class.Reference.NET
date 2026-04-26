---
title: "ClassDefFormat Class"
---

## ClassDefFormat Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Format** | ushort |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetClass** | ushort |  |
| **GetDigestCoverage** | ushort[] |  |
| **Read** `static` | [ClassDefFormat](ClassDefFormat.md) |  |

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

**Read**(**reader**: StiFontReader, **offset**: uint): [ClassDefFormat](ClassDefFormat.md)

**Parameters**

- **reader** (StiFontReader)  
- **offset** (uint)  

**Returns** [ClassDefFormat](ClassDefFormat.md)

