---
title: "DateOnly Struct"
---

## DateOnly Struct

**Namespace:** `System`

### Inheritance

Implements: IComparable  

### Constructors

| Constructor | Description |
| --- | --- |
| **DateOnly**(DateTime dateTime) |  |

**DateOnly**(**dateTime**: DateTime)

**Parameters**

- **dateTime** (DateTime)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **FromDateTime** `static` | [DateOnly](DateOnly.md) |  |
| **GetHashCode** | int |  |
| **Parse** `static` *(+2 overloads)* | [DateOnly](DateOnly.md) |  |
| **Subtract** | TimeSpan |  |
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

**FromDateTime**(**dateTime**: DateTime): [DateOnly](DateOnly.md)

**Parameters**

- **dateTime** (DateTime)  

**Returns** [DateOnly](DateOnly.md)


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### Parse `static`

**Parse**(**s**: string): [DateOnly](DateOnly.md)

**Parameters**

- **s** (string)  

**Returns** [DateOnly](DateOnly.md)

---

**Parse**(**s**: string, **provider**: IFormatProvider): [DateOnly](DateOnly.md)

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  

**Returns** [DateOnly](DateOnly.md)

---

**Parse**(**s**: string, **provider**: IFormatProvider, **style**: System.Globalization.DateTimeStyles): [DateOnly](DateOnly.md)

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  
- **style** (System.Globalization.DateTimeStyles)  

**Returns** [DateOnly](DateOnly.md)


---

#### Subtract

**Subtract**(**date**: [DateOnly](DateOnly.md)): TimeSpan

**Parameters**

- **date** ([DateOnly](DateOnly.md))  

**Returns** TimeSpan


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

**TryParse**(**s**: string, **result**: [DateOnly](DateOnly.md)): bool

**Parameters**

- **s** (string)  
- **result** ([DateOnly](DateOnly.md))  

**Returns** bool

---

**TryParse**(**s**: string, **provider**: IFormatProvider, **result**: [DateOnly](DateOnly.md)): bool

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  
- **result** ([DateOnly](DateOnly.md))  

**Returns** bool

---

**TryParse**(**s**: string, **provider**: IFormatProvider, **style**: System.Globalization.DateTimeStyles, **result**: [DateOnly](DateOnly.md)): bool

**Parameters**

- **s** (string)  
- **provider** (IFormatProvider)  
- **style** (System.Globalization.DateTimeStyles)  
- **result** ([DateOnly](DateOnly.md))  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Day** | int |  |
| **MaxValue** | [DateOnly](DateOnly.md) |  |
| **MinValue** | [DateOnly](DateOnly.md) |  |
| **Month** | int |  |
| **Now** | [DateOnly](DateOnly.md) |  |
| **Year** | int |  |
