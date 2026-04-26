---
title: "CommonTree Class"
---

## CommonTree Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [BaseTree](BaseTree.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **CommonTree**() |  |
| **CommonTree**([CommonTree](CommonTree.md) node) |  |
| **CommonTree**([IToken](../IToken.md) t) |  |

**CommonTree**()

---

**CommonTree**(**node**: [CommonTree](CommonTree.md))

**Parameters**

- **node** ([CommonTree](CommonTree.md))  

---

**CommonTree**(**t**: [IToken](../IToken.md))

**Parameters**

- **t** ([IToken](../IToken.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DupNode** | [ITree](ITree.md) |  |
| **SetUnknownTokenBoundaries** | void |  |
| **ToString** | string |  |

---

### Method Details

#### DupNode

**DupNode**(): [ITree](ITree.md)

**Returns** [ITree](ITree.md)


---

#### SetUnknownTokenBoundaries

**SetUnknownTokenBoundaries**(): void


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **startIndex** | int |  |
| **stopIndex** | int |  |
