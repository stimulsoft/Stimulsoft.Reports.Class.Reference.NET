---
title: "CharRange Class"
---

## CharRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **CharRange**() |  |
| **CharRange**(char from, char to) |  |

**CharRange**()

---

**CharRange**(**from**: char, **to**: char)

**Parameters**

- **from** (char)  
- **to** (char)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **From** | char |  |
| **To** | char |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: char): bool

**Parameters**

- **value** (char)  

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

