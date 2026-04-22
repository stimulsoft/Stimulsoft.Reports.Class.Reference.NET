---
title: "TokenRewriteStream Class"
---

## TokenRewriteStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class TokenRewriteStream
```

### Inheritance

Inherits from: [CommonTokenStream](CommonTokenStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `TokenRewriteStream()` |  |
| `TokenRewriteStream([ITokenSource](ITokenSource.md) tokenSource)` |  |
| `TokenRewriteStream([ITokenSource](ITokenSource.md) tokenSource, int channel)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CatOpText** | string |  |
| **Delete** *(+5 overloads)* | void |  |
| **DeleteProgram** *(+1 overloads)* | void |  |
| **Execute** *(+2 overloads)* | int |  |
| **GetKindOfOps** *(+1 overloads)* | IList<RewriteOperation> |  |
| **GetLastRewriteTokenIndex** *(+1 overloads)* | int |  |
| **GetProgram** | IList<RewriteOperation> |  |
| **Init** | void |  |
| **InsertAfter** *(+3 overloads)* | void |  |
| **InsertBefore** *(+3 overloads)* | void |  |
| **Replace** *(+5 overloads)* | void |  |
| **Rollback** *(+1 overloads)* | void |  |
| **SetLastRewriteTokenIndex** | void |  |
| **ToDebugString** *(+1 overloads)* | string |  |
| **ToOriginalString** *(+1 overloads)* | string |  |
| **ToString** *(+5 overloads)* | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DEFAULT_PROGRAM_NAME** | string |  |
| **MIN_TOKEN_INDEX** | int |  |
| **PROGRAM_INIT_SIZE** | int |  |
| **index** | int |  |
| **instructionIndex** | int |  |
| **lastIndex** | int |  |
| **stream** | [TokenRewriteStream](TokenRewriteStream.md) |  |
| **text** | object |  |
