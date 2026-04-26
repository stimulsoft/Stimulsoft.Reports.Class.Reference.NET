---
title: "GuidRange Class"
---

## GuidRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **GuidRange**() |  |
| **GuidRange**(Guid from, Guid to) |  |

**GuidRange**()

---

**GuidRange**(**from**: Guid, **to**: Guid)

**Parameters**

- **from** (Guid)  
- **to** (Guid)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: Guid): bool

**Parameters**

- **value** (Guid)  

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
| **From** | Guid |  |
| **To** | Guid |  |
