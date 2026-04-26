---
title: "IntRange Class"
---

## IntRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **IntRange**() |  |
| **IntRange**(int from, int to) |  |

**IntRange**()

---

**IntRange**(**from**: int, **to**: int)

**Parameters**

- **from** (int)  
- **to** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: int): bool

**Parameters**

- **value** (int)  

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
| **From** | int |  |
| **To** | int |  |
