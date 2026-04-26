---
title: "DoubleRange Class"
---

## DoubleRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **DoubleRange**() |  |
| **DoubleRange**(double from, double to) |  |

**DoubleRange**()

---

**DoubleRange**(**from**: double, **to**: double)

**Parameters**

- **from** (double)  
- **to** (double)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: double): bool

**Parameters**

- **value** (double)  

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
| **From** | double |  |
| **To** | double |  |
