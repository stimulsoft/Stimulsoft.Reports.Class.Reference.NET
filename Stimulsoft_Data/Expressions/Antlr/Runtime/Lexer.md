---
title: "Lexer Class"
---

## Lexer Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public abstract class Lexer
```

### Inheritance

Inherits from: [BaseRecognizer](BaseRecognizer.md)  
Implements: [ITokenSource](ITokenSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **Lexer**() |  |
| **Lexer**([ICharStream](ICharStream.md) input) |  |
| **Lexer**([ICharStream](ICharStream.md) input, [RecognizerSharedState](RecognizerSharedState.md) state) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Emit** *(+1 overloads)* | void |  |
| **GetCharErrorDisplay** | string |  |
| **GetEndOfFileToken** | [IToken](IToken.md) |  |
| **GetErrorMessage** | string |  |
| **Match** *(+1 overloads)* | void |  |
| **MatchAny** | void |  |
| **MatchRange** | void |  |
| **NextToken** | [IToken](IToken.md) |  |
| **ParseNextToken** | void |  |
| **Recover** | void |  |
| **ReportError** | void |  |
| **Reset** | void |  |
| **Skip** | void |  |
| **TraceIn** | void |  |
| **TraceOut** | void |  |
| **mTokens** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **input** | [ICharStream](ICharStream.md) |  |
