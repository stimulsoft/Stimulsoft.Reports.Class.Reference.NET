---
title: "LongRange Class"
---

## LongRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **LongRange**() |  |
| **LongRange**(long from, long to) |  |

**LongRange**()

---

**LongRange**(**from**: long, **to**: long)

**Parameters**

- **from** (long)  
- **to** (long)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: long): bool

**Parameters**

- **value** (long)  

**Returns** bool


---

#### Parse

**Parse**(**from**: string, **to**: string): void

Fill From and To item of range with it string representation.

**Parameters**

- **from** (string)  
- **to** (string)  


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **From** | long |  |
| **To** | long |  |
