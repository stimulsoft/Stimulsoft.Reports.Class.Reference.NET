---
title: "DateTimeRange Class"
---

## DateTimeRange Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: [Range](Range.md)  
Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **DateTimeRange**() |  |
| **DateTimeRange**(DateTime from, DateTime to) |  |
| **DateTimeRange**(DateTime? from, DateTime? to) |  |

**DateTimeRange**()

---

**DateTimeRange**(**from**: DateTime, **to**: DateTime)

**Parameters**

- **from** (DateTime)  
- **to** (DateTime)  

---

**DateTimeRange**(**from**: DateTime?, **to**: DateTime?)

**Parameters**

- **from** (DateTime?)  
- **to** (DateTime?)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+1 overloads)* | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToString** *(+1 overloads)* | string |  |

---

### Method Details

#### Contains

**Contains**(**value**: DateTime): bool

**Parameters**

- **value** (DateTime)  

**Returns** bool

---

**Contains**(**value**: DateTime?): bool

**Parameters**

- **value** (DateTime?)  

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

---

**ToString**(**format**: string): string

**Parameters**

- **format** (string)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **From** | DateTime? |  |
| **FromDate** | DateTime |  |
| **To** | DateTime? |  |
| **ToDate** | DateTime |  |
