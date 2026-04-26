---
title: "BaseTree Class"
---

## BaseTree Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Implements: [ITree](ITree.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BaseTree**() |  |
| **BaseTree**([ITree](ITree.md) node) |  |

**BaseTree**()

---

**BaseTree**(**node**: [ITree](ITree.md))

**Parameters**

- **node** ([ITree](ITree.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddChild** | void |  |
| **AddChildren** | void |  |
| **CreateChildrenList** | IList<[ITree](ITree.md)> |  |
| **DeleteChild** | object |  |
| **DupNode** | [ITree](ITree.md) |  |
| **FreshenParentAndChildIndexes** *(+1 overloads)* | void |  |
| **FreshenParentAndChildIndexesDeeply** *(+1 overloads)* | void |  |
| **GetAncestor** | [ITree](ITree.md) |  |
| **GetAncestors** | IList<[ITree](ITree.md)> |  |
| **GetChild** | [ITree](ITree.md) |  |
| **GetFirstChildWithType** | [ITree](ITree.md) |  |
| **HasAncestor** | bool |  |
| **InsertChild** | void |  |
| **ReplaceChildren** | void |  |
| **SanityCheckParentAndChildIndexes** *(+1 overloads)* | void |  |
| **SetChild** | void |  |
| **ToString** | string |  |
| **ToStringTree** | string |  |

---

### Method Details

#### AddChild

**AddChild**(**t**: [ITree](ITree.md)): void

**Parameters**

- **t** ([ITree](ITree.md))  


---

#### AddChildren

**AddChildren**(**kids**: IEnumerable<[ITree](ITree.md)>): void

**Parameters**

- **kids** (IEnumerable<[ITree](ITree.md)>)  


---

#### CreateChildrenList

**CreateChildrenList**(): IList<[ITree](ITree.md)>

**Returns** IList<[ITree](ITree.md)>


---

#### DeleteChild

**DeleteChild**(**i**: int): object

**Parameters**

- **i** (int)  

**Returns** object


---

#### DupNode

**DupNode**(): [ITree](ITree.md)

**Returns** [ITree](ITree.md)


---

#### FreshenParentAndChildIndexes

**FreshenParentAndChildIndexes**(): void

---

**FreshenParentAndChildIndexes**(**offset**: int): void

**Parameters**

- **offset** (int)  


---

#### FreshenParentAndChildIndexesDeeply

**FreshenParentAndChildIndexesDeeply**(): void

---

**FreshenParentAndChildIndexesDeeply**(**offset**: int): void

**Parameters**

- **offset** (int)  


---

#### GetAncestor

**GetAncestor**(**ttype**: int): [ITree](ITree.md)

**Parameters**

- **ttype** (int)  

**Returns** [ITree](ITree.md)


---

#### GetAncestors

**GetAncestors**(): IList<[ITree](ITree.md)>

**Returns** IList<[ITree](ITree.md)>


---

#### GetChild

**GetChild**(**i**: int): [ITree](ITree.md)

**Parameters**

- **i** (int)  

**Returns** [ITree](ITree.md)


---

#### GetFirstChildWithType

**GetFirstChildWithType**(**type**: int): [ITree](ITree.md)

**Parameters**

- **type** (int)  

**Returns** [ITree](ITree.md)


---

#### HasAncestor

**HasAncestor**(**ttype**: int): bool

**Parameters**

- **ttype** (int)  

**Returns** bool


---

#### InsertChild

**InsertChild**(**i**: int, **t**: [ITree](ITree.md)): void

**Parameters**

- **i** (int)  
- **t** ([ITree](ITree.md))  


---

#### ReplaceChildren

**ReplaceChildren**(**startChildIndex**: int, **stopChildIndex**: int, **t**: object): void

**Parameters**

- **startChildIndex** (int)  
- **stopChildIndex** (int)  
- **t** (object)  


---

#### SanityCheckParentAndChildIndexes

**SanityCheckParentAndChildIndexes**(): void

---

**SanityCheckParentAndChildIndexes**(**parent**: [ITree](ITree.md), **i**: int): void

**Parameters**

- **parent** ([ITree](ITree.md))  
- **i** (int)  


---

#### SetChild

**SetChild**(**i**: int, **t**: [ITree](ITree.md)): void

**Parameters**

- **i** (int)  
- **t** ([ITree](ITree.md))  


---

#### ToString

**ToString**(): string

**Returns** string


---

#### ToStringTree

**ToStringTree**(): string

**Returns** string

