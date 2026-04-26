---
title: "DateTimeList Class"
---

## DateTimeList Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Inherits from: List<DateTime>  
Implements: [IStiList](IStiList.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **DateTimeList**() |  |
| **DateTimeList**(DateTimevalues ) |  |

**DateTimeList**()

---

**DateTimeList**(****: DateTimevalues)

**Parameters**

- **** (DateTimevalues)  


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
| **ToQueryString** *(+4 overloads)* | string |  |
| **ToString** *(+1 overloads)* | string |  |

---

### Method Details

#### AddElement

**AddElement**(**value**: object): void

**Parameters**

- **value** (object)  


---

#### Contains

**Contains**(**value**: DateTime?): bool

**Parameters**

- **value** (DateTime?)  

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

**ToQueryString**(**quotationMark**: string, **dateTimeFormat**: string): string

**Parameters**

- **quotationMark** (string)  
- **dateTimeFormat** (string)  

**Returns** string

---

**ToQueryString**(**quotationMark**: string, **needEscape**: bool): string

**Parameters**

- **quotationMark** (string)  
- **needEscape** (bool)  

**Returns** string

---

**ToQueryString**(**quotationMark**: string, **dateTimeFormat**: string, **needEscape**: bool): string

**Parameters**

- **quotationMark** (string)  
- **dateTimeFormat** (string)  
- **needEscape** (bool)  

**Returns** string


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
| **ListName** | string | Gets specified name of List. List name equal to name of List class. |
| **ListType** | Type | Gets the type of List items. |
