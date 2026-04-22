---
title: "LegacyCommonTokenStream Class"
---

## LegacyCommonTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class LegacyCommonTokenStream
```

### Inheritance

Implements: [ITokenStream](ITokenStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **LegacyCommonTokenStream**() |  |
| **LegacyCommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource) |  |
| **LegacyCommonTokenStream**([ITokenSource](ITokenSource.md) tokenSource, int channel) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **channel** | int |  |
| **discardOffChannelTokens** | bool |  |
| **discardSet** | List<int> |  |
| **lastMarker** | int |  |
| **p** | int |  |
| **tokens** | List<[IToken](IToken.md)> |  |
