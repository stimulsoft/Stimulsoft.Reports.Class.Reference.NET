---
title: "StiPagesRange Class"
---

## StiPagesRange Class

**Namespace:** `Stimulsoft.Report`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPagesRange**() | Creates a new instance of the StiPagesRange class. |
| **StiPagesRange**(int currentPage) | Creates a new instance of the StiPagesRange class. |
| **StiPagesRange**(string pageRanges) | Creates a new instance of the StiPagesRange class. |
| **StiPagesRange**([StiRangeType](StiRangeType.md) rangeType, string pageRanges, int currentPage) | Creates a new instance of the StiPagesRange class. |

**StiPagesRange**()

Creates a new instance of the StiPagesRange class.

---

**StiPagesRange**(**currentPage**: int)

Creates a new instance of the StiPagesRange class.

**Parameters**

- **currentPage** (int) — Current page.  

---

**StiPagesRange**(**pageRanges**: string)

Creates a new instance of the StiPagesRange class.

**Parameters**

- **pageRanges** (string) — Range of pages.  

---

**StiPagesRange**(**rangeType**: [StiRangeType](StiRangeType.md), **pageRanges**: string, **currentPage**: int)

Creates a new instance of the StiPagesRange class.

**Parameters**

- **rangeType** ([StiRangeType](StiRangeType.md)) — Type of pages range.  
- **pageRanges** (string) — Range of pages.  
- **currentPage** (int) — Current page.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CurrentPage** | int |  |
| **PageRanges** | string |  |
| **RangeType** | [StiRangeType](StiRangeType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **GetSelectedPages** | [StiPagesCollection](../Components/StiPagesCollection.md) | Returns collection of selected pages. |

---

### Method Details

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### GetSelectedPages

**GetSelectedPages**(**originalPages**: [StiPagesCollection](../Components/StiPagesCollection.md)): [StiPagesCollection](../Components/StiPagesCollection.md)

Returns collection of selected pages.

**Parameters**

- **originalPages** ([StiPagesCollection](../Components/StiPagesCollection.md)) — Collection of pages for filtering.  

**Returns** [StiPagesCollection](../Components/StiPagesCollection.md) — Collection of selected pages.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **All** | [StiPagesRange](StiPagesRange.md) |  |
