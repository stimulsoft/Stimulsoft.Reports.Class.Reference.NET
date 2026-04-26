---
title: "LookupType6SubtableFormat1 Class"
---

## LookupType6SubtableFormat1 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [LookupSubtable](LookupSubtable.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LookupType6SubtableFormat1**() |  |

**LookupType6SubtableFormat1**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ChainedSequenceRuleSets** | [ChainedSequenceRuleSet](ChainedSequenceRuleSet.md)[] |  |
| **Coverage** | [CoverageFormat](CoverageFormat.md) |  |

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

