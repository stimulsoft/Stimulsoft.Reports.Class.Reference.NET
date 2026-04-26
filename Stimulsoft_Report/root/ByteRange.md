---
title: "ByteRange Class"
---

## ByteRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **ByteRange**() |  |
| **ByteRange**(byte from, byte to) |  |

**ByteRange**()

---

**ByteRange**(**from**: byte, **to**: byte)

**Parameters**

- **from** (byte)  
- **to** (byte)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: byte): bool

**Parameters**

- **value** (byte)  

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
| **From** | byte |  |
| **To** | byte |  |
