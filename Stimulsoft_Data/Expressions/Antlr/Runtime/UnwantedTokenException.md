---
title: "UnwantedTokenException Class"
---

## UnwantedTokenException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class UnwantedTokenException
```

### Inheritance

Inherits from: [MismatchedTokenException](MismatchedTokenException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **UnwantedTokenException**() |  |
| **UnwantedTokenException**(string message) |  |
| **UnwantedTokenException**(string message, Exception innerException) |  |
| **UnwantedTokenException**(int expecting, [IIntStream](IIntStream.md) input) |  |
| **UnwantedTokenException**(SerializationInfo info, StreamingContext context) |  |
| **UnwantedTokenException**(int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames) |  |
| **UnwantedTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames) |  |
| **UnwantedTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames, Exception innerException) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string |  |
