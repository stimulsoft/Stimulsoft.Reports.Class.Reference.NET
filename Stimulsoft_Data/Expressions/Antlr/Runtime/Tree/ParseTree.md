---
title: "ParseTree Class"
---

## ParseTree Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [BaseTree](BaseTree.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ParseTree**(object label) |  |

**ParseTree**(**label**: object)

**Parameters**

- **label** (object)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DupNode** | [ITree](ITree.md) |  |
| **ToInputString** | string |  |
| **ToString** | string |  |
| **ToStringLeaves** | void |  |
| **ToStringWithHiddenTokens** | string |  |

---

### Method Details

#### DupNode

**DupNode**(): [ITree](ITree.md)

**Returns** [ITree](ITree.md)


---

#### ToInputString

**ToInputString**(): string

**Returns** string


---

#### ToString

**ToString**(): string

**Returns** string


---

#### ToStringLeaves

**ToStringLeaves**(**buf**: StringBuilder): void

**Parameters**

- **buf** (StringBuilder)  


---

#### ToStringWithHiddenTokens

**ToStringWithHiddenTokens**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **hiddenTokens** | List<[IToken](../IToken.md)> |  |
| **payload** | object |  |
