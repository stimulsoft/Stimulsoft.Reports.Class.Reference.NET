---
title: "LegacyCommonTokenStream Class"
---

## LegacyCommonTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Implements: [ITokenStream](ITokenStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LegacyCommonTokenStream**() |  |
| **LegacyCommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |
| **LegacyCommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource, int channel) |  |

**LegacyCommonTokenStream**()

---

**LegacyCommonTokenStream**(**tokenSource**: [ITokenSource](ITokenSource.md))

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  

---

**LegacyCommonTokenStream**(**tokenSource**: [ITokenSource](ITokenSource.md), **channel**: int)

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  
- **channel** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Consume** | void |  |
| **DiscardTokenType** | void |  |
| **FillBuffer** | void |  |
| **Get** *(+1 overloads)* | [IToken](IToken.md) |  |
| **GetTokens** *(+4 overloads)* | IList<[IToken](IToken.md)> |  |
| **LA** | int |  |
| **LB** | [IToken](IToken.md) |  |
| **LT** | [IToken](IToken.md) |  |
| **Mark** | int |  |
| **Release** | void |  |
| **Reset** | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **SetDiscardOffChannelTokens** | void |  |
| **SetTokenSource** | void |  |
| **SetTokenTypeChannel** | void |  |
| **SkipOffTokenChannels** | int |  |
| **SkipOffTokenChannelsReverse** | int |  |
| **ToString** *(+2 overloads)* | string |  |

---

### Method Details

#### Consume

**Consume**(): void


---

#### DiscardTokenType

**DiscardTokenType**(**ttype**: int): void

**Parameters**

- **ttype** (int)  


---

#### FillBuffer

**FillBuffer**(): void


---

#### Get

**Get**(**i**: int): [IToken](IToken.md)

**Parameters**

- **i** (int)  

**Returns** [IToken](IToken.md)

---

**Get**(**start**: int, **count**: int): List<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **count** (int)  

**Returns** List<[IToken](IToken.md)>


---

#### GetTokens

**GetTokens**(): IList<[IToken](IToken.md)>

**Returns** IList<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int): IList<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  

**Returns** IList<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int, **types**: [BitSet](BitSet.md)): IList<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  
- **types** ([BitSet](BitSet.md))  

**Returns** IList<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int, **types**: IList<int>): IList<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  
- **types** (IList<int>)  

**Returns** IList<[IToken](IToken.md)>

---

**GetTokens**(**start**: int, **stop**: int, **ttype**: int): IList<[IToken](IToken.md)>

**Parameters**

- **start** (int)  
- **stop** (int)  
- **ttype** (int)  

**Returns** IList<[IToken](IToken.md)>


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

#### SetDiscardOffChannelTokens

**SetDiscardOffChannelTokens**(**discardOffChannelTokens**: bool): void

**Parameters**

- **discardOffChannelTokens** (bool)  


---

#### SetTokenSource

**SetTokenSource**(**tokenSource**: [ITokenSource](ITokenSource.md)): void

**Parameters**

- **tokenSource** ([ITokenSource](ITokenSource.md))  


---

#### SetTokenTypeChannel

**SetTokenTypeChannel**(**ttype**: int, **channel**: int): void

**Parameters**

- **ttype** (int)  
- **channel** (int)  


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
| **channel** | int |  |
| **discardOffChannelTokens** | bool |  |
| **discardSet** | List<int> |  |
| **lastMarker** | int |  |
| **p** | int |  |
| **tokens** | List<[IToken](IToken.md)> |  |
