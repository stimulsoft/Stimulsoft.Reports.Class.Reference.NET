---
title: "LookupType5SubtableFormat3 Class"
---

## LookupType5SubtableFormat3 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [LookupSubtable](LookupSubtable.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LookupType5SubtableFormat3**() |  |

**LookupType5SubtableFormat3**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Coverages** | [CoverageFormat](CoverageFormat.md)[] |  |
| **SequenceLookups** | [SequenceLookup](SequenceLookup.md)[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDigestCoverage** | ushort[] |  |
| **Read** `static` | [LookupSubtable](LookupSubtable.md) |  |

---

### Method Details

#### GetDigestCoverage

**GetDigestCoverage**(): ushort[]

**Returns** ushort[]


---

#### Read `static`

**Read**(**reader**: StiFontReader, **offset**: uint): [LookupSubtable](LookupSubtable.md)

**Parameters**

- **reader** (StiFontReader)  
- **offset** (uint)  

**Returns** [LookupSubtable](LookupSubtable.md)

