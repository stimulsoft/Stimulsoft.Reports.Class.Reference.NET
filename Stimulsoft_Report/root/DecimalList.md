---
title: "DecimalList Class"
---

## DecimalList Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: List<decimal>  
Implements: [IStiList](IStiList.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **DecimalList**() |  |
| **DecimalList**(decimalvalues ) |  |

**DecimalList**()

---

**DecimalList**(****: decimalvalues)

**Parameters**

- **** (decimalvalues)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddElement** | void |  |
| **Contains** *(+1 overloads)* | bool |  |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **LoadFromString** | [IStiList](IStiList.md) |  |
| **SaveToString** | string |  |
| **ToObjectArray** | object[] |  |
| **ToQueryString** *(+2 overloads)* | string |  |
| **ToString** | string |  |

---

### Method Details

#### AddElement

**AddElement**(**value**: object): void

**Parameters**

- **value** (object)  


---

#### Contains

**Contains**(**value**: long): bool

**Parameters**

- **value** (long)  

**Returns** bool

---

**Contains**(**value**: string): bool

**Parameters**

- **value** (string)  

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

#### LoadFromString

**LoadFromString**(**str**: string): [IStiList](IStiList.md)

**Parameters**

- **str** (string)  

**Returns** [IStiList](IStiList.md)


---

#### SaveToString

**SaveToString**(): string

**Returns** string


---

#### ToObjectArray

**ToObjectArray**(): object[]

**Returns** object[]


---

#### ToQueryString

**ToQueryString**(): string

**Returns** string

---

**ToQueryString**(**quotationMark**: string): string

**Parameters**

- **quotationMark** (string)  

**Returns** string

---

**ToQueryString**(**quotationMark**: string, **needEscape**: bool): string

**Parameters**

- **quotationMark** (string)  
- **needEscape** (bool)  

**Returns** string


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ListName** | string | Gets specified name of List. List name equal to name of List class. |
| **ListType** | Type | Gets the type of List items. |
