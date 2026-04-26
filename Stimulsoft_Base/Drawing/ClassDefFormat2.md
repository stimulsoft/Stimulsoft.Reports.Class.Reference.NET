---
title: "ClassDefFormat2 Class"
---

## ClassDefFormat2 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [ClassDefFormat](ClassDefFormat.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClassRangeRecords** | [ClassRangeRecord](ClassRangeRecord.md)[] |  |
| **Format** | ushort |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetClass** | ushort |  |
| **GetDigestCoverage** | ushort[] |  |
| **Read** `static` | [ClassDefFormat2](ClassDefFormat2.md) |  |

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

**Read**(**reader**: StiFontReader): [ClassDefFormat2](ClassDefFormat2.md)

**Parameters**

- **reader** (StiFontReader)  

**Returns** [ClassDefFormat2](ClassDefFormat2.md)

