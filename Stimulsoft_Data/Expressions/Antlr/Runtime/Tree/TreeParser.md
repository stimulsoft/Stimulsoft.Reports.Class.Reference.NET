---
title: "TreeParser Class"
---

## TreeParser Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class TreeParser
```

### Inheritance

Inherits from: [BaseRecognizer](../BaseRecognizer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `TreeParser([ITreeNodeStream](ITreeNodeStream.md) input)` |  |
| `TreeParser([ITreeNodeStream](ITreeNodeStream.md) input, [RecognizerSharedState](../RecognizerSharedState.md) state)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCurrentInputSymbol** | object |  |
| **GetErrorHeader** | string |  |
| **GetErrorMessage** | string |  |
| **GetTreeNodeStream** | [ITreeNodeStream](ITreeNodeStream.md) |  |
| **MatchAny** | void |  |
| **RecoverFromMismatchedToken** | object |  |
| **Reset** | void |  |
| **SetTreeNodeStream** | void |  |
| **TraceIn** | void |  |
| **TraceOut** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DOWN** | int |  |
| **UP** | int |  |
| **input** | [ITreeNodeStream](ITreeNodeStream.md) |  |
