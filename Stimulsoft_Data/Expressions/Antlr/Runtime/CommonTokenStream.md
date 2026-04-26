---
title: "CommonTokenStream Class"
---

## CommonTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [BufferedTokenStream](BufferedTokenStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **CommonTokenStream**() |  |
| **CommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |
| **CommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource, int channel) |  |

**CommonTokenStream**()

---

**CommonTokenStream**(**tokenSource**: [ITokenSource](ITokenSource.md))

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  

---

**CommonTokenStream**(**tokenSource**: [ITokenSource](ITokenSource.md), **channel**: int)

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  
- **channel** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Consume** | void |  |
| **LB** | [IToken](IToken.md) |  |
| **LT** | [IToken](IToken.md) |  |
| **Reset** | void |  |
| **Setup** | void |  |
| **SkipOffTokenChannels** | int |  |
| **SkipOffTokenChannelsReverse** | int |  |

---

### Method Details

#### Consume

**Consume**(): void


---

#### LB

**LB**(**k**: int): [IToken](IToken.md)

**Parameters**

- **k** (int)  

**Returns** [IToken](IToken.md)


---

#### LT

**LT**(**k**: int): [IToken](IToken.md)

**Parameters**

- **k** (int)  

**Returns** [IToken](IToken.md)


---

#### Reset

**Reset**(): void


---

#### Setup

**Setup**(): void


---

#### SkipOffTokenChannels

**SkipOffTokenChannels**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### SkipOffTokenChannelsReverse

**SkipOffTokenChannelsReverse**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int

