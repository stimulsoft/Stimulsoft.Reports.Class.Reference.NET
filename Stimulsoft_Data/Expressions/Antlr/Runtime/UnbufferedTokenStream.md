---
title: "UnbufferedTokenStream Class"
---

## UnbufferedTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class UnbufferedTokenStream
```

### Inheritance

Inherits from: Misc.LookaheadStream<[IToken](IToken.md)>  
Implements: [ITokenStream](ITokenStream.md), [ITokenStreamInformation](ITokenStreamInformation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **UnbufferedTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **channel** | int |  |
| **tokenIndex** | int |  |
| **tokenSource** | [ITokenSource](ITokenSource.md) |  |
