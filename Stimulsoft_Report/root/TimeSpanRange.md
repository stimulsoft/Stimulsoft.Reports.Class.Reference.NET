---
title: "TimeSpanRange Class"
---

## TimeSpanRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **TimeSpanRange**() |  |
| **TimeSpanRange**(TimeSpan from, TimeSpan to) |  |
| **TimeSpanRange**(TimeSpan? from, TimeSpan? to) |  |

**TimeSpanRange**()

---

**TimeSpanRange**(**from**: TimeSpan, **to**: TimeSpan)

**Parameters**

- **from** (TimeSpan)  
- **to** (TimeSpan)  

---

**TimeSpanRange**(**from**: TimeSpan?, **to**: TimeSpan?)

**Parameters**

- **from** (TimeSpan?)  
- **to** (TimeSpan?)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+1 overloads)* | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: TimeSpan): bool

**Parameters**

- **value** (TimeSpan)  

**Returns** bool

---

**Contains**(**value**: TimeSpan?): bool

**Parameters**

- **value** (TimeSpan?)  

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
| **From** | TimeSpan? |  |
| **FromTime** | TimeSpan |  |
| **To** | TimeSpan? |  |
| **ToTime** | TimeSpan |  |
