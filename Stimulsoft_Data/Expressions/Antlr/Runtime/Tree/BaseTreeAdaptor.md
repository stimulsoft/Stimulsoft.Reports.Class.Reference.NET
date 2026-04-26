---
title: "BaseTreeAdaptor Class"
---

## BaseTreeAdaptor Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Implements: [ITreeAdaptor](ITreeAdaptor.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddChild** | void |  |
| **BecomeRoot** *(+1 overloads)* | object |  |
| **Create** *(+4 overloads)* | object |  |
| **CreateToken** *(+1 overloads)* | [IToken](../IToken.md) |  |
| **DeleteChild** | object |  |
| **DupNode** *(+3 overloads)* | object |  |
| **DupTree** *(+1 overloads)* | object |  |
| **GetChild** | object |  |
| **GetChildCount** | int |  |
| **GetChildIndex** | int |  |
| **GetParent** | object |  |
| **GetText** | string |  |
| **GetToken** | [IToken](../IToken.md) |  |
| **GetTokenStartIndex** | int |  |
| **GetTokenStopIndex** | int |  |
| **GetTree** | [ITree](ITree.md) |  |
| **GetType** | int |  |
| **GetUniqueID** | int |  |
| **IsNil** | bool |  |
| **Nil** | object |  |
| **ReplaceChildren** | void |  |
| **RulePostProcessing** | object |  |
| **SetChild** | void |  |
| **SetChildIndex** | void |  |
| **SetParent** | void |  |
| **SetText** | void |  |
| **SetTokenBoundaries** | void |  |
| **SetType** | void |  |

---

### Method Details

#### AddChild

**AddChild**(**t**: object, **child**: object): void

**Parameters**

- **t** (object)  
- **child** (object)  


---

#### BecomeRoot

**BecomeRoot**(**newRoot**: object, **oldRoot**: object): object

**Parameters**

- **newRoot** (object)  
- **oldRoot** (object)  

**Returns** object

---

**BecomeRoot**(**newRoot**: [IToken](../IToken.md), **oldRoot**: object): object

**Parameters**

- **newRoot** ([IToken](../IToken.md))  
- **oldRoot** (object)  

**Returns** object


---

#### Create

**Create**(**tokenType**: int, **fromToken**: [IToken](../IToken.md)): object

**Parameters**

- **tokenType** (int)  
- **fromToken** ([IToken](../IToken.md))  

**Returns** object

---

**Create**(**tokenType**: int, **fromToken**: [IToken](../IToken.md), **text**: string): object

**Parameters**

- **tokenType** (int)  
- **fromToken** ([IToken](../IToken.md))  
- **text** (string)  

**Returns** object

---

**Create**(**fromToken**: [IToken](../IToken.md), **text**: string): object

**Parameters**

- **fromToken** ([IToken](../IToken.md))  
- **text** (string)  

**Returns** object

---

**Create**(**tokenType**: int, **text**: string): object

**Parameters**

- **tokenType** (int)  
- **text** (string)  

**Returns** object

---

**Create**(**payload**: [IToken](../IToken.md)): object

**Parameters**

- **payload** ([IToken](../IToken.md))  

**Returns** object


---

#### CreateToken

**CreateToken**(**tokenType**: int, **text**: string): [IToken](../IToken.md)

**Parameters**

- **tokenType** (int)  
- **text** (string)  

**Returns** [IToken](../IToken.md)

---

**CreateToken**(**fromToken**: [IToken](../IToken.md)): [IToken](../IToken.md)

**Parameters**

- **fromToken** ([IToken](../IToken.md))  

**Returns** [IToken](../IToken.md)


---

#### DeleteChild

**DeleteChild**(**t**: object, **i**: int): object

**Parameters**

- **t** (object)  
- **i** (int)  

**Returns** object


---

#### DupNode

**DupNode**(**type**: int, **treeNode**: object): object

**Parameters**

- **type** (int)  
- **treeNode** (object)  

**Returns** object

---

