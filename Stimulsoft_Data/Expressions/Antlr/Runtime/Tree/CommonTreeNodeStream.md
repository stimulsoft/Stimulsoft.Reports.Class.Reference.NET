---
title: "CommonTreeNodeStream Class"
---

## CommonTreeNodeStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class CommonTreeNodeStream
```

### Inheritance

Inherits from: Misc.LookaheadStream<object>  
Implements: [ITreeNodeStream](ITreeNodeStream.md), [IPositionTrackingStream](IPositionTrackingStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `CommonTreeNodeStream(object tree)` |  |
| `CommonTreeNodeStream([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dequeue** | object |  |
| **GetKnownPositionElement** | object |  |
| **HasPositionInformation** | bool |  |
| **IsEndOfFile** | bool |  |
| **LA** | int |  |
| **NextElement** | object |  |
| **Pop** | int |  |
| **Push** | void |  |
| **ReplaceChildren** | void |  |
| **Reset** | void |  |
| **ToString** | string |  |
| **ToTokenTypeString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DEFAULT_INITIAL_BUFFER_SIZE** | int |  |
| **INITIAL_CALL_STACK_SIZE** | int |  |
| **tokens** | [ITokenStream](../ITokenStream.md) |  |
