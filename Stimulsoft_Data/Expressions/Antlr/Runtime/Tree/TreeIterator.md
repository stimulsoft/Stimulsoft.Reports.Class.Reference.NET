---
title: "TreeIterator Class"
---

## TreeIterator Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Implements: IEnumerator<object>  

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeIterator**([CommonTree](CommonTree.md) tree) |  |
| **TreeIterator**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree) |  |

**TreeIterator**(**tree**: [CommonTree](CommonTree.md))

**Parameters**

- **tree** ([CommonTree](CommonTree.md))  

---

**TreeIterator**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **tree**: object)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **tree** (object)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **MoveNext** | bool |  |
| **Reset** | void |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### MoveNext

**MoveNext**(): bool

**Returns** bool


---

#### Reset

**Reset**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **down** | object |  |
| **eof** | object |  |
| **firstTime** | bool |  |
| **nodes** | Queue<object> |  |
| **root** | object |  |
| **tree** | object |  |
| **up** | object |  |
