---
title: "UnbufferedTokenStream Class"
---

## UnbufferedTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: Misc.LookaheadStream<[IToken](IToken.md)>  
Implements: [ITokenStream](ITokenStream.md), [ITokenStreamInformation](ITokenStreamInformation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **UnbufferedTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |

**UnbufferedTokenStream**(**tokenSource**: [ITokenSource](ITokenSource.md))

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Consume** | void |  |
| **Get** | [IToken](IToken.md) |  |
| **IsEndOfFile** | bool |  |
| **LA** | int |  |
| **Mark** | int |  |
| **NextElement** | [IToken](IToken.md) |  |
| **Release** | void |  |
| **ToString** *(+1 overloads)* | string |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### Consume

**Consume**(): void


---

#### Get

**Get**(**i**: int): [IToken](IToken.md)

**Parameters**

- **i** (int)  

**Returns** [IToken](IToken.md)


---

#### IsEndOfFile

**IsEndOfFile**(**o**: [IToken](IToken.md)): bool

**Parameters**

- **o** ([IToken](IToken.md))  

**Returns** bool


---

#### LA

**LA**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### Mark

**Mark**(): int

**Returns** int


---

#### NextElement

**NextElement**(): [IToken](IToken.md)

**Returns** [IToken](IToken.md)


---

#### Release

**Release**(**marker**: int): void

**Parameters**

- **marker** (int)  


---

#### ToString

**ToString**(**start**: int, **stop**: int): string

**Parameters**

- **start** (int)  
- **stop** (int)  

**Returns** string

---

**ToString**(**start**: [IToken](IToken.md), **stop**: [IToken](IToken.md)): string

**Parameters**

- **start** ([IToken](IToken.md))  
- **stop** ([IToken](IToken.md))  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **channel** | int |  |
| **tokenIndex** | int |  |
| **tokenSource** | [ITokenSource](ITokenSource.md) |  |
