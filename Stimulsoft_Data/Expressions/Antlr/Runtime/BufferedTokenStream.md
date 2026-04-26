---
title: "BufferedTokenStream Class"
---

## BufferedTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Implements: [ITokenStream](ITokenStream.md), [ITokenStreamInformation](ITokenStreamInformation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BufferedTokenStream**() |  |
| **BufferedTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |

**BufferedTokenStream**()

---

**BufferedTokenStream**(**tokenSource**: [ITokenSource](ITokenSource.md))

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Consume** | void |  |
| **Fetch** | void |  |
| **Fill** | void |  |
| **Get** *(+1 overloads)* | [IToken](IToken.md) |  |
| **GetTokens** *(+4 overloads)* | List<[IToken](IToken.md)> |  |
| **LA** | int |  |
| **LB** | [IToken](IToken.md) |  |
| **LT** | [IToken](IToken.md) |  |
| **Mark** | int |  |
| **Release** | void |  |
| **Reset** | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **Setup** | void |  |
| **Sync** | void |  |
| **ToString** *(+2 overloads)* | string |  |

---

### Method Details

#### Consume

**Consume**(): void


---

#### Fetch

**Fetch**(**n**: int): void

**Parameters**

- **n** (int)  


---

#### Fill

**Fill**(): void


---

#### Get

**Get**(**i**: int): [IToken](IToken.md)

**Parameters**

- **i** (int)  

**Returns** [IToken](IToken.md)

---

**Get**(**start**: int, **count**: int): List<[IToken](IToken.md)>

Get all tokens from start..(start+count-1) inclusively

**Parameters**

- **start** (int)  
- **count** (int)  

**Returns** List<[IToken](IToken.md)>


---

#### GetTokens

**GetTokens**(): List<[IToken](IToken.md)>

**Returns** List<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int): List<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  

**Returns** List<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int, **types**: [BitSet](BitSet.md)): List<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  
- **types** ([BitSet](BitSet.md))  

**Returns** List<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int, **types**: IEnumerable<int>): List<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  
- **types** (IEnumerable<int>)  

**Returns** List<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int, **ttype**: int): List<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  
- **ttype** (int)  

**Returns** List<[IToken](IToken.md)>


---

#### LA

**LA**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


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

#### Mark

**Mark**(): int

**Returns** int


---

#### Release

**Release**(**marker**: int): void

**Parameters**

- **marker** (int)  


---

#### Reset

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

#### Setup

**Setup**(): void


---

#### Sync

**Sync**(**i**: int): void

**Parameters**

- **i** (int)  


---

#### ToString

**ToString**(): string

**Returns** string

---

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
| **_p** | int |  |
| **_tokens** | List<[IToken](IToken.md)> |  |
