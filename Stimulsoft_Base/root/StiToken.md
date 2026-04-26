---
title: "StiToken Class"
---

## StiToken Class

**Namespace:** `Stimulsoft.Base`

Class describes Token.

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiToken**([StiTokenType](StiTokenType.md) type) | Create a new instance StiToken. |
| **StiToken**([StiTokenType](StiTokenType.md) type, int index, int length) | Creates a new object of the type StiToken. |
| **StiToken**([StiTokenType](StiTokenType.md) type, int index, int length, char charValue) | Creates a new object of the type StiToken. |
| **StiToken**([StiTokenType](StiTokenType.md) type, int index, int length, string stringValue) | Creates an object of the type StiToken that contains the value of the string. |
| **StiToken**([StiTokenType](StiTokenType.md) type, int index, int length, object obj) | Creates an object of the type StiToken that contains an object. |

**StiToken**(**type**: [StiTokenType](StiTokenType.md))

Create a new instance StiToken.

**Parameters**

- **type** ([StiTokenType](StiTokenType.md)) — Type Token.  

---

**StiToken**(**type**: [StiTokenType](StiTokenType.md), **index**: int, **length**: int)

Creates a new object of the type StiToken.

**Parameters**

- **type** ([StiTokenType](StiTokenType.md)) — Type Token.  
- **index** (int) — The Beginning Token in text.  
- **length** (int) — The Length Token.  

---

**StiToken**(**type**: [StiTokenType](StiTokenType.md), **index**: int, **length**: int, **charValue**: char)

Creates a new object of the type StiToken.

**Parameters**

- **type** ([StiTokenType](StiTokenType.md)) — Type Token.  
- **index** (int) — The Beginning Token in text.  
- **length** (int) — The Length Token.  
- **charValue** (char) — Char for initializing  

---

**StiToken**(**type**: [StiTokenType](StiTokenType.md), **index**: int, **length**: int, **stringValue**: string)

Creates an object of the type StiToken that contains the value of the string.

**Parameters**

- **type** ([StiTokenType](StiTokenType.md)) — Type Token.  
- **index** (int) — The Beginning Token in text.  
- **length** (int) — The Length Token.  
- **stringValue** (string) — String for initializing.  

---

**StiToken**(**type**: [StiTokenType](StiTokenType.md), **index**: int, **length**: int, **obj**: object)

Creates an object of the type StiToken that contains an object.

**Parameters**

- **type** ([StiTokenType](StiTokenType.md)) — Type Token  
- **index** (int) — The Beginning Token in text.  
- **length** (int) — The Length Token.  
- **obj** (object) — Object for initializing.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Data** | object | Gets or sets Value of the identifier. |
| **Index** | int | Gets or sets value indicates the beginning of token in text. |
| **Length** | int | Gets or sets value indicates the length of token. |
| **Type** | [StiTokenType](StiTokenType.md) | Gets or sets value indicates the type of token. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **IsAssign** | bool |  |
| **IsDot** | bool |  |
| **IsIdent** | bool |  |
| **IsIdentOrKeyword** | bool |  |
| **IsKeyword** | bool |  |
| **IsLBrace** | bool |  |
| **IsLBracket** | bool |  |
| **IsLPar** | bool |  |
| **IsRBrace** | bool |  |
| **IsRBracket** | bool |  |
| **IsRPar** | bool |  |
| **ToString** | string |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### IsAssign

**IsAssign**(): bool

**Returns** bool


---

#### IsDot

**IsDot**(): bool

**Returns** bool


---

#### IsIdent

**IsIdent**(**ident**: string): bool

**Parameters**

- **ident** (string)  

**Returns** bool


---

#### IsIdentOrKeyword

**IsIdentOrKeyword**(): bool

**Returns** bool


---

#### IsKeyword

**IsKeyword**(**keyword**: string): bool

**Parameters**

- **keyword** (string)  

**Returns** bool


---

#### IsLBrace

**IsLBrace**(): bool

**Returns** bool


---

#### IsLBracket

**IsLBracket**(): bool

**Returns** bool


---

#### IsLPar

**IsLPar**(): bool

**Returns** bool


---

#### IsRBrace

**IsRBrace**(): bool

**Returns** bool


---

#### IsRBracket

**IsRBracket**(): bool

**Returns** bool


---

#### IsRPar

**IsRPar**(): bool

**Returns** bool


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DataAsString** | string |  |
| **EOF** | [StiToken](StiToken.md) |  |
