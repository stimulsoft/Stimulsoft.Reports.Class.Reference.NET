---
title: "DecimalRange Class"
---

## DecimalRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **DecimalRange**() |  |
| **DecimalRange**(decimal from, decimal to) |  |

**DecimalRange**()

---

**DecimalRange**(**from**: decimal, **to**: decimal)

**Parameters**

- **from** (decimal)  
- **to** (decimal)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: decimal): bool

**Parameters**

- **value** (decimal)  

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
| **From** | decimal |  |
| **To** | decimal |  |
