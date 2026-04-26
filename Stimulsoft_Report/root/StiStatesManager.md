---
title: "StiStatesManager Class"
---

## StiStatesManager Class

**Namespace:** `Stimulsoft.Report`

The class describes the manager of the object state.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void | Clear all earlier saved object states. |
| **ClearState** | void |  |
| **IsExist** | bool |  |
| **Pop** | object | Gets the object state. |
| **PopBool** | bool | Gets the object state. |
| **PopDecimal** | decimal |  |
| **PopDouble** | double |  |
| **PopFloat** | float |  |
| **PopInt** | int |  |
| **PopInt64** | Int64 |  |
| **PopRange** | [Range](Range.md) |  |
| **Push** | void | Saves the specified object state. |
| **PushBool** | void | Saves the specified object state. |
| **PushDecimal** | void |  |
| **PushDouble** | void |  |
| **PushFloat** | void |  |
| **PushInt** | void |  |
| **PushInt64** | void |  |
| **PushRange** | void |  |

---

### Method Details

#### Clear

**Clear**(): void

Clear all earlier saved object states.


---

#### ClearState

**ClearState**(**stateName**: string): void

**Parameters**

- **stateName** (string)  


---

#### IsExist

**IsExist**(**stateName**: string, **obj**: object): bool

**Parameters**

- **stateName** (string)  
- **obj** (object)  

**Returns** bool


---

#### Pop

**Pop**(**stateName**: string, **obj**: object, **property**: string): object

Gets the object state.

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** object


---

#### PopBool

**PopBool**(**stateName**: string, **obj**: object, **property**: string): bool

Gets the object state.

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** bool


---

#### PopDecimal

**PopDecimal**(**stateName**: string, **obj**: object, **property**: string): decimal

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** decimal


---

#### PopDouble

**PopDouble**(**stateName**: string, **obj**: object, **property**: string): double

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** double


---

#### PopFloat

**PopFloat**(**stateName**: string, **obj**: object, **property**: string): float

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** float


---

#### PopInt

**PopInt**(**stateName**: string, **obj**: object, **property**: string): int

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** int


---

#### PopInt64

**PopInt64**(**stateName**: string, **obj**: object, **property**: string): Int64

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** Int64


---

#### PopRange

**PopRange**(**stateName**: string, **obj**: object, **property**: string): [Range](Range.md)

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  

**Returns** [Range](Range.md)


---

#### Push

**Push**(**stateName**: string, **obj**: object, **property**: string, **value**: object): void

Saves the specified object state.

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (object)  


---

#### PushBool

**PushBool**(**stateName**: string, **obj**: object, **property**: string, **value**: bool): void

Saves the specified object state.

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (bool)  


---

#### PushDecimal

**PushDecimal**(**stateName**: string, **obj**: object, **property**: string, **value**: decimal): void

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (decimal)  


---

#### PushDouble

**PushDouble**(**stateName**: string, **obj**: object, **property**: string, **value**: double): void

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (double)  


---

#### PushFloat

**PushFloat**(**stateName**: string, **obj**: object, **property**: string, **value**: float): void

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (float)  


---

#### PushInt

**PushInt**(**stateName**: string, **obj**: object, **property**: string, **value**: int): void

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (int)  


---

#### PushInt64

**PushInt64**(**stateName**: string, **obj**: object, **property**: string, **value**: Int64): void

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** (Int64)  


---

#### PushRange

**PushRange**(**stateName**: string, **obj**: object, **property**: string, **value**: [Range](Range.md)): void

**Parameters**

- **stateName** (string)  
- **obj** (object)  
- **property** (string)  
- **value** ([Range](Range.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **From** | object |  |
| **RangeType** | Type |  |
| **To** | object |  |
| **value** | int |  |
| **value** | float |  |
| **value** | double |  |
| **value** | Int64 |  |
| **value** | decimal |  |
