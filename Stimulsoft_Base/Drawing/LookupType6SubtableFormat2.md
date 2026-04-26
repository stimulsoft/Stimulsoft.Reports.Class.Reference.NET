---
title: "LookupType6SubtableFormat2 Class"
---

## LookupType6SubtableFormat2 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [LookupSubtable](LookupSubtable.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LookupType6SubtableFormat2**() |  |

**LookupType6SubtableFormat2**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BacktrackClassDef** | [ClassDefFormat](ClassDefFormat.md) |  |
| **ChainedClassSequenceRuleSets** | [ChainedClassSequenceRuleSet](ChainedClassSequenceRuleSet.md)[] |  |
| **Coverage** | [CoverageFormat](CoverageFormat.md) |  |
| **InputClassDef** | [ClassDefFormat](ClassDefFormat.md) |  |
| **LookaheadClassDef** | [ClassDefFormat](ClassDefFormat.md) |  |

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

