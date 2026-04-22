---
title: "RewriteRuleElementStream Class"
---

## RewriteRuleElementStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public abstract class RewriteRuleElementStream
```

### Constructors

| Constructor | Description |
| --- | --- |
| `RewriteRuleElementStream([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription)` |  |
| `RewriteRuleElementStream([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, object oneElement)` |  |
| `RewriteRuleElementStream([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, IList elements)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **Dup** | object |  |
| **NextCore** | object |  |
| **NextTree** | object |  |
| **Reset** | void |  |
| **ToTree** | object |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **cursor** | int |  |
| **dirty** | bool |  |
| **elementDescription** | string |  |
| **elements** | IList |  |
| **singleElement** | object |  |
