---
title: "BufferedTreeNodeStream Class"
---

## BufferedTreeNodeStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Implements: [ITreeNodeStream](ITreeNodeStream.md), [ITokenStreamInformation](../ITokenStreamInformation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BufferedTreeNodeStream**(object tree) |  |
| **BufferedTreeNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree) |  |
| **BufferedTreeNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree, int initialBufferSize) |  |

**BufferedTreeNodeStream**(**tree**: object)

**Parameters**

- **tree** (object)  

---

**BufferedTreeNodeStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **tree**: object)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **tree** (object)  

---

**BufferedTreeNodeStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **tree**: object, **initialBufferSize**: int)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **tree** (object)  
- **initialBufferSize** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddNavigationNode** | void |  |
| **Consume** | void |  |
| **Dispose** | void |  |
| **FillBuffer** *(+1 overloads)* | void |  |
| **GetCurrentSymbol** | object |  |
| **GetNodeIndex** | int |  |
| **Iterator** | IEnumerator<object> |  |
| **LA** | int |  |
| **LB** | object |  |
| **LT** | object |  |
| **Mark** | int |  |
| **MoveNext** | bool |  |
| **Pop** | int |  |
| **Push** | void |  |
| **Release** | void |  |
| **ReplaceChildren** | void |  |
| **Reset** *(+1 overloads)* | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **ToString** | string |  |
| **ToTokenString** | string |  |
| **ToTokenTypeString** | string |  |
| **getLastTreeNode** | object |  |

---

### Method Details

#### AddNavigationNode

**AddNavigationNode**(**ttype**: int): void

**Parameters**

- **ttype** (int)  


---

#### Consume

**Consume**(): void


---

#### Dispose

**Dispose**(): void


---

#### FillBuffer

**FillBuffer**(): void

---

**FillBuffer**(**t**: object): void

**Parameters**

- **t** (object)  


---

#### GetCurrentSymbol

**GetCurrentSymbol**(): object

**Returns** object


---

#### GetNodeIndex

**GetNodeIndex**(**node**: object): int

**Parameters**

- **node** (object)  

**Returns** int


---

#### Iterator

**Iterator**(): IEnumerator<object>

**Returns** IEnumerator<object>


---

#### LA

**LA**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### LB

**LB**(**k**: int): object

**Parameters**

- **k** (int)  

**Returns** object


---

#### LT

**LT**(**k**: int): object

**Parameters**

- **k** (int)  

**Returns** object


---

#### Mark

**Mark**(): int

**Returns** int


---

#### MoveNext

**MoveNext**(): bool

**Returns** bool


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

#### Release

**Release**(**marker**: int): void

**Parameters**

- **marker** (int)  


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

**Reset**(): void


---

#### Rewind

**Rewind**(**marker**: int): void

**Parameters**

- **marker** (int)  

---

**Rewind**(): void


---

#### Seek

**Seek**(**index**: int): void

**Parameters**

- **index** (int)  


---

#### ToString

**ToString**(**start**: object, **stop**: object): string

**Parameters**

- **start** (object)  
- **stop** (object)  

**Returns** string


---

#### ToTokenString

**ToTokenString**(**start**: int, **stop**: int): string

**Parameters**

- **start** (int)  
- **stop** (int)  

**Returns** string


---

#### ToTokenTypeString

**ToTokenTypeString**(): string

**Returns** string


---

#### getLastTreeNode

**getLastTreeNode**(): object

**Returns** object


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DEFAULT_INITIAL_BUFFER_SIZE** | int |  |
| **INITIAL_CALL_STACK_SIZE** | int |  |
| **calls** | Stack<int> |  |
| **down** | object |  |
| **eof** | object |  |
| **lastMarker** | int |  |
| **nodes** | IList |  |
| **p** | int |  |
| **root** | object |  |
| **tokens** | [ITokenStream](../ITokenStream.md) |  |
| **up** | object |  |
