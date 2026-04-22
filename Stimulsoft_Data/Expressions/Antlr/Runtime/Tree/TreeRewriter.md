---
title: "TreeRewriter Class"
---

## TreeRewriter Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class TreeRewriter
```

### Inheritance

Inherits from: [TreeParser](TreeParser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `TreeRewriter([ITreeNodeStream](ITreeNodeStream.md) input)` |  |
| `TreeRewriter([ITreeNodeStream](ITreeNodeStream.md) input, [RecognizerSharedState](../RecognizerSharedState.md) state)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyOnce** | object |  |
| **ApplyRepeatedly** | object |  |
| **Bottomup** | [IAstRuleReturnScope](../IAstRuleReturnScope.md) |  |
| **Downup** *(+1 overloads)* | object |  |
| **ReportTransformation** | void |  |
| **Topdown** | [IAstRuleReturnScope](../IAstRuleReturnScope.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **originalAdaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **originalTokenStream** | [ITokenStream](../ITokenStream.md) |  |
| **showTransformations** | bool |  |
