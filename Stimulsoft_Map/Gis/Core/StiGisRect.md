---
title: "StiGisRect Struct"
---

## StiGisRect Struct

**Namespace:** `Stimulsoft.Map.Gis.Core`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisRect**([StiGisPoint](StiGisPoint.md) location, [StiGisSize](StiGisSize.md) size) |  |
| **StiGisRect**(int x, int y, int width, int height) |  |

**StiGisRect**(**location**: [StiGisPoint](StiGisPoint.md), **size**: [StiGisSize](StiGisSize.md))

**Parameters**

- **location** ([StiGisPoint](StiGisPoint.md))  
- **size** ([StiGisSize](StiGisSize.md))  

---

**StiGisRect**(**x**: int, **y**: int, **width**: int, **height**: int)

**Parameters**

- **x** (int)  
- **y** (int)  
- **width** (int)  
- **height** (int)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | int |  |
| **Width** | int |  |
| **X** | int |  |
| **Y** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+2 overloads)* | bool |  |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **Inflate** | void |  |
| **Offset** | void |  |
| **OffsetNegative** | void |  |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**x**: int, **y**: int): bool

**Parameters**

- **x** (int)  
- **y** (int)  

**Returns** bool

---

**Contains**(**pt**: [StiGisPoint](StiGisPoint.md)): bool

**Parameters**

- **pt** ([StiGisPoint](StiGisPoint.md))  

**Returns** bool

---

**Contains**(**rect**: [StiGisRect](StiGisRect.md)): bool

**Parameters**

- **rect** ([StiGisRect](StiGisRect.md))  

**Returns** bool


---

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

#### Inflate

**Inflate**(**width**: int, **height**: int): void

**Parameters**

- **width** (int)  
- **height** (int)  


---

#### Offset

**Offset**(**x**: int, **y**: int): void

**Parameters**

- **x** (int)  
- **y** (int)  


---

#### OffsetNegative

**OffsetNegative**(**pos**: [StiGisPoint](StiGisPoint.md)): void

**Parameters**

- **pos** ([StiGisPoint](StiGisPoint.md))  


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bottom** | int |  |
| **Empty** | [StiGisRect](StiGisRect.md) |  |
| **IsEmpty** | bool |  |
| **Left** | int |  |
| **LeftBottom** | [StiGisPoint](StiGisPoint.md) |  |
| **Right** | int |  |
| **RightBottom** | [StiGisPoint](StiGisPoint.md) |  |
| **RightTop** | [StiGisPoint](StiGisPoint.md) |  |
| **Top** | int |  |
