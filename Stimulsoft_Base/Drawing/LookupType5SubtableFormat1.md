---
title: "LookupType5SubtableFormat1 Class"
---

## LookupType5SubtableFormat1 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [LookupSubtable](LookupSubtable.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LookupType5SubtableFormat1**() |  |

**LookupType5SubtableFormat1**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Coverage** | [CoverageFormat](CoverageFormat.md) |  |
| **SequenceRuleSets** | [SequenceRuleSet](SequenceRuleSet.md)[] |  |

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

