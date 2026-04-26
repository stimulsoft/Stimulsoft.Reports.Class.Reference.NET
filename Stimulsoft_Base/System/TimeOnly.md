---
title: "TimeOnly Struct"
---

## TimeOnly Struct

**Namespace:** `System`

### Inheritance

Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **TimeOnly**(long ticks) |  |
| **TimeOnly**(DateTime dateTime) |  |

**TimeOnly**(**ticks**: long)

**Parameters**

- **ticks** (long)  

---

**TimeOnly**(**dateTime**: DateTime)

**Parameters**

- **dateTime** (DateTime)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **FromDateTime** `static` | [TimeOnly](TimeOnly.md) |  |
| **GetHashCode** | int |  |
| **Parse** `static` *(+2 overloads)* | [TimeOnly](TimeOnly.md) |  |
| **ToString** *(+3 overloads)* | string |  |
| **TryParse** `static` *(+2 overloads)* | bool |  |

---

### Method Details

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### FromDateTime `static`

**FromDateTime**(**dateTime**: DateTime): [TimeOnly](TimeOnly.md)

**Parameters**

- **dateTime** (DateTime)  

**Returns** [TimeOnly](TimeOnly.md)


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### Parse `static`

**Parse**(**s**: string): [TimeOnly](TimeOnly.md)

**Parameters**

- **s** (string)  

**Returns** [TimeOnly](TimeOnly.md)

---

**Parse**(**s**: string, **provider**: IFormatProvider): [TimeOnly](TimeOnly.md)

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  

**Returns** [TimeOnly](TimeOnly.md)

---

**Parse**(**s**: string, **provider**: IFormatProvider, **style**: System.Globalization.DateTimeStyles): [TimeOnly](TimeOnly.md)

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  
- **style** (System.Globalization.DateTimeStyles)  

**Returns** [TimeOnly](TimeOnly.md)


---

#### ToString

**ToString**(): string

**Returns** string

---

**ToString**(**format**: string): string

**Parameters**

- **format** (string)  

**Returns** string

---

**ToString**(**provider**: IFormatProvider): string

**Parameters**

- **provider** (IFormatProvider)  

**Returns** string

---

**ToString**(**format**: string, **provider**: IFormatProvider): string

**Parameters**

- **format** (string)  
- **provider** (IFormatProvider)  

**Returns** string


---

#### TryParse `static`

**TryParse**(**s**: string, **result**: [TimeOnly](TimeOnly.md)): bool

**Parameters**

- **s** (string)  
- **result** ([TimeOnly](TimeOnly.md))  

**Returns** bool

---

**TryParse**(**s**: string, **provider**: IFormatProvider, **result**: [TimeOnly](TimeOnly.md)): bool

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  
- **result** ([TimeOnly](TimeOnly.md))  

**Returns** bool

---

**TryParse**(**s**: string, **provider**: IFormatProvider, **style**: System.Globalization.DateTimeStyles, **result**: [TimeOnly](TimeOnly.md)): bool

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  
- **style** (System.Globalization.DateTimeStyles)  
- **result** ([TimeOnly](TimeOnly.md))  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Hour** | int |  |
| **Millisecond** | int |  |
| **Minute** | int |  |
| **Second** | int |  |
| **Zero** | [TimeOnly](TimeOnly.md) |  |
