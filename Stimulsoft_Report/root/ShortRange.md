---
title: "ShortRange Class"
---

## ShortRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **ShortRange**() |  |
| **ShortRange**(short from, short to) |  |

**ShortRange**()

---

**ShortRange**(**from**: short, **to**: short)

**Parameters**

- **from** (short)  
- **to** (short)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: short): bool

**Parameters**

- **value** (short)  

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
| **From** | short |  |
| **To** | short |  |
