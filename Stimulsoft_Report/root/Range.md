---
title: "Range Class"
---

## Range Class

**Namespace:** `Stimulsoft.Report`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FromObject** | object | Gets or sets From item of range. |
| **RangeName** | string | Gets specified name of range. Range name equal to name of range class. |
| **RangeType** | Type | Gets the type of range items. |
| **ToObject** | object | Gets or set To item of range. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **IsRangeType** `static` | bool |  |
| **Parse** | void | Fill From and To item of range with it string representation. |
| **ToDecimalRange** | [DecimalRange](DecimalRange.md) |  |

---

### Method Details

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### IsRangeType `static`

**IsRangeType**(**type**: Type): bool

**Parameters**

- **type** (Type)  

**Returns** bool


---

#### Parse

**Parse**(**from**: string, **to**: string): void

Fill From and To item of range with it string representation.

**Parameters**

- **from** (string)  
- **to** (string)  


---

#### ToDecimalRange

**ToDecimalRange**(): [DecimalRange](DecimalRange.md)

**Returns** [DecimalRange](DecimalRange.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **FromStrLoc** | string |  |
| **ToStrLoc** | string |  |
