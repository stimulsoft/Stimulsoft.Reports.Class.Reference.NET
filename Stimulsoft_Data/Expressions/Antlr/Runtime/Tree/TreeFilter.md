---
title: "TreeFilter Class"
---

## TreeFilter Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class TreeFilter
```

### Inheritance

Inherits from: [TreeParser](TreeParser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeFilter**([ITreeNodeStream](ITreeNodeStream.md) input) |  |
| **TreeFilter**([ITreeNodeStream](ITreeNodeStream.md) input, [RecognizerSharedState](../RecognizerSharedState.md) state) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyOnce** | void |  |
| **Bottomup** | void |  |
| **Downup** | void |  |
| **Topdown** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **originalAdaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **originalTokenStream** | [ITokenStream](../ITokenStream.md) |  |
