---
title: "LookupType6SubtableFormat3 Class"
---

## LookupType6SubtableFormat3 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [LookupSubtable](LookupSubtable.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LookupType6SubtableFormat3**() |  |

**LookupType6SubtableFormat3**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BacktrackCoverages** | [CoverageFormat](CoverageFormat.md)[] |  |
| **InputCoverages** | [CoverageFormat](CoverageFormat.md)[] |  |
| **LookaheadCoverages** | [CoverageFormat](CoverageFormat.md)[] |  |
| **SeqLookups** | [SequenceLookup](SequenceLookup.md)[] |  |

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

