---
title: "StiGisPoint Struct"
---

## StiGisPoint Struct

**Namespace:** `Stimulsoft.Map.Gis.Core`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisPoint**(int x, int y) |  |

**StiGisPoint**(**x**: int, **y**: int)

**Parameters**

- **x** (int)  
- **y** (int)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **X** | int |  |
| **Y** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **Offset** *(+1 overloads)* | void |  |
| **OffsetNegative** | void |  |
| **ToString** | string |  |

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

#### Offset

**Offset**(**dx**: int, **dy**: int): void

**Parameters**

- **dx** (int)  
- **dy** (int)  

---

**Offset**(**p**: [StiGisPoint](StiGisPoint.md)): void

**Parameters**

- **p** ([StiGisPoint](StiGisPoint.md))  


---

#### OffsetNegative

**OffsetNegative**(**p**: [StiGisPoint](StiGisPoint.md)): void

**Parameters**

- **p** ([StiGisPoint](StiGisPoint.md))  


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiGisPoint](StiGisPoint.md) |  |
| **IsEmpty** | bool |  |