**DupNode**(**treeNode**: object, **text**: string): object

**Parameters**

- **treeNode** (object)  
- **text** (string)  

**Returns** object

---

**DupNode**(**type**: int, **treeNode**: object, **text**: string): object

**Parameters**

- **type** (int)  
- **treeNode** (object)  
- **text** (string)  

**Returns** object

---

**DupNode**(**treeNode**: object): object

**Parameters**

- **treeNode** (object)  

**Returns** object


---

#### DupTree

**DupTree**(**tree**: object): object

**Parameters**

- **tree** (object)  

**Returns** object

---

**DupTree**(**t**: object, **parent**: object): object

**Parameters**

- **t** (object)  
- **parent** (object)  

**Returns** object


---

#### GetChild

**GetChild**(**t**: object, **i**: int): object

**Parameters**

- **t** (object)  
- **i** (int)  

**Returns** object


---

#### GetChildCount

**GetChildCount**(**t**: object): int

**Parameters**

- **t** (object)  

**Returns** int


---

#### GetChildIndex

**GetChildIndex**(**t**: object): int

**Parameters**

- **t** (object)  

**Returns** int


---

#### GetParent

**GetParent**(**t**: object): object

**Parameters**

- **t** (object)  

**Returns** object


---

#### GetText

**GetText**(**t**: object): string

**Parameters**

- **t** (object)  

**Returns** string


---

#### GetToken

**GetToken**(**t**: object): [IToken](../IToken.md)

**Parameters**

- **t** (object)  

**Returns** [IToken](../IToken.md)


---

#### GetTokenStartIndex

**GetTokenStartIndex**(**t**: object): int

**Parameters**

- **t** (object)  

**Returns** int


---

#### GetTokenStopIndex

**GetTokenStopIndex**(**t**: object): int

**Parameters**

- **t** (object)  

**Returns** int


---

#### GetTree

**GetTree**(**t**: object): [ITree](ITree.md)

**Parameters**

- **t** (object)  

**Returns** [ITree](ITree.md)


---

#### GetType

**GetType**(**t**: object): int

**Parameters**

- **t** (object)  

**Returns** int


---

#### GetUniqueID

**GetUniqueID**(**node**: object): int

**Parameters**

- **node** (object)  

**Returns** int


---

#### IsNil

**IsNil**(**tree**: object): bool

**Parameters**

- **tree** (object)  

**Returns** bool


---

#### Nil

**Nil**(): object

**Returns** object


---

#### ReplaceChildren

**ReplaceChildren**(**parent**: object, **startChildIndex**: int, **stopChildIndex**: int, **t**: object): void

**Parameters**

- **parent** (object)  
- **startChildIndex** (int)  
- **stopChildIndex** (int)  
- **t** (object)  


---

#### RulePostProcessing

**RulePostProcessing**(**root**: object): object

**Parameters**

- **root** (object)  

**Returns** object


---

#### SetChild

**SetChild**(**t**: object, **i**: int, **child**: object): void

**Parameters**

- **t** (object)  
- **i** (int)  
- **child** (object)  


---

#### SetChildIndex

**SetChildIndex**(**t**: object, **index**: int): void

**Parameters**

- **t** (object)  
- **index** (int)  


---

#### SetParent

**SetParent**(**t**: object, **parent**: object): void

**Parameters**

- **t** (object)  
- **parent** (object)  


---

#### SetText

**SetText**(**t**: object, **text**: string): void

**Parameters**

- **t** (object)  
- **text** (string)  


---

#### SetTokenBoundaries

**SetTokenBoundaries**(**t**: object, **startToken**: [IToken](../IToken.md), **stopToken**: [IToken](../IToken.md)): void

**Parameters**

- **t** (object)  
- **startToken** ([IToken](../IToken.md))  
- **stopToken** ([IToken](../IToken.md))  


---

#### SetType

**SetType**(**t**: object, **type**: int): void

**Parameters**

- **t** (object)  
- **type** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **uniqueNodeID** | int |  |
