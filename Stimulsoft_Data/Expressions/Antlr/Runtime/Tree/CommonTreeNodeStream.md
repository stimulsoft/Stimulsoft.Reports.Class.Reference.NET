---
title: "CommonTreeNodeStream Class"
---

## CommonTreeNodeStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: Misc.LookaheadStream<object>  
Implements: [ITreeNodeStream](ITreeNodeStream.md), [IPositionTrackingStream](IPositionTrackingStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **CommonTreeNodeStream**(object tree) |  |
| **CommonTreeNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree) |  |

**CommonTreeNodeStream**(**tree**: object)

**Parameters**

- **tree** (object)  

---

**CommonTreeNodeStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **tree**: object)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **tree** (object)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dequeue** | object |  |
| **GetKnownPositionElement** | object |  |
| **HasPositionInformation** | bool |  |
| **IsEndOfFile** | bool |  |
| **LA** | int |  |
| **NextElement** | object |  |
| **Pop** | int |  |
| **Push** | void |  |
| **ReplaceChildren** | void |  |
| **Reset** | void |  |
| **ToString** | string |  |
| **ToTokenTypeString** | string |  |

---

### Method Details

#### Dequeue

**Dequeue**(): object

**Returns** object


---

#### GetKnownPositionElement

**GetKnownPositionElement**(**allowApproximateLocation**: bool): object

**Parameters**

- **allowApproximateLocation** (bool)  

**Returns** object


---

#### HasPositionInformation

**HasPositionInformation**(**node**: object): bool

**Parameters**

- **node** (object)  

**Returns** bool


---

#### IsEndOfFile

**IsEndOfFile**(**o**: object): bool

**Parameters**

- **o** (object)  

**Returns** bool


---

#### LA

**LA**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### NextElement

**NextElement**(): object

**Returns** object


---

#### Pop

**Pop**(): int

**Returns** int


---

#### Push

**Push**(**index**: int): void

**Parameters**

- **index** (int)  


---

#### ReplaceChildren

**ReplaceChildren**(**parent**: object, **startChildIndex**: int, **stopChildIndex**: int, **t**: object): void

**Parameters**

- **parent** (object)  
- **startChildIndex** (int)  
- **stopChildIndex** (int)  
- **t** (object)  


---

#### Reset

**Reset**(): void


---

#### ToString

**ToString**(**start**: object, **stop**: object): string

**Parameters**

- **start** (object)  
- **stop** (object)  

**Returns** string


---

#### ToTokenTypeString

**ToTokenTypeString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DEFAULT_INITIAL_BUFFER_SIZE** | int |  |
| **INITIAL_CALL_STACK_SIZE** | int |  |
| **tokens** | [ITokenStream](../ITokenStream.md) |  |
