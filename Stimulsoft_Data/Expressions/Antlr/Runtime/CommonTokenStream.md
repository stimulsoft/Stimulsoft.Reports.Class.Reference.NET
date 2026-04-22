---
title: "CommonTokenStream Class"
---

## CommonTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class CommonTokenStream
```

### Inheritance

Inherits from: [BufferedTokenStream](BufferedTokenStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **CommonTokenStream**() |  |
| **CommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |
| **CommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource, int channel) |  |

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
