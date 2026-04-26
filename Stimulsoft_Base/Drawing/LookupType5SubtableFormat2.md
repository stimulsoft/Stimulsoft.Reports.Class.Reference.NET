---
title: "LookupType5SubtableFormat2 Class"
---

## LookupType5SubtableFormat2 Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: [LookupSubtable](LookupSubtable.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LookupType5SubtableFormat2**() |  |

**LookupType5SubtableFormat2**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClassDef** | [ClassDefFormat](ClassDefFormat.md) |  |
| **ClassSequenceRuleSets** | [ClassSequenceRuleSet](ClassSequenceRuleSet.md)[] |  |
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

