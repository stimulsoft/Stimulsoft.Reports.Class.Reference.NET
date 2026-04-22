---
title: "BufferedTokenStream Class"
---

## BufferedTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class BufferedTokenStream
```

### Inheritance

Implements: [ITokenStream](ITokenStream.md), [ITokenStreamInformation](ITokenStreamInformation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BufferedTokenStream**() |  |
| **BufferedTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **_p** | int |  |
| **_tokens** | List<[IToken](IToken.md)> |  |
