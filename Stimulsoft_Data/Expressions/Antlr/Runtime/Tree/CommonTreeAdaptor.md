---
title: "CommonTreeAdaptor Class"
---

## CommonTreeAdaptor Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [BaseTreeAdaptor](BaseTreeAdaptor.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** | object |  |
| **CreateToken** *(+1 overloads)* | [IToken](../IToken.md) |  |
| **GetToken** | [IToken](../IToken.md) |  |

---

### Method Details

#### Create

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

#### GetToken

**GetToken**(**t**: object): [IToken](../IToken.md)

**Parameters**

- **t** (object)  

**Returns** [IToken](../IToken.md)

